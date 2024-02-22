# Enhanced Machine Translation for Video Subtitling

## Introduction

This project aims to revolutionize the translation process for cinema and streaming content by developing a machine translation system capable of converting English audio into Hebrew subtitles. By leveraging neural machine translation (NMT) and a novel two-layer model

## Data Collection and Cleaning

We begin with an extensive data collection phase, gathering subtitles from a wide range of movies and series. This raw data is then cleaned and refined to ensure high-quality translations. Our approach focuses on complete sentence translations in both the source and target languages to capture cultural expressions, idioms, and linguistic complexities accurately.

## Model Training

Our system features a dual-layer translation model. The first layer utilizes existing NMT models for foundational translation, while the second layer, trained on our curated dataset, refines these translations. This innovative approach allows for continuous learning and adaptation to new linguistic patterns.

## Features

- **Dual-layer Neural Machine Translation**: A combination of existing models and our custom-trained NMT ensures superior translation accuracy.
- **Automated Data Cleaning**: Advanced algorithms prepare and refine the dataset for translation.
- **Contextual Accuracy**: Emphasizes local idioms, cultural nuances, and complex linguistic structures for natural-feeling translations.

## Setting Up the Project

### Creating a Virtual Environment

First, install `virtualenv` if you haven't already:

```bash
py -m pip install --user virtualenv
```

Then, create a virtual environment:

```bash
py -m venv env
```

Activate the virtual environment:

On Windows:

```bash
.\env\Scripts\activate
```

On Unix or MacOS:

```bash
source env/bin/activate
```


Handling Errors with Pytube
If you encounter errors with the Pytube module, here are fixes for common issues:

Error 1: If you run into XML to SRT conversion issues, a solution can be found on Stack Overflow. Search for "xml to srt conversion not working after installing pytube" for detailed instructions.

Error 2: For issues related to RegexMatchError with Pytube, another Stack Overflow thread titled "Pytube exceptions RegexMatchError: get_throttling_function_name: could not find" provides a solution.


Contributors

Guy Dahan
Lior Elisberg

[Final Project - Movie Subtitle Generator PDF](https://github.com/GuyDahan1/EngToHeb-Movie-Subtitle-Generator/blob/master/Final%20Project%20-%20Movie%20Subtitle%20Generator.pdf)
