# Tracking Carbon Emissions for your NeuCLIR Submission

NeuCLIR aims to be the first carbon-neutral track at TREC.
In order to do so, we are encouraging all participants to track and report carbon emissions they generated while preparing their submission.

We also encourage participants to buy offsets for the emissions they produced; it is more affordable than you think!

On this page, we provide resources that explain both how to track and buy carbon offsets; **Offsetting your emissions is cheaper than you think!** For example, 2 weeks of compute on a [`p4d.24xlarge`](https://aws.amazon.com/ec2/instance-types/p4/) AWS instance in [`us-east-1`](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html) emit ~250 kg CO2 eq., which can be offset by as little as *4 USD* when donating to [UN's Efficient Cook Stove Programme in Kenya](https://offset.climateneutralnow.org/efficient-cook-stove-programme-kenya-5336-?searchResultsLink=%2Fallprojects).

## Background

Most aspect of submitting a run to a TREC track generate carbon emissions: from the resources used to train neural models, to the power required to transfer data over the internet, to the energy used by the device you are using right now to read this page!
However, the energy used for model training and parameter search is typically responsible for the bulk of carbon emission generated (Strubell et al., 2020).

Carbon emissions created during model training depend primarily on three factors (Luccioni 2021):

1. **Type of energy used**: depending on the region where the infrastructure used to train a model is located, emissions can vary by more than 30 times (Lacoste et al., 2019); this is due to the mix of sustainable- and fossil fuel-derived evergy in each region. Models trained on devices that use reneweable energy will have a lesser impact on the environment.
2. **How long a model is trained for**: models that are trained for longer time require more energy, thus leading to higher emissions.
3. **Hardware**: different types of hardware accelerators (e.g., [GPUs](https://en.wikipedia.org/wiki/Graphics_processing_unit), [TPUs](https://en.wikipedia.org/wiki/Tensor_Processing_Unit)) will have different power requirements. Recent architectures are typically more efficient, thanks to the inclusion of AI-specific components (e.g., NVIDIA's [Tensor Cores](https://www.nvidia.com/en-us/data-center/tensor-cores/)).

When possible, we recommend participants to choose location and hardware that have the lowest footprint. The calculator on [this page](https://mlco2.github.io/impact/) can help assessing the best option.

## Tracking Emissions

We recommend participants to use [CodeCarbon](https://codecarbon.io), a python package designed to track emissions for machine learning experiments. It can be installed via:

```bash
pip install codecarbon
```

Once installed, the impact of an experiment can be estimated as follows:

```python
from codecarbon import EmissionsTracker

tracker = EmissionsTracker(output_dir='co2')
tracker.start()

# Training loop and other gpu-intensive
# code goes here...

tracker.stop()
```

The code above will save a csv file in the directory `co2` called `emissions.csv`. For more information about how to use CodeCarbon, please check out the [official documentation](https://mlco2.github.io/codecarbon/index.html).


In case experiments cannot be tracked with the package above, or participants have trouble setting up CodeCarbon, we recommend using [this ML CO2 impact calculator](https://mlco2.github.io/impact/).

## Buying Carbon Offsets

Inspired by CILVR (2021), we recommend participants to consult the [United Nations Carbon Offsets Platform](https://offset.climateneutralnow.org) to learn more on how to buy carbon offsets. This program highlights [plenty of initiatives](https://offset.climateneutralnow.org/allprojects) around the planet aimed at reducing carbon emission; each initiative offers a donation rate per tonne of CO2 emitted. After each donation, an official [certificate of voluntary cancellation](https://offset.climateneutralnow.org/Plugins/CarbonOffsetPlatform.Website/Theme/Content/images/offset/certificatePreview.PNG) is issues via email.


## References

- CILVR. "Carbon Neutral Lab." 2021. Last accessed<br/>2022-01-28. <a href='https://wp.nyu.edu/cilvr/carbon-neutral-lab/' title='link'>Link <i aria-hidden="true" class="fas fa-link"></i></a>;  <a href='https://web.archive.org/web/20201031231203/https://wp.nyu.edu/cilvr/carbon-neutral-lab/' title='backup link'>backup <i aria-hidden="true" class="fas fa-history"></i></a>.
- Alexandre Lacoste, Alexandra Luccioni, Victor Schmidt, Thomas Dandres. "Quantifying the Carbon Emissions of Machine Learning." Tackling Climate Change with Machine Learning Workshop, NeurIPS, 2019.<br/><a href='https://www.climatechange.ai/papers/neurips2019/22' title='link'>Link <i aria-hidden="true" class="fas fa-link"></i></a>;  <a href='https://arxiv.org/abs/1910.09700' title='pdf mascucript'>PDF <i aria-hidden="true" class="fas fa-file-pdf"></i></a>.
- Sasha Luccioni. "The carbon footprint of Transformers." Youtube 2021. Last accessed 2022-01-28. <br/><a href='https://www.youtube.com/watch?v=ftWlj4FBHTg' title='link'>Link <i aria-hidden="true" class="fas fa-link"></i></a>;  <a href='https://web.archive.org/web/20211118174124/https://www.youtube.com/watch?v=ftWlj4FBHTg' title='backup link'>backup <i aria-hidden="true" class="fas fa-history"></i></a>.
- Strubell, Emma, Ananya Ganesh and Andrew McCallum. “Energy and Policy Considerations for Modern Deep Learning Research.” AAAI 2020. <a href='https://ojs.aaai.org//index.php/AAAI/article/view/7123' title='link'>Link <i aria-hidden="true" class="fas fa-link"></i></a>;  <a href='https://ojs.aaai.org/index.php/AAAI/article/view/7123/6977' title='pdf mascucript'>PDF <i aria-hidden="true" class="fas fa-file-pdf"></i></a>.