# Going Denser with Open-Vocabulary Part Segmentation

![](docs/boom.png)

Object detection has been expanded from a limited number of categories to open vocabulary. 
Moving forward, a complete intelligent vision system requires understanding more fine-grained object descriptions, object parts. 
In this work, we propose a detector with the ability to predict both open-vocabulary objects and their part segmentation.
This ability comes from two designs:
- We train the detector on the joint of part-level, object-level and image-level data. 
- We parse the novel object into its parts by its dense semantic correspondence with the base object.

## Installation

See [installation instructions](INSTALL.md).

## Getting Started

See [Preparing Datasets](datasets) and [Preparing Models](models).

See [Getting Started](GETTING_STARTED.md) for demo, training and inference.

