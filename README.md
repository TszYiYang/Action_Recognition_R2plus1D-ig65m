Due to the size limitation on Github, the two demonstrative videos are uploaded to Youtube with the following hyperlinks for reviewing.

#### Demonstration Video 1. [Training and testing the DL model](https://youtu.be/JFYeygxIdTo) (11 minutes)
#### Demonstration Video 2. [Model deployment for human action recognition](https://youtu.be/XCZgkWDFz3A) (5 minutes)

```````
```````
This respository is a modified version of [Microsoft-computervision-recipes](https://github.com/microsoft/computervision-recipes) library. To install the repository and its dependencies follow these simple steps:  

1. (optional) Install Anaconda with Python >= 3.6. [Anaconda](https://www.anaconda.com/). 

2. Clone the repository (require my admin login)
    ```
    git clone https://github.tamu.edu/yangze2065/CSCE636-Spring2021 
    ```
3. Download the repository as zip file, extract the file to local machine (recommended, no password required)
    ```
    Use drop down menu to download the zipped repository
    ```
1. Install the conda environment, you'll find the `environment.yml` file in the root directory. To build the conda environment:
    ```
    cd CSCE636-Spring2021-master
    conda env create -f environment.yml
    ```
1. Activate the conda environment and register it with Jupyter:
    ```
    conda activate csce636-cv
    python -m ipykernel install --user --name csce636-cv --display-name "Python (csce636-cv)"
    ```
1. Start the Jupyter notebook server
    ```
    jupyter notebook
    ```
