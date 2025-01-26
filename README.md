Netflix Data Analysis and Visualization Using Amazon QuickSight

Overview
This project demonstrates how to visualize Netflix data using Amazon QuickSight. The process involves uploading data to Amazon S3, configuring the necessary manifest file, and creating an interactive dashboard in QuickSight to gain insights from the data.

Steps Involved
1. Upload Data to S3
- Upload the dataset into an Amazon S3 bucket.
- Copy the URI of the uploaded data file for reference in the manifest file.
 
![image](https://github.com/user-attachments/assets/212cba33-d310-46ba-be7c-0e661bf16cbf)






2. Update the `manifest.json` File
- Modify the `manifest.json` file to include the correct S3 data path.
  - The `manifest.json` file acts as a map, helping Amazon QuickSight locate and interpret the dataset.
  - It describes the data organization and structure to ensure proper visualization.
- Save the updated file.
  
![image](https://github.com/user-attachments/assets/f117680e-ad4e-484d-ae79-76952645230c)

 













3. Re-upload the `manifest.json` File
- Upload the updated `manifest.json` file back into the S3 bucket.
 
![image](https://github.com/user-attachments/assets/47ddac2a-2df6-4c58-8e33-ad684f2da682)



4. Establish Connection with Amazon QuickSight
- Set up a data source connection between Amazon QuickSight and the S3 bucket.
- Ensure the manifest file and dataset are properly linked for QuickSight to access and interpret the data.

![image](https://github.com/user-attachments/assets/604f31b8-38d0-44b5-92f0-a25bbf876edf)






- Creating connection with Quicksight and S3
  
![image](https://github.com/user-attachments/assets/ac9ea546-99fa-4d49-a5cd-3c99f1f9c4cd)



- Creating S3 data source connection for visualization. 

![image](https://github.com/user-attachments/assets/b724d83e-a5da-41af-8f79-9cd956c4b48c)




5. Create a Dashboard in Amazon QuickSight
- Design and build an interactive dashboard using the imported dataset.
- Utilize QuickSight’s visualization tools to represent data insights effectively.
  
  ![image](https://github.com/user-attachments/assets/1f8b3d5c-6720-480e-ae87-1201620f2bdb)
![Uploading image.png…]()

 

 

Notes
- The `manifest.json` file is critical for accurate data visualization. Without it, QuickSight may not interpret or display the data correctly.

