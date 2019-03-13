# Visualize High-Dimensional Data Fast | Watson Studio: [Blog](ADD-LINK)

## Step by step instructions to reproduce viz in [blog](ADD-LINK)

1. Download the MNIST handwritten digits sample data set from [here](https://ibm.box.com/s/94e4q8askq82owlnr6qxerworm6cx2sp). The file's name is `mnist_all_sample_10000.csv`.

1. Create an account on Watson Studio [cloud](https://www.ibm.com/cloud/watson-studio) or download the desktop version [here](https://www.ibm.com/products/watson-studio-desktop).

1. Open Watson Studio.

1. Click `New project` on the top right to create a new project on Watson Studio. <img src="https://github.com/IBMDataScience/visualize-data-fast/blob/master/screenshots/1%20create%20project.png">

1. Name your project and click `Create` on the bottom right. <img src="NEW IMAGE HERE">

1. Click the `Assets` tab if you are not already there.

1. Upload the `mnist_all_sample_10000.csv`, on the right hand side of the screen drop or browse the file. <img src="ADD NEW IMAGE">

1. In your project, under `Data assets`, click the data set to see a preview of the data set. <img src="ADD NEW IMAGE HERE">

1. Click the `Refine` blue box in the top right to open the data set with the Data Refinery tool. <img src="ADD NEW IMAGE HERE">

1. Once the Data Refinery tool is open, navigate to the `Visualizations` tab. <img src="ADD NEW IMAGE HERE">

1. Create the t-SNE visualization:
    1. Select the `t-SNE chart` on the CHART TYPES. <img src="">
    1. Set the `Perplexity` parameter to 75. <img src="">
    1. Select the column "label" as the `Color map`. <img src="">
    1. This is the t-SNE visualization after 1000 iterations. <img src="">
