[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hibernator11/notebook-texts-example/master)

[![DOI](https://zenodo.org/badge/252769662.svg)](https://zenodo.org/badge/latestdoi/252769662)

# notebook-texts-metadata
This project includes several notebooks to exploit GLAM datasets that contain text and metadata. 

## dataset-extraction-images
This [notebook](dataset-extraction-images.ipynb) extracts a dataset as a CSV file from a digital collection described using MARCXML files. [View notebook in nbviewer](https://nbviewer.jupyter.org/github/hibernator11/notebook-marc-csv-example/blob/master/Dataset-Extraction-Example.ipynb)

We use [Data Package](https://specs.frictionlessdata.io/data-package/) as a simple container format for describing a coherent collection of data in a single 'package'. It provides the basis for convenient delivery, installation and management of datasets.

This notebook uses a dataset of descriptive metadata from the [Moving Image Archive catalogue](https://data.nls.uk/data/metadata-collections/moving-image-archive/), which is Scotland’s national collection of moving images.

## topic-modeling-billing
This [notebook](topic-modeling-billing.ipynb) extracts the most common words in a corpus of text documents. This notebook is an example of Topic Modeling based on Digitised Volumes of theatrical English, Scottish, and Irish playbills between 1600 - 1902 from [data.bl.uk](data.bl.uk). [View notebook in nbviewer](https://nbviewer.jupyter.org/github/hibernator11/notebook-marc-csv-example/blob/master/topic-modeling-billing.ipynb)

![Topic modeling](images/topic-modeling.png)

# References
The [GLAM Workbench](https://glam-workbench.github.io/) has been used as inspiration to create this example. In particular, the notebook [Exploring metadata harvested from the Tribune negative collection in the State Library of NSW](https://nbviewer.jupyter.org/github/GLAM-Workbench/ozglam-data-records-of-resistance/blob/master/Exploring-Tribune-negatives-metadata.ipynb).


Theatrical playbills from Britain and Ireland (OCR text only) Optically Character Recognised (OCR)-derived text for the playbills, encoded in UTF-8. DOI: https://doi.org/10.21250/pb2
