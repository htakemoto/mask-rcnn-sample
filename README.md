# Mask RCNN Sample

Matterport Mask RCNN Implementation

- Kangaroo Detection
- Nuclei Detection

## Setup (Google Colab)

Simply just open one of the following Jupyter Notebook files:

- mask-rcnn-kangaroo.ipynb
- mask-rcnn-nuclei.ipynb

## Setup (Local)

### Requirements

- pyenv
- pipenv

### Install dependencies

```bash
pipenv install
```

Enable jupyter extension (optional)

```bash
pipenv run jupyter contrib nbextension install --sys-prefix
pipenv run jupyter nbextensions_configurator enable --sys-prefix
```

### Start

```bash
pipenv run start
```
