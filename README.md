# OpenBio

## This is a space for open bioinformatics projects in which DNAnexus employees have an organizational role. To check out a particular project, please click on the appropriate link below!  

## As-Is Software Disclaimer
This content in this repository is delivered "As-Is". Notwithstanding anything to the contrary, DNAnexus will have no warranty, support, liability or other obligations with respect to Materials provided hereunder.

## Downloading Content from OpenBio to a JupyterLab Instance
To download the entire OpenBio repository in your JupyterLab instance, copy the cloning link and use `git clone <cloning link>` from your terminal or Bash notebook/console.
```bash
git clone https://github.com/dnanexus/OpenBio.git
```
The cloning link may be found by clicking on the "Code" drop down menu in Github and following instructrutions.


To download a particular notebook from the OpenBio repository, copy the link address of the raw version of that notebook and download the notebook from your terminal or Bash notebook/console, use `wget <link address of notebook>`:
```bash
wget https://raw.githubusercontent.com/dnanexus/OpenBio/master/dx-toolkit/dx_extract_dataset_bash.ipynb
```

## Uploading Content from a JupyterLab Instance to a Project on the Platform
To upload a file to your project, use CLI dx-toolbox command, `dx upload <file_name>`.
```bash
dx upload BGEN_import.ipynb
```

To upload a folder to your project, use CLI dx-toolbox command, `dx upload -r <folder_name>`.
```bash
dx upload -r OpenBio
```
