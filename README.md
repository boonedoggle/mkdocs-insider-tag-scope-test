# mkdocs-insider-tag-scope-test
Repository to test the tag features of mkdocs-material-insider, specifically the scope
feature of tags.

## Installation
### Create Virtual Environment
1. Install Anaconda
2. Create the conda environment
    ```
    conda env create -f environment.yml
    ```
3. Activate the conda environment
    ```
    $ conda activate mkdocs-test
    ```

### Updating the Virtual Environment
If you already have an existing mkdocs-test environment and the requirements.txt file has
been updated, you can update your local environment:
```
conda activate mkdocs-test
pip install --upgrade --force-reinstall -r requirements.txt
```

## Serve the Site
To serve the documentation locally, run the following:
```
$ cd /path/to/mkdocs-insider-tag-scope-test/
$ mkdocs serve
```
