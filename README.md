# **AWS Glue and S3 Data Pipeline**

### **🌟 Project Overview**
This project showcases **how to build a scalable, automated ETL pipeline** using **AWS Glue**, **Amazon S3**, and **Athena**. The pipeline efficiently handles **large datasets**, transforming raw data into **queryable formats** for analytics and insights.

---

## **✨ Features**
- **Data Storage**: Utilizes **Amazon S3** to store raw files such as **CSV** or **JSON**.
- **Data Cataloging**: Leverages **AWS Glue Crawlers** for schema discovery and catalog creation.
- **Data Transformation**: Processes data through **Glue jobs** for cleaning and transformations.
- **Data Querying**: Queries transformed datasets with **Amazon Athena** to derive meaningful insights.

---

## **🔧 Architecture**
![ETL Architecture](https://github.com/Suriyancdurai/AWS-Glue-S3-DataPipeline/blob/main/01.AWS-Glue-S3-Athena-DataPipeline%20Diagram.png)

1. **Raw Data**: Uploaded to an **S3 bucket**.
2. **Schema Discovery**: Handled by **AWS Glue Crawlers** to create a **data catalog**.
3. **Data Processing**: Executed through **Glue Jobs** for cleaning and transformation.
4. **Transformed Data**: Stored in a **target S3 bucket**.
5. **Querying**: Accessed via **Athena** to perform interactive analysis.

---

## **🛠️ Tools & Technologies**
- **Amazon S3** for scalable storage.  
- **AWS Glue** (Crawler and Jobs) for automated ETL workflows.  
- **Amazon Athena** for serverless querying.  
- **Python** (optional) for custom scripts and transformations.

---

## **📋 Setup Instructions**
1. **Upload Raw Data**: Place your raw data files in an **S3 bucket**.  
2. **Configure Glue Crawler**: Set up **Glue Crawlers** to detect schemas and build a catalog.  
3. **Define Glue Jobs**: Use the **Glue Visual Editor** or Python scripts for transformations.  
4. **Query Data**: Use **Athena** to query and analyze the transformed datasets.  

---


## **📚 References**
- [AWS Glue Official Documentation](https://docs.aws.amazon.com/glue/)  
- [YouTube Tutorial](https://www.youtube.com/watch?v=1IJJmWKzeXQ)
