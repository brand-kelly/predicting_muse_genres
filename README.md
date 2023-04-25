---

---






# Model Card for Deep Learning Network for Predicting Music Genre and Energy Level

<!-- Provide a quick summary of what the model is/does. [Optional] -->
With the high quantity of music being released in this digital age, Music Genre Recognition (MGR) has become an increasingly important task. Many existing MGR models using deep learning have demonstrated success in classifying songs from their audio files. However, we wanted to create a deep learning model that would not only be limited to MGR, but can also predict the energy rating of a song. We believe that such a network could have an additional practical use regarding user recommendations, as the combination of genre and energy level can be an important factor of one’s choice of music.




#  Table of Contents

- [Model Card for Deep Learning Network for Predicting Music Genre and Energy Level](#model-card-for--model_id-)
- [Table of Contents](#table-of-contents)
- [Table of Contents](#table-of-contents-1)
- [Model Details](#model-details)
  - [Model Description](#model-description)
- [Uses](#uses)
  - [Direct Use](#direct-use)
  - [Downstream Use [Optional]](#downstream-use-optional)
  - [Out-of-Scope Use](#out-of-scope-use)
- [Bias, Risks, and Limitations](#bias-risks-and-limitations)
  - [Recommendations](#recommendations)
- [Training Details](#training-details)
  - [Training Data](#training-data)
  - [Training Procedure](#training-procedure)
    - [Preprocessing](#preprocessing)
    - [Speeds, Sizes, Times](#speeds-sizes-times)
- [Evaluation](#evaluation)
  - [Testing Data, Factors & Metrics](#testing-data-factors--metrics)
    - [Testing Data](#testing-data)
    - [Factors](#factors)
    - [Metrics](#metrics)
  - [Results](#results)
- [Model Examination](#model-examination)
- [Environmental Impact](#environmental-impact)
- [Technical Specifications [optional]](#technical-specifications-optional)
  - [Model Architecture and Objective](#model-architecture-and-objective)
  - [Compute Infrastructure](#compute-infrastructure)
    - [Hardware](#hardware)
    - [Software](#software)
- [Citation](#citation)
- [Glossary [optional]](#glossary-optional)
- [More Information [optional]](#more-information-optional)
- [Model Card Authors [optional]](#model-card-authors-optional)
- [Model Card Contact](#model-card-contact)
- [How to Get Started with the Model](#how-to-get-started-with-the-model)


# Model Details

## Model Description

<!-- Provide a longer summary of what this model is/does. -->
With the high quantity of music being released in this digital age, Music Genre Recognition (MGR) has become an increasingly important task. Many existing MGR models using deep learning have demonstrated success in classifying songs from their audio files. However, we wanted to create a deep learning model that would not only be limited to MGR, but can also predict the energy rating of a song. We believe that such a network could have an additional practical use regarding user recommendations, as the combination of genre and energy level can be an important factor of one’s choice of music.

- **Developed by:** More information needed
    - Anaya Mehta
    - Brandon Kelly
    - Yun Luk Liu
    - Wenhan Lee
- **Model type:** Language model
- **Language(s) (NLP):** en
- **License:** mit
- **Resources for more information:**
    - [FMA's GitHub Repo](https://github.com/mdeff/fma)
    - [FMA's Associated Paper](https://arxiv.org/abs/1612.01840)

# Uses

<!-- Address questions around how the model is intended to be used, including the foreseeable users of the model and those affected by the model. -->

## Direct Use

<!-- This section is for the model use without fine-tuning or plugging into a larger ecosystem/app. -->
<!-- If the user enters content, print that. If not, but they enter a task in the list, use that. If neither, say "more info needed." -->

This model could be used in music recommendation systems, music curation and organization, music synchronization, genre and energy-level-based music categorization, and more.


## Downstream Use [Optional]

<!-- This section is for the model use when fine-tuned for a task, or when plugged into a larger ecosystem/app -->
<!-- If the user enters content, print that. If not, but they enter a task in the list, use that. If neither, say "more info needed." -->
 



## Out-of-Scope Use

<!-- This section addresses misuse, malicious use, and uses that the model will not work well for. -->
<!-- If the user enters content, print that. If not, but they enter a task in the list, use that. If neither, say "more info needed." -->

Audio recognition outside of music, generating new audio, music identification, non-audio data processing, and other similar task.


# Bias, Risks, and Limitations

<!-- This section is meant to convey both technical and sociotechnical limitations. -->



## Recommendations

<!-- This section is meant to convey recommendations with respect to the bias, risk, and technical limitations. -->





# Training Details

## Training Data

<!-- This should link to a Data Card, perhaps with a short stub of information on what the training data is all about as well as documentation related to data pre-processing or additional filtering. -->

The training data used was from Free Music Archive&#39;s open dataset GitHub page.


## Training Procedure

<!-- This relates heavily to the Technical Specifications. Content here should link to that section when it is relevant to the training procedure. -->

### Preprocessing

More information needed

### Speeds, Sizes, Times

<!-- This section provides information about throughput, start/end time, checkpoint size if relevant, etc. -->

More information needed
 
# Evaluation

<!-- This section describes the evaluation protocols and provides the results. -->

## Testing Data, Factors & Metrics

### Testing Data

<!-- This should link to a Data Card if possible. -->

More information needed


### Factors

<!-- These are the things the evaluation is disaggregating by, e.g., subpopulations or domains. -->

More information needed

### Metrics

<!-- These are the evaluation metrics being used, ideally with a description of why. -->

More information needed

## Results 

More information needed

# Model Examination

More information needed

# Environmental Impact

<!-- Total emissions (in grams of CO2eq) and additional considerations, such as electricity usage, go here. Edit the suggested text below accordingly -->

Carbon emissions can be estimated using the [Machine Learning Impact calculator](https://mlco2.github.io/impact#compute) presented in [Lacoste et al. (2019)](https://arxiv.org/abs/1910.09700).

- **Hardware Type:** More information needed
- **Hours used:** More information needed
- **Cloud Provider:** More information needed
- **Compute Region:** More information needed
- **Carbon Emitted:** More information needed

# Technical Specifications [optional]

## Model Architecture and Objective

Multi-layers Convolutional Recurrent Neural Network.

## Compute Infrastructure

### Hardware
- CPU: Google Colab's provided base CPU
- RAM: Google Colab's provided base 12GB RAM

### Software
- Jupyter Notebook
- PyTorch
- NumPy
- Pandas
- SciPy
- Librosa
- Matplotlib
- IPython
- Sklearn

# Citation

<!-- If there is a paper or blog post introducing the model, the APA and Bibtex information for that should go in this section. -->

**BibTeX:**


**APA:**

# Glossary [optional]

<!-- If relevant, include terms and calculations in this section that can help readers understand the model or model card. -->

More information needed

# More Information [optional]

More information needed

# Model Card Authors [optional]

<!-- This section provides another layer of transparency and accountability. Whose views is this model card representing? How many voices were included in its construction? Etc. -->

  - Brandon Kelly

# Model Card Contact

More information needed

# How to Get Started with the Model

Use the code below to get started with the model.

<details>
<summary> Click to expand </summary>

More information needed

</details>
