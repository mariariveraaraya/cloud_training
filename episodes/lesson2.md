---
title: "Data Layers and Containers"
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

1.	Understand the concept of data layers and their uses.
2.	Understand the concept of containers and their function in storage accounts.
3.	Understand the difference and relationship between different data layers and containers.


::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

1.	Define and explain the concept of data layers in databases and their uses for organising and transforming data.
2.	Define and explain the concept of containers in the context of storage accounts, and their role in separating data layers.
3.	Clarify the difference and relationship between data layers and containers using practical examples.


::::::::::::::::::::::::::::::::::::::::::::::::
## Data Layers
In simple terms, data layers define different stages of data transformation. They represent the progression of raw data through various stages until it becomes useful for advanced analysis and reporting.
The common data layers include:
- userupload; for files that are manually uploaded
- Raw: Original unprocessed records as received from source systems.
- Landing: The layer where raw data first lands and initial validity checks may be applied.
- Curated: A highly processed layer where data is cleansed, transformed, and prepared for analysis, equipped with necessary attributes and dimensions.
  
Each layer signifies a unique stage of data transformation, ensuring that data changes are traceable, thus maintaining data integrity across the system.

## Containers
Containers primarily serve as the organisers in a storage account architecture. They can be perceived as virtual folders, each storing a distinct type of data or data at different transformation stages.

Containers facilitate separation of concerns, allowing each data layer to be managed individually. They simplify data access, collaboration, retrieval, and help in maintaining a well-structured, clean, and orderly storage system.

## Relationship between Data Layers and Containers
Containers and data layers closely interact in real-world data management. Containers often hold different data layers, aiding data classification, and efficient access.

For instance, assume three containers named 'raw', 'landing', and 'curated'. The 'raw' container houses the raw data, 'landing' has the data after primary validity checks, while 'curated' contains the cleaned, wrangled data, ready for analysis. This demonstrates how containers embody different data layers, maintaining an orderly process flow and easy retrieval.

Due to the processing undertaken at every layer, analysts often engage with the 'curated' layer predominantly because the data is already clean, wrangled, and optimised for analysis.

To summarise, the relationship between containers and data layers is of organisation and efficiency. Containers hold the data layers, maintaining an optimal transformation chain, while data layers encapsulate varying degrees of data transformation, enabling the systematic conversion of raw data into actionable insights.

![Data layers](episodes/fig/data_layers.PNG)

### Comparing Physical and Logical Representations

Physical and logical data representations stand as complementary aspects of data storage and management.

Physical storage pertains to raw data files kept on some hardware or cloud-based platform. It does not concern itself with data's meaningfulness or organisation - it's fundamentally about ensuring data is stored, intact and accessible when required.

On the other hand, logical representation is about bringing 'sense' and 'meaning' to that stored data. It presents the data in an organised, often simplified form, making it easy for users to interact with and utilise the data.

Think of physical representation as the warehouse storing boxes of raw materials (data), and the logical representation as the display in a store - sorted, arranged, and ready for consumers (users) to browse and purchase.

Remember that comprehending both concepts is vital in understanding data management as a whole. They form the building blocks of data storage; understanding their synergy will guide you in leveraging the power of data effectively and efficiently.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: Physical vs logical?

What characterizes the curated data layer? 
- a) It only includes the logical component 
- b) It only includes the physical component 
- c) It may contain both the physical file and logical representation 
- d) It includes neither the physical nor the logical component



:::::::::::::::::::::::: solution 
 
c) It may contain both the physical file and logical representation

:::::::::::::::::::::::::::::::::::::


## Challenge 2: What is the difference between physical storage and logical representation of data? 
- a) Physical storage is the process of transforming data, while logical representation refers to the actual files. 
- b) Physical storage involves storing different file formats, while logical representation refers to the folders and containers. 
- c) Physical storage is the raw format of files, while logical representation provides a view that can be accessed and analyzed. 
- d) Physical storage is used for data wrangling, while logical representation is used for data cleaning.
  
:::::::::::::::::::::::: solution 

c) Physical storage is the raw format of files, while logical representation provides a view that can be accessed and analyzed.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

