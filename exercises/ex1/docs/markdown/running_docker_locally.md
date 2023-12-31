# Running Jupyter in Docker

To run Jupyter in Docker, make sure that you have
[Docker installed](https://www.docker.com/get-started).

Docker is a great way to quickly get an environment up and running.
For this workshop, we recommend the `jupyter/scipy-notebook` image.

To quickly bring up a JupyterLab server inside Docker,
[run the following command](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/running.html):

```bash
docker run -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes jupyter/scipy-notebook:latest
```

![docker run](../images/docker_run.png)

This will print an URL which will point you to your running Jupyter environment.
There, you can upload this notebook file and execute it. You can find instructions
to upload the notebook in the [Exercises](#exercises) section.

## Exercises

*If you followed one of the links to mybinder.org or to Google Colab, the notebook
will open automatically. You only need to follow the steps below if you have your
own JupyterLab instance, such as when running with Docker.*

Start the exercises by downloading the
[Jupyter notebook from Github](https://github.com/SAP-samples/teched2023-AI268/blob/main/exercises/ex1/Sales_Order_Completion_Using_Data_Attribute_Reccomendation.ipynb).

Click the download button to download the notebook as shown below.

![Screenshot Upload 0](../images/download-notebook.png)

Inside of your Jupyter environment, click the "Upload" button.

![Screenshot Upload 1](../images/upload-1.png)

In the file selection dialog, select the notebook file.

![Screenshot Upload 2](../images/upload-2.png)

Double-check that the file name ends with `.ipynb`. If the file has a different
extension, please change the file extension to `.ipynb`. First, select the row
containing the file and then right click and select the "Rename" button.

![Screenshot Upload 3](../images/upload-3.png)


After the file is uploaded, simply double click the file name in the file listing to start the
notebook:

![Screenshot Upload 5](../images/upload-4.png)

Once you have launched the notebook, you are all set.
The remaining workshop content is located inside the notebook.
