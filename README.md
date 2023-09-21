# Visualize-Data-using-Amazon-QuickSight
![0](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/0c7398ff-c31b-429c-8e38-6227e6ea0191)
In this project, you'll learn how to create visualizations from a large dataset using Amazon S3 and Amazon Quicksight. We'll be working with a dataset of 50 best-selling book on Amazon.com.

### Step 1:Download the Dataset
* Download the "Amazon-Top-50-Bestselling-Books-2009-2019" CSV file and the "manifest.json" file.
* Click on "raw" and Control+S to save both files onto your computer.

### Step 2:Store the Dataset in Amazon S3
* Open the Amazon S3 console and click "Create Bucket."
* Name the bucket (e.g., "aws-project-0") and keep the settings as default.
* Upload the CSV file and the "manifest.json" file into the bucket.
* Replace the URL in the "manifest.json" file with the S3 URL of your dataset.

### Step 3:Connect S3 Bucket with Amazon Quicksight
* Open the AWS management console and navigate to Amazon Quicksight.
* Sign up for a free trial of the Enterprise edition if you don't have an account.
* Select Amazon S3 and tick the box for the S3 bucket you created.
* Enter the link to your "manifest.json" file and connect to Quicksight.
* Select "interactive sheet" to start creating visualizations. 

### Step 4:Create Visulization
* Drag fields into the graph to create visualizations (e.g., Most popular author).
* Sort, filter, and customize the graphs as desired.
* Experiment with different types of graphs like bar charts, pie charts, line graphs, etc.
