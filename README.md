# 5sigma
supporting materials on 5sigma idea

# Anomaly detection

- "Anomaly detection in time series: a comprehensive evaluation" - https://timeeval.github.io/evaluation-paper/
- "Anomaly Detection Principles and Algorithms" (book) - https://link.springer.com/book/10.1007/978-3-319-67526-8

### "Anomaly Detection Principles and Algorithms" by Mehrotra Kishan G. and Varun Dahiya

**Description:**
"Anomaly Detection Principles and Algorithms" provides a comprehensive guide to the concepts, techniques, and algorithms used in anomaly detection. It covers both theoretical foundations and practical implementations, making it a valuable resource for researchers, practitioners, and students in the field of data science, machine learning, and cybersecurity.

**Key Topics Covered:**

1. **Introduction to Anomaly Detection:**
   - Definition of anomalies and their importance in various applications.
   - Overview of different types of anomalies: point anomalies, contextual anomalies, and collective anomalies.

2. **Statistical Methods:**
   - Techniques based on statistical models to detect anomalies.
   - Methods include Gaussian models, hypothesis testing, and regression analysis.

3. **Machine Learning Approaches:**
   - **Supervised Learning:** Techniques that require labeled data for training, such as classification algorithms (e.g., SVM, decision trees).
   - **Unsupervised Learning:** Techniques that do not require labeled data, including clustering (e.g., K-means, DBSCAN) and density-based methods.
   - **Semi-supervised Learning:** Combines both labeled and unlabeled data to improve detection performance.

4. **Advanced Algorithms:**
   - **Neural Networks and Deep Learning:** Utilization of neural networks, autoencoders, and LSTM for detecting anomalies in complex data.
   - **Ensemble Methods:** Combining multiple models to improve robustness and accuracy, such as random forests and boosting techniques.

5. **Time Series Anomaly Detection:**
   - Specific techniques for handling temporal data, including ARIMA, Holt-Winters, and deep learning approaches like LSTM and GRU.

6. **Contextual and Collective Anomalies:**
   - Methods to identify anomalies in data with contextual information and groups of data points that together form an anomaly.

7. **Evaluation Metrics:**
   - Metrics for assessing the performance of anomaly detection models, such as precision, recall, F1-score, and ROC-AUC.

8. **Applications:**
   - Real-world applications of anomaly detection across various domains, including fraud detection, network security, industrial monitoring, and healthcare.

9. **Case Studies and Practical Implementations:**
   - Detailed case studies demonstrating the application of different anomaly detection techniques.
   - Practical guidance on implementing anomaly detection algorithms using popular programming languages and tools.

**Advantages:**
- **Comprehensive Coverage:** Provides a thorough understanding of both basic and advanced anomaly detection techniques.
- **Practical Focus:** Includes real-world case studies and practical implementation tips.
- **Accessible Writing:** Suitable for both beginners and experienced practitioners, with clear explanations and examples.

**Reference:** "Anomaly Detection Principles and Algorithms" by Mehrotra Kishan G. and Varun Dahiya. This book serves as a valuable resource for anyone looking to understand and apply anomaly detection techniques in various fields.

# On predictive maintenance

- "Predictive Maintenance using Machine Learning" - https://arxiv.org/abs/2205.09402 
- "Machine learning-based predictive maintenance: A cost-oriented model for implementation" - https://www.sciencedirect.com/science/article/abs/pii/S0925527321000906

# Data analytics - industry

- pushing ChatGPT 4o for summary:

### Microsoft Fabric

- **Description:** Microsoft Fabric is a comprehensive, end-to-end analytics platform designed to integrate various data services, enabling seamless data engineering, data integration, data warehousing, and machine learning capabilities within a unified environment.
- **Features:**
  - **Data Integration:** Simplifies the process of connecting and ingesting data from multiple sources using tools like Azure Data Factory.
  - **Data Engineering:** Facilitates data transformation and processing with scalable and serverless data pipelines.
  - **Data Warehousing:** Provides robust, scalable data storage solutions with Azure Synapse Analytics, supporting complex queries and real-time analytics.
  - **Machine Learning:** Integrates with Azure Machine Learning to build, train, and deploy ML models efficiently.
  - **Analytics and Reporting:** Utilizes Power BI for advanced data visualization, reporting, and business intelligence.
  - **Collaboration:** Offers a unified workspace for data engineers, data scientists, and business analysts to collaborate effectively.
  - **Security and Compliance:** Ensures data security and regulatory compliance with built-in Azure security features and governance tools.

- **Reference:** [Microsoft Fabric](https://www.microsoft.com/en-us/microsoft-fabric)

#### Example Applications:

1. **Retail Analytics:**
   - Integrates sales, customer, and inventory data from various sources.
   - Uses machine learning to forecast demand and optimize inventory management.
   - Provides real-time dashboards for sales performance and customer insights.

2. **Financial Services:**
   - Aggregates data from financial transactions, market feeds, and customer profiles.
   - Employs predictive analytics for risk management and fraud detection.
   - Generates comprehensive financial reports and compliance documentation.

3. **Healthcare:**
   - Collects patient data from electronic health records (EHR) and IoT medical devices.
   - Analyzes data to predict patient outcomes and optimize treatment plans.
   - Facilitates secure sharing of data among healthcare providers for collaborative care.

#### Advantages:

- **Unified Platform:** Offers a single, integrated solution for managing and analyzing data across the entire data lifecycle.
- **Scalability:** Scales seamlessly to handle large volumes of data and complex analytical workloads.
- **Ease of Use:** Provides user-friendly tools and interfaces for both technical and non-technical users.
- **Comprehensive Analytics:** Combines data engineering, machine learning, and business intelligence capabilities in one platform.

Microsoft Fabric is an ideal choice for organizations looking to streamline their data operations, improve collaboration across teams, and derive actionable insights from their data.

### **Google Cloud Platform (GCP)**

#### Google BigQuery
- **Description:** A fully managed, serverless data warehouse that allows for scalable analysis over petabytes of data.
- **Features:** SQL-based querying, real-time analytics, machine learning integration with BigQuery ML, and seamless integration with other GCP services.
- **Reference:** [Google BigQuery](https://cloud.google.com/bigquery)

#### Google Dataflow
- **Description:** A unified stream and batch data processing service.
- **Features:** Autoscaling, integration with Apache Beam, and built-in data transformation and enrichment capabilities.
- **Reference:** [Google Dataflow](https://cloud.google.com/dataflow)

#### Vertex AI
- **Description:** A unified AI platform for building, deploying, and scaling machine learning models.
- **Features:** End-to-end ML workflow support, integrated with GCP's data and analytics services.
- **Reference:** [Vertex AI](https://cloud.google.com/vertex-ai)

### **Amazon Web Services (AWS)**

#### Amazon Redshift
- **Description:** A fully managed data warehouse service that allows you to run complex queries on structured and semi-structured data.
- **Features:** Columnar storage, high query performance, integration with AWS analytics and ML services.
- **Reference:** [Amazon Redshift](https://aws.amazon.com/redshift)

#### AWS Glue
- **Description:** A serverless data integration service that makes it easy to prepare and transform data.
- **Features:** ETL (Extract, Transform, Load), data cataloging, integration with other AWS services.
- **Reference:** [AWS Glue](https://aws.amazon.com/glue)

#### Amazon SageMaker
- **Description:** A fully managed service for building, training, and deploying machine learning models.
- **Features:** Integrated Jupyter notebooks, automated model tuning, and deployment capabilities.
- **Reference:** [Amazon SageMaker](https://aws.amazon.com/sagemaker)

### **IBM Cloud**

#### IBM Watson Studio
- **Description:** An integrated environment for data scientists, application developers, and subject matter experts to collaboratively work with data.
- **Features:** Data preparation, model building, deployment, and monitoring capabilities.
- **Reference:** [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio)

#### IBM Db2 Warehouse on Cloud
- **Description:** A fully managed SQL cloud data warehouse that delivers independent scaling of storage and compute.
- **Features:** Advanced data management, analytics, and machine learning integration.
- **Reference:** [IBM Db2 Warehouse on Cloud](https://www.ibm.com/cloud/db2-warehouse-on-cloud)

### **Oracle Cloud Infrastructure (OCI)**

#### Oracle Autonomous Data Warehouse
- **Description:** A fully managed data warehouse service with built-in machine learning.
- **Features:** Autonomous administration, high-performance querying, and integrated analytics.
- **Reference:** [Oracle Autonomous Data Warehouse](https://www.oracle.com/autonomous-database/autonomous-data-warehouse/)

#### Oracle Cloud Data Integration
- **Description:** A comprehensive data integration platform that allows for data movement, transformation, and replication.
- **Features:** Seamless ETL, data pipeline orchestration, and integration with Oracle's analytics and ML services.
- **Reference:** [Oracle Cloud Data Integration](https://www.oracle.com/integration/data-integration/)

### **Snowflake**

- **Description:** A cloud data platform that provides data warehousing, data lake, and data sharing capabilities.
- **Features:** Near-unlimited scalability, support for semi-structured data, built-in data sharing, and integration with data engineering and ML tools.
- **Reference:** [Snowflake](https://www.snowflake.com/)

### **Databricks**

- **Description:** An analytics platform built on Apache Spark that offers collaborative data science and engineering.
- **Features:** Unified analytics for data science, engineering, and business; ML workflows; scalable compute; Delta Lake for reliable data lakes.
- **Reference:** [Databricks](https://databricks.com/)

### **Cloudera Data Platform (CDP)**

- **Description:** A comprehensive data platform that offers data engineering, data warehousing, machine learning, and operational databases.
- **Features:** Hybrid and multi-cloud support, integrated data lifecycle management, and machine learning capabilities.
- **Reference:** [Cloudera Data Platform](https://www.cloudera.com/products/cloudera-data-platform.html)

### **SAP Data Intelligence**

- **Description:** An end-to-end data management solution that allows for data integration, orchestration, and machine learning.
- **Features:** Integration with SAP and non-SAP systems, data cataloging, pipeline orchestration, and ML operations.
- **Reference:** [SAP Data Intelligence](https://www.sap.com/products/data-intelligence.html)

These platforms offer a range of capabilities similar to Microsoft Fabric, allowing for data integration, processing, analysis, and machine learning. Each platform has its strengths and is suitable for different use cases depending on your specific requirements.

# Industry commercial solutions for system maintenance / asset management (random)

- https://www.advancedtech.com/industrial-maintenance/
- use of MS fabric - https://smartbridge.com/microsoft-fabric-real-time-analytics/ 

### IBM Maximo

- **Description:** IBM Maximo is an enterprise asset management (EAM) solution that leverages IoT, AI, and analytics to optimize the lifecycle management of physical assets across various industries. It helps organizations maximize the performance, extend the lifespan, and ensure the efficient operation of their assets.
- **Features:**
  - **Asset Management:** Comprehensive tracking and management of asset information, including maintenance schedules, lifecycle costs, and asset hierarchies.
  - **Work Management:** Streamlines the planning, scheduling, and execution of maintenance tasks, work orders, and service requests.
  - **Inventory Management:** Efficiently manages spare parts and materials, ensuring the right parts are available when needed.
  - **Procurement Management:** Integrates purchasing processes, from requisition to procurement, to ensure cost-effective and timely acquisition of goods and services.
  - **Service Management:** Manages service delivery, including service level agreements (SLAs) and customer support.
  - **IoT Integration:** Utilizes IoT data for real-time monitoring of asset conditions, enabling predictive maintenance and reducing downtime.
  - **AI and Analytics:** Leverages IBM Watson to provide advanced analytics, predictive maintenance, and anomaly detection.
  - **Mobile Access:** Supports mobile applications for field technicians to access work orders, asset information, and reporting tools on the go.

- **Reference:** [IBM Maximo](https://www.ibm.com/products/maximo)

### Example Applications:

1. **Manufacturing:**
   - **Application:** Monitors equipment health and performance in real-time using IoT sensors.
   - **Features:** Predictive maintenance models identify potential failures before they occur, reducing unplanned downtime and maintenance costs.
   - **Outcome:** Increases equipment availability and optimizes maintenance schedules.

2. **Energy and Utilities:**
   - **Application:** Manages and maintains critical infrastructure such as power plants, substations, and distribution networks.
   - **Features:** Advanced analytics for asset performance management and risk assessment.
   - **Outcome:** Enhances reliability, ensures regulatory compliance, and reduces operational risks.

3. **Transportation:**
   - **Application:** Oversees fleet management, including vehicles, railcars, and aircraft.
   - **Features:** Comprehensive tracking of maintenance activities, spare parts inventory, and compliance with safety standards.
   - **Outcome:** Improves fleet reliability, reduces maintenance costs, and ensures safety.

4. **Healthcare:**
   - **Application:** Manages medical equipment and facility infrastructure.
   - **Features:** Scheduling and tracking of preventive maintenance and repairs, ensuring compliance with healthcare regulations.
   - **Outcome:** Ensures the availability and reliability of critical medical equipment, enhancing patient care.

### Advantages:

- **Comprehensive EAM Solution:** Offers a wide range of functionalities to manage all aspects of asset lifecycle management.
- **Predictive Maintenance:** Uses AI and IoT to predict asset failures and optimize maintenance activities, reducing downtime and costs.
- **Scalability:** Suitable for organizations of all sizes, from small enterprises to large, complex operations.
- **Mobile Capabilities:** Provides mobile solutions for field workers, enhancing productivity and ensuring real-time data access.
- **Integration:** Easily integrates with other enterprise systems and IoT platforms, providing a holistic view of asset performance and management.

IBM Maximo is ideal for organizations seeking to enhance asset reliability, extend asset life, and improve overall operational efficiency through advanced asset management, IoT integration, and predictive analytics.
