# Luma Development Reference

This repository hosts the development reference for **Luma**, structured as a [Quarto book](https://quarto.org/docs/books/).  

## Contributing to the Development Reference

To contribute to this development reference, please follow these steps:

1.  Clone the repository to your local machine.
2.  Create a new branch for your changes.
3.  Edit the relevant `.qmd` files to implement your updates.
4.  Document your modifications in the Braindump under the "Work in Progress" section.
5.  Test your changes by rendering the Quarto book locally to ensure correctness.
6.  Commit and push your changes to your branch.
7.  Submit a pull request for review. All changes must be merged via pull request.
8.  Proposed changes will be discussed, and once approved, merged into the main branch. Your feature branch will then be deleted.

## Repository Structure  

The documentation is organized into the following structure: 

```
├── images/                 : Folder containing image assets
├── files/                  : Folder containing additional files and resources, such as the Visio diagram of the modules for the User Journey and System Response reference
└── _quarto.yml             : Quarto configuration file
```
The rendered development reference are structured as follows:

```
├── index.qmd               : Landing page  
├── ee_init.qmd             : Initialization instructions for Earth Engine. Development reference for `luma-stack/src/epistemx/ee_init.py`
├── python_setup.qmd        : Python environment setup guide
├── testing_guidelines.qmd  : Testing procedures and guidelines for developers prior to code merge
├── writing_guidelines.qmd  : Writing guideline for developers contributing to the whole "three-stream" workflow
├── helpers.qmd             : Library of helper functions used across multiple modules. Development reference for `luma-stack/src/epistemx/helpers.py`
├── module01.qmd            : Development reference for `luma-stack/src/epistemx/data_acquisition.py`
├── module02.qmd            : Development reference for `luma-stack/src/epistemx/classification_scheme.py`
├── module03.qmd            : Development reference for `luma-stack/src/epistemx/sample_data.py`
├── module04.qmd            : Development reference for `luma-stack/src/epistemx/sample_data_quality.py`
├── module05.qmd            : Development reference for `luma-stack/src/epistemx/predictor.py`
├── module06.qmd            : Development reference for `luma-stack/src/epistemx/classification.py`
├── module07.qmd            : Development reference for `luma-stack/src/epistemx/thematic_assessment.py`
└── module08.qmd            : Development reference for `luma-stack/src/epistemx/post_classification.py`
```
