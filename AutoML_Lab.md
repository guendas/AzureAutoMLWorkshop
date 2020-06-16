# Automated Machine Learning

Determining the right algorithm and preprocessing transformations for model training can involve a lot of guesswork and experimentation.

In this lab, you'll use automated machine learning to determine the optimal algorithm and preprocessing steps for a model.

## Before You Start

Before you start this lab, ensure that you have completed the following steps:
1. Navigate to the *resource group* where you deployed your **Azure Machine Learning Service**
2. Select the *Azure Machine Learning resource*
3. On the *Overview* page download the **config.json** file
    ![Alt text](imgs/config.jpg?raw=true "config.json")
4. Open the **Azure Machine Learning Studio** experience for managing the end-to-end machine learning lifecycle
    ![Alt text](imgs/azureml.jpg?raw=true "Azure Machine Learning Studio")
5. Select the **Notebook** icon from the menu on the left
6. Upload the **config.json** file
    ![Alt text](imgs/upload.jpg?raw=true "Upload config.json")
7. Create a new folder called *data*
    ![Alt text](imgs/folder1.jpg?raw=true "Create new folder")
    ![Alt text](imgs/folder2.jpg?raw=true "Upload files")
8. Upload the files available in the lab data folder (*diabetes.csv* and *diabetes2.csv*) inside the **data** folder you created in the previous step 
> **N.B.** select the folder otherwise your file will be uploaded in the root)

![Alt text](imgs/folder3.jpg?raw=true "Upload files")

9. Upload the file **Automated_Ml.ipynb** which will contain the code we'll run for this lab.

## Tips for the lab

You will need to create different compute resources to run the notebook and your experiment. How do you create the resources?
1. In the *Azure Machine Learning Studio* select the **Compute** icon from the left menu
2. Create a new resource from the UI or manage the compute resources deployed.

    ![Alt text](imgs/Compute.jpg?raw=true "Upload files")

For more info on the [**compute targets**](https://docs.microsoft.com/en-us/azure/machine-learning/concept-compute-target)

### Create Notebook compute instance

You can create the notebook compute instance in two ways:
1. From the *Notebook* tab, you select **New Compute** and then give a name and select the compute resource you need
    ![Alt text](imgs/NotebookCompute/NotebookCompute1.jpg?raw=true "Create compute")
    ![Alt text](imgs/NotebookCompute/NotebookCompute2.jpg?raw=true "Select compute")
2. From the *Compute* tab, select **Compute Instances** and then **New**
    ![Alt text](imgs/NotebookCompute/NotebookCompute3.jpg?raw=true "Select compute")

## Use Automated Machine Learning

In this task, you'll use automated machine learning to determine the optimal algorithm and preprocessing transformations for model training.

1. In [Azure Machine Learning studio](https://ml.azure.com), view the **Compute** page for your workspace; and on the **Compute Instances** tab, ensure your compute instance is running. If not, start it.
2. When the compute instance is running, click the **Notebook** tab.
3. Open the **Automated_ML.ipynb** notebook. Then read the notes in the notebook, running each code cell in turn.

> **Important**: When you have finished the lab, close all Jupyter tabs and **Stop** your compute instance to avoid incurring unnecessary costs.
