Netflix Data Analysis and Visualization Using Amazon QuickSight

Overview
This project demonstrates how to visualize Netflix data using Amazon QuickSight. The process involves uploading data to Amazon S3, configuring the necessary manifest file, and creating an interactive dashboard in QuickSight to gain insights from the data.

Steps Involved
1. Upload Data to S3
- Upload the dataset into an Amazon S3 bucket.
- Copy the URI of the uploaded data file for reference in the manifest file.
 







2. Update the `manifest.json` File
- Modify the `manifest.json` file to include the correct S3 data path.
  - The `manifest.json` file acts as a map, helping Amazon QuickSight locate and interpret the dataset.
  - It describes the data organization and structure to ensure proper visualization.
- Save the updated file.

 













3. Re-upload the `manifest.json` File
- Upload the updated `manifest.json` file back into the S3 bucket.
 



4. Establish Connection with Amazon QuickSight
- Set up a data source connection between Amazon QuickSight and the S3 bucket.
- Ensure the manifest file and dataset are properly linked for QuickSight to access and interpret the data.
 






- Creating connection with Quicksight and S3
 


- Creating S3 data source connection for visualization. 
 




5. Create a Dashboard in Amazon QuickSight
- Design and build an interactive dashboard using the imported dataset.
- Utilize QuickSight’s visualization tools to represent data insights effectively.
 

 

Notes
- The `manifest.json` file is critical for accurate data visualization. Without it, QuickSight may not interpret or display the data correctly.

