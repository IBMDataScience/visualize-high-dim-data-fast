# Visualize High-Dimensional Data Fast | Watson Studio: [Blog](ADD-LINK)

## Step by step instructions to reproduce viz in [blog](ADD-LINK)

1. Download the MNIST handwritten digits sample data set from [here](https://ibm.box.com/s/94e4q8askq82owlnr6qxerworm6cx2sp). The file's name is `mnist_all_sample_10000.csv`.

1. Create an account on Watson Studio [cloud](https://www.ibm.com/cloud/watson-studio) or download the desktop version [here](https://www.ibm.com/products/watson-studio-desktop).

1. Open Watson Studio.

1. Click `New project` on the top right to create a new project on Watson Studio. <img src="https://github.com/IBMDataScience/visualize-data-fast/blob/master/screenshots/1%20create%20project.png">

1. Name your project and click `Create` on the bottom right. <img src="https://github.com/IBMDataScience/visualize-high-dim-data-fast/blob/master/screenshots/1%20name%20and%20create%20project.png">

1. Click the `Assets` tab if you are not already there.

1. Upload the `mnist_all_sample_10000.csv`, on the right hand side of the screen drop or browse the file. <img src="https://github.com/IBMDataScience/visualize-high-dim-data-fast/blob/master/screenshots/2%20drop%20or%20browse%20mnist%20data%20set.png">

1. In your project, under `Data assets`, click the data set to see a preview of the data set. <img src="https://github.com/IBMDataScience/visualize-high-dim-data-fast/blob/master/screenshots/3%20click%20data%20set%20to%20preview.png">

1. Click the `Refine` blue box in the top right to open the data set with the Data Refinery tool. <img src="https://github.com/IBMDataScience/visualize-high-dim-data-fast/blob/master/screenshots/4%20click%20refine.png">

1. Once the Data Refinery tool is open, navigate to the `Visualizations` tab. <img src="https://github.com/IBMDataScience/visualize-high-dim-data-fast/blob/master/screenshots/5%20navigate%20to%20viz.png">

1. Create the t-SNE visualization:
    1. Select the `t-SNE chart` on the CHART TYPES. <img src="https://github.com/IBMDataScience/visualize-high-dim-data-fast/blob/master/screenshots/6%20choose%20tsne.png">
    1. Set the `Perplexity` parameter to 75. <img src="https://github.com/IBMDataScience/visualize-high-dim-data-fast/blob/master/screenshots/7%20set%20perp%20to%2075.png">
    1. Select the column "label" as the `Color map`. <img src="https://github.com/IBMDataScience/visualize-high-dim-data-fast/blob/master/screenshots/8%20set%20color%20map%20to%20label.png">
    1. This is the t-SNE visualization after 1000 iterations. Each colored cloud represent a different digit from zero to nine. For instance, the purple cloud represents the images of the number one digit. <img src="https://github.com/IBMDataScience/visualize-high-dim-data-fast/blob/master/screenshots/9%20tsne%20after%201000%20iterations.png">
