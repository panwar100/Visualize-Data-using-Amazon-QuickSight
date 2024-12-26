# Visualize-Data-using-Amazon-QuickSight
<p>In this project, you'll learn how to create visualizations from a large dataset using Amazon S3 and Amazon Quicksight. We'll be working with a dataset of 50 best-selling book on Amazon.com.</p>

![0](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/0c7398ff-c31b-429c-8e38-6227e6ea0191)

### Step 1:Download the Dataset
* Download the "Amazon-Top-50-Bestselling-Books-2009-2019" CSV file and the "manifest.json" file.
![1](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/f90344ca-e36d-45a7-9457-7953457db26d)
* Click on "raw" and Control+S to save both files onto your computer.
![2](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/cc0ec3ba-6dbf-4171-9c16-e7725b035c89)

### Step 2:Store the Dataset in Amazon S3
* Open the Amazon S3 console and click "Create Bucket."
* Name the bucket (e.g., "aws-project-0") and keep the settings as default.
![3](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/9b57ea49-0c14-4531-ae21-4eeda98123e3)
* Upload the CSV file and the "manifest.json" file into the bucket.
![4](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/ad4d83d4-d728-46c0-a1e2-6c5d20a9b958)
* Replace the URL in the "manifest.json" file with the S3 URL of your dataset.
![5](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/f2ed12d2-89f5-458c-9416-e601ddb13026)

### Step 3:Connect S3 Bucket with Amazon Quicksight
* Open the AWS management console and navigate to Amazon Quicksight.
* Sign up for a free trial of the Enterprise edition if you don't have an account.
 ![6](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/ed42a0c7-52e1-4c22-934e-c9b7b7071db3)
* Select Amazon S3 and tick the box for the S3 bucket you created.
  ![7 1](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/eede5dd2-28e3-4b9a-b235-b5271aae3784)
 ![8](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/298347c1-a6e1-4990-80b7-06e32d9b7d0f)
  ![9](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/078dac68-08f1-490b-be31-abbdf334498b)
  ![10](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/c7d4a0bc-9089-4732-bb74-7baa124a360a)
  ![11](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/97ea75d2-7fb3-4431-97a8-039b6aad8db6)
* Enter the link to your "manifest.json" file and connect to Quicksight.
![12](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/56eef577-e48b-418a-92ea-f46faaac858c)
![13](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/4bd463cd-95ae-4e63-8549-2f0263dac884)
* Click Visualize
![13 1](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/893ac88a-89b1-4efa-8abe-8fac84d8f35e)
* Select "interactive sheet" to start creating visualizations.
![14](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/4a6dcbea-8389-413b-8239-26b1f4563278)

### Step 4:Create Visulization
* Drag fields into the graph to create visualizations (e.g., Most popular author).
![15](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/340bba8c-0953-45d3-9617-18696c78f138)
![16](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/20163d3a-67f1-4fe1-9741-5181c0ca7903)
* Sort, filter, and customize the graphs as desired.
 ![17](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/6dbd057a-f4b4-4015-b1f1-cade0aaeb920)
* Experiment with different types of graphs like bar charts, pie charts, line graphs, etc.
  ![18](https://github.com/panwar100/Visualize-Data-using-Amazon-QuickSight/assets/134361823/c90f37ca-4c11-405a-bc47-927d7e74d102)
  

  
