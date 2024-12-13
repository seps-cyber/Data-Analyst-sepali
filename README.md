# Academic Section Hiring and Appointment: Cloud Computing Project

## Project Overview
This project focuses on streamlining and analyzing the academic section hiring and appointment procedures using cloud computing services. By leveraging AWS tools and services, the goal is to ensure efficiency, scalability, and robust monitoring for the dataset associated with this process.

## Objectives
- **Data Management**: Efficiently store, process, and retrieve large datasets related to academic hiring.
- **Automation**: Simplify data processing pipelines for academic appointment procedures.
- **Monitoring**: Set up robust monitoring systems to track and optimize workflows.
- **Visualization**: Create dashboards to provide real-time insights into system performance and processes.

## Dataset Description
The dataset used pertains to academic hiring and appointment processes, including data fields such as applicant details, hiring stages, and outcomes. Specific fields have been anonymized for privacy compliance.

## Tools and Technologies
The following AWS services were utilized to develop and manage this project:
- **Amazon S3 (Simple Storage Service)**: For secure and scalable data storage.
- **AWS Glue**: To prepare and transform data for analysis.
- **AWS Lambda**: To automate data processing tasks.
- **Amazon CloudWatch**: For real-time monitoring and performance dashboards.
- **Amazon VPC (Virtual Private Cloud)**: To ensure a secure network environment.
- **AWS CloudTrail**: To track and log all activities for auditing purposes.
- **Amazon QuickSight**: For visualizing insights derived from data analysis.

## Project Methodology
1. **Data Ingestion**: The dataset was uploaded to an Amazon S3 bucket for secure storage.
2. **Data Transformation**:
   - AWS Glue was used to clean and prepare the dataset.
   - ETL pipelines were designed to process the data.
3. **Data Analysis**: Custom Lambda functions were created to extract key metrics from the processed data.
4. **Monitoring and Alerts**:
   - Amazon CloudWatch Dashboards were configured to visualize system performance.
   - Alarms were set to notify stakeholders of anomalies or issues.
5. **Network Security**:
   - Amazon VPC was implemented to isolate resources securely.
   - CloudTrail logs were reviewed for security and compliance auditing.
6. **Visualization**: Dashboards were created using Amazon QuickSight to present actionable insights.

## Webpage and Links
Explore the live webpage showcasing this project:
[Project Webpage](https://seps-cyber.github.io/Data-Analyst-sepali/)

Additionally, screenshots and diagrams have been added for better un
derstanding and visualization:

## Screenshots
The Graphical show case of projeect
![Screenshot 2024-12-11 210512](https://github.com/user-attachments/assets/7f571dfe-5929-46f2-b6ad-48e167fc56f5)


The following screenshots are included in the `/screenshots` folder to demonstrate the implementation and outcomes:
1. **Amazon S3**:![Screenshot 2024-10-28 000747](https://github.com/user-attachments/assets/c2695247-6d0e-434a-a137-a1a143c3dc83)

   - Dataset files uploaded to the bucket.
   - Bucket permissions configuration.
2. **AWS Glue**:![Screenshot 2024-12-11 200021](https://github.com/user-attachments/assets/a668896c-9fbd-4ef9-9799-e4417c089d08)

   - ETL job workflow and job history.
3. **AWS Lambda**:
   - Function configuration and execution logs.
4. **Amazon CloudWatch**:
   - Dashboard visualizations and alarms setup.
5. **AWS VPC**:
   - VPC subnet and routing table configurations.
6. **AWS CloudTrail**:
   - Event logs for activities and auditing.
7. **Amazon QuickSight**:
   - Dashboards and insights visualizations.
8. **General AWS Management Console**:![Screenshot 2024-12-11 200110](https://github.com/user-attachments/assets/018d8614-32ee-472d-88de-2b12bece25b0)

   - Summary view of all project-related resources.

## Architecture Diagram
Below is the architecture diagram for the project, showcasing the integration of AWS services:
![Architecture Diagram](diagrams/architecture.png)

The diagram includes:
- **Data Flow**: Movement between S3, Glue, Lambda, and QuickSight.
- **Monitoring**: Interaction of CloudWatch and CloudTrail with other services.
- **Security**: VPC isolation and IAM role implementations.

The editable `.drawio` file is also available in the `/diagrams` folder for further modifications.

## Deliverables
- **AWS Configuration Screenshots**: Available in the `/screenshots` directory.
- **Code Repository**: Contains the scripts for AWS Glue and Lambda functions.
- **Documentation**: Detailed explanations of processes, methodologies, and configurations.
- **Monitoring Dashboards**: Screenshots and configurations for CloudWatch dashboards.
- **Architecture Diagram**: Included in the `/diagrams` folder.

## How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/seps-cyber /academic-hiring-cloud-project.git
   ```
2. Navigate through the `/screenshots` folder for AWS configurations and workflows.
3. Review the `/diagrams` folder for the architecture diagram and editable files.
4. Read the documentation for detailed insights into the project methodology.

## Contact
For questions or feedback, feel free to contact me via Sepali.weeraseka5783@myucw.ca or through GitHub Issues.


