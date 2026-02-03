# BIG-DATA-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SANKET MITHBAVKAR

*INTERN ID*: 556BDB3B1676F398

*DOMAIN*: DATA ANALYTICS

*DURATION*: 12 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION ABOUT THIS TASK*:
Big data analysis plays a crucial role in today’s data-driven world, where organizations deal with massive volumes of structured and unstructured data generated every day. Traditional data processing tools often fail to handle such large datasets efficiently due to memory and performance limitations. To overcome these challenges, scalable big data frameworks such as PySpark and Dask are widely used. In this task, a large Amazon sales dataset was analyzed using the Dask framework to demonstrate scalable big data processing and extract meaningful insights. The dataset used for this task consists of approximately 10 lakh (1 million) sales records related to Amazon transactions. It contains multiple attributes such as order details, order status, sales channel, category, quantity, amount, shipping location, and fulfillment information. Due to its large size, the dataset represents a realistic real-world big data scenario where efficient data handling and parallel computation are required. The dataset was stored in CSV format and optimized to ensure compatibility with development platforms and version control systems such as GitHub.

To perform the analysis, the Dask DataFrame library was chosen as the primary big data processing tool. Dask is a powerful Python-based framework designed to scale data analysis workloads by breaking large datasets into smaller partitions and processing them in parallel. Unlike traditional Pandas, which loads the entire dataset into memory, Dask uses lazy evaluation and distributed computation, allowing efficient processing of large files without overwhelming system resources. This made Dask particularly suitable for handling the 10 lakh record Amazon sales dataset on a single machine.
The entire task was developed using Visual Studio Code (VS Code) as the primary platform editor. VS Code was selected due to its flexibility, strong Python support, and seamless integration with Jupyter Notebooks and data science libraries. Several scalable actions were performed during the analysis to clearly demonstrate big data processing capabilities. First, the dataset was loaded using Dask’s read_csv function with lazy loading, ensuring that data was not immediately read into memory. The dataset was automatically divided into multiple partitions, enabling parallel processing. Missing values were identified and handled appropriately to maintain data quality, which is a common challenge in real-world datasets. Exploratory analysis was conducted to understand the dataset size, number of columns, data types, and presence of null values.

Further, aggregation operations such as total sales calculation, category-wise sales analysis, top-selling categories, order status distribution, and average sales per category were performed. These operations demonstrated how Dask efficiently executes group-by and aggregation tasks across partitions. To enhance scalability, the dataset was explicitly repartitioned to increase parallelism, and memory persistence was applied to speed up repeated computations. These actions clearly showcased how Dask scales computation by utilizing available system resources effectively. The deliverable for this task was a well-structured script/notebook containing all analysis steps, scalable operations, and insights derived from the dataset. The notebook included proper documentation, logical cell ordering, and clear explanations of each stage of analysis. This deliverable meets the internship requirement of demonstrating both technical understanding and practical application of big data tools. The concepts and techniques applied in this task are highly applicable in real-world scenarios. E-commerce companies like Amazon use similar large-scale data analysis to track sales performance, identify high-demand product categories, optimize logistics, and improve customer experience. Beyond e-commerce, such scalable data processing is applicable in finance, healthcare, social media analytics, supply chain management, and business intelligence systems where massive datasets must be processed efficiently.

In conclusion, this task successfully demonstrates big data analysis using Dask on a large Amazon sales dataset. By leveraging scalable actions such as partitioning, lazy evaluation, and parallel computation, meaningful insights were extracted efficiently. The use of VS Code as a development platform further enhanced productivity and organization. Overall, this project highlights the importance of scalable big data tools and provides practical experience relevant to real-world data analytics applications.

*OUTPUTS*:
<img width="2557" height="1340" alt="Image" src="https://github.com/user-attachments/assets/10e227be-8cd0-4221-845c-5110d621008f" />

<img width="2557" height="1339" alt="Image" src="https://github.com/user-attachments/assets/57957fd1-d2f3-4e04-9d6a-ab8ecdbc638b" />

<img width="2555" height="1336" alt="Image" src="https://github.com/user-attachments/assets/05b84792-7a7c-422e-ac20-625cb4936f96" />

<img width="2553" height="1339" alt="Image" src="https://github.com/user-attachments/assets/ef76d605-1f50-41a3-b75f-b6c4e9bb43f3" />

<img width="2558" height="1336" alt="Image" src="https://github.com/user-attachments/assets/8494dc00-396b-4718-aee4-90e18ea6d39a" />

<img width="2536" height="1338" alt="Image" src="https://github.com/user-attachments/assets/1a048dd5-9935-44a8-bef0-f3fbdf8723c4" />
