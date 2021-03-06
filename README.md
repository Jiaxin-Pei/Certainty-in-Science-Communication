# Certainty-in-Science-Communication

Official Github Repo for EMNLP 2021 paper [Measuring Sentence-Level and Aspect-Level (Un)certainty in Science Communications]() by [Jiaxin Pei](https://jiaxin-pei.github.io/) and [David Jurgens](https://jurgens.people.si.umich.edu/).

## Data
### Annotated scientific findings with sentence-level and aspect-level certainty: 
`data/annotated_data` 

### The URLs of science news and research papers used in our analysis
`data/urls`
contains 128942 news mentions of 57807 papers. We release URLs for news and DOIs for papers.

## Code
### Python pacakge for certainty prediction
If `pip` is installed, certainty-estimator could be installed directly via [pip](https://pypi.org/project/certainty-estimator/):
```
pip3 install certainty-estimator
```
Please check this [Github repo](https://github.com/Jiaxin-Pei/certainty-estimator) for code and examples.

### Pre-trained model
We use Hugging Face to host both the [sentence-level](https://huggingface.co/pedropei/sentence-level-certainty) and [aspect-level](https://huggingface.co/pedropei/aspect-level-certainty) prediction models.

### Code to train the model

If you only need to use the certainty prediction model, please checkout our [python package](https://pypi.org/project/certainty-estimator/).
We use [Hugging Face Transformers](https://huggingface.co/transformers/model_doc/bert.html#bertforsequenceclassification) to train our models. 
Please email Jiaxin Pei (pedropei@umich.edu) if you need our code to train the certainty prediction models.

## Contact
Jiaxin Pei (pedropei@umich.edu)
