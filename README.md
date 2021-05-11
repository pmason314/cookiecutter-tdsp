# cookiecutter-tdsp
A [cookiecutter](https://cookiecutter.readthedocs.io/) template for a data science project file structure following Microsoft's [Team Data Science Process (TDSP)](https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/overview) guidelines.  This template allows for the easy creation of a full project directory that is both language- and cloud-agnostic.

## Usage

1. Install the project template utility [cookiecutter](https://cookiecutter.readthedocs.io/) using the package manager of your choice.
    * `$ pip install cookiecutter`
    * `$ conda install cookiecutter`
    * `$ sudo apt-get install cookiecutter`
2. Generate your project using the project template from this repository.  You will be prompted for both the project name and the customer or client.
```
$ cookiecutter https://github.com/pmason314/cookiecutter-tdsp
project_name [Placeholder-Data-ScienceProject]: my_data_science_project
customer_name [Placeholder Customer Name]: John Smith
```
3. (Optional) Initialize a git repository in the newly created project directory.  You can choose to take advantage of the provided .gitignore file, which contains the GitHub default for Python- and R-based projects.
```
$ cd my_data_science_project
$ git init
```
## Project Structure

Each subdirectory contains a README (omitted from this diagram) containing a template and recommended contents for that stage of the data science life cycle.
```
[Project Name]
├── code
|   ├── exploratory_data_analysis 
|   ├── modeling
|   └── deployment
├── sample_data
|   ├── raw
|   ├── processed
|   └── for_modeling
├── Docs
|   ├── Data Dictionaries
|   ├── Data Reports
|   ├── Model
|   |   ├── Baseline
|   |   └── Model 1
|   └── Project
|       ├── Charter.md
|       ├── Exit Report.md
|       └── System Architecture.docx
├── README.md
└── .gitignore
```

## TDSP

Microsoft's [Team Data Science Process](https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/overview) is an agile, iterative, data science methodology to improve collaboration and team learning. It is supported through a lifecycle definition, standard project structure, artifact templates, and tools for productive data science.  The original archived repository containing the TDSP format is available at https://github.com/Azure/Azure-TDSP-Utilities.

