# Visualizing-Netflix-Data-with-Amazon-QuickSight

## Introduction

This repository showcases a project where I used Amazon QuickSight, AWS's business analytics service, to analyze and visualize trends within Netflix's content catalog. This project provided me with hands-on experience in data-driven decision-making through the creation of insightful visualizations.


![Screenshot 2024-08-30 111659](https://github.com/user-attachments/assets/cdd7b040-530b-4e05-85ff-67157d661316)


### Understanding Amazon QuickSight

Amazon QuickSight is a cloud-based service that empowers users to quickly analyze and visualize their data. It enables businesses to extract actionable insights, facilitating faster and more informed decisions.
### Project Breakdown

#### 1. Data Preparation with Amazon S3

**Dataset**: The project utilizes a dataset containing detailed information on Netflix's movies and TV shows, including genres, release years, and more.

**S3 Bucket**: The dataset, along with a crucial `manifest.json` file, was uploaded to an Amazon S3 bucket. The `manifest.json` file played an essential role in guiding QuickSight to accurately interpret the dataset.![Screenshot 2024-08-28 150622](https://github.com/user-attachments/assets/cf39ef6e-c4f2-47fb-8df9-f3faa59f4489)
#### 2. Setting Up Amazon QuickSight

**Account Setup**: Creating an Amazon QuickSight account was a swift process, taking just a few minutes. 

**Data Access**: QuickSight was configured to access the S3 bucket, ensuring seamless data retrieval.
![Screenshot 2024-08-28 155340](https://github.com/user-attachments/assets/19c584d1-9ec1-4cb2-911b-9bc0d337ad87)
#### 3. Linking S3 to QuickSight

**Dataset Connection**: A new dataset was created in QuickSight by selecting S3 as the data source and connecting it using the S3 URL linked to the `manifest.json` file. This connection was pivotal for accurate data analysis and visualization.
![Screenshot 2024-08-28 160347](https://github.com/user-attachments/assets/f81fd298-7505-4118-9797-fbe0f34132e4)
#### 4. Crafting Visualizations

**Visualization Process**: QuickSight's AutoGraph feature was used to build visualizations. An example visualization showed the distribution of movies versus TV shows by their release year.

![Screenshot 2024-08-28 161534](https://github.com/user-attachments/assets/a24d069a-a55f-43c1-a033-a94db52095a8)
![Screenshot 2024-08-28 161751](https://github.com/user-attachments/assets/c13b0c6e-38cc-4bb8-bfe9-25f0a4218430)


#### 5. Applying Filters for Targeted Insights

**Data Filtering**: QuickSight's filtering options allowed for refining the data, such as focusing on content released after 2015. This approach helped in creating more relevant and focused visualizations.

#### 6. Building and Finalizing the Dashboard

**Dashboard Creation**: After creating the visualizations, enhancements were made by adjusting titles and layouts for clarity. Export options, such as converting the dashboard into a PDF, were also explored for easy sharing.

![Screenshot 2024-08-28 170336](https://github.com/user-attachments/assets/6fd7023e-c46b-4341-9a32-37257de749e1)
## Key Learnings

- **User-Friendly Interface**: QuickSight’s intuitive design simplifies the data visualization process.
- **Seamless S3 Integration**: The connection between S3 and QuickSight was smooth, thanks to the `manifest.json` file.
- **Flexible Visualization Tools**: QuickSight offers a variety of tools for building diverse visualizations.
- **Potential for Real-Time Insights**: This project has sparked an interest in exploring real-time data visualization in the future.

## Conclusion

This project provided a valuable introduction to Amazon QuickSight,  by working through the steps of setting up S3, connecting datasets, and creating meaningful visualizations, I gained a deeper understanding of how to leverage cloud-based tools for analytical purposes. The ease and efficiency of QuickSight have sparked my interest in exploring more advanced features and integrating it with other AWS services. 

