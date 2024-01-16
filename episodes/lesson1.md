---
title: "Physical and Logical Representation of Data"
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

1.	Understand the concept of physical storage of data.
2.	Understand the concept of logical representation of data.
3.	Understand the difference between physical storage and logical representation.

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

1. Define and explain the concept of physical storage using platform storage accounts as examples.
2. Define and explain the concept of logical representation using views in Synapse as examples.
3. Differentiate between files in their raw formats in physical storage and cleaned, wrangled files in logical representation.

::::::::::::::::::::::::::::::::::::::::::::::::

### Physical Data Storage
Physical data storage refers to the tangible means by which data is stored in digital form, on devices like hard drives, Flash storage, memory cards, DVDs, etc. When relating this to a storage account platform in the QESD Platform such as sboxlakedev, the data is physically stored as files within the cloud storage. These files are kept in containers, which form the primary component of the platform's data storage architecture. Data here is raw and untransformed, thus may require additional processing steps for optimal use.

### Logical Representation of Data
Contrary to physical data storage, logical representation of data abstracts the underlying complexity of physical storage. It concerns the way data is perceived from a user's point of view, invariably hiding intricate lower-level details. For instance, in Synapse, users interact with a logical representation of the data - a structured, cleaned, and organised 'view' - rather than dealing directly with the physical storage. The underlying technology enables users to manipulate, search, and retrieve the data without needing extensive comprehension of how and where the data is physically stored.

![Physical vs logical data](episodes/fig/physical_logical.PNG)

### Comparing Physical and Logical Representations

Physical and logical data representations stand as complementary aspects of data storage and management.

Physical storage pertains to raw data files kept on some hardware or cloud-based platform. It does not concern itself with data's meaningfulness or organisation - it's fundamentally about ensuring data is stored, intact and accessible when required.

On the other hand, logical representation is about bringing 'sense' and 'meaning' to that stored data. It presents the data in an organised, often simplified form, making it easy for users to interact with and utilise the data.

Think of physical representation as the warehouse storing boxes of raw materials (data), and the logical representation as the display in a store - sorted, arranged, and ready for consumers (users) to browse and purchase.

Remember that comprehending both concepts is vital in understanding data management as a whole. They form the building blocks of data storage; understanding their synergy will guide you in leveraging the power of data effectively and efficiently.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: Physical vs logical?

1.	What does physical storage, as mentioned in the transcript, refer to in the context of data management? 

- a) The logical representation of data 
- b) The actual files stored in a storage account 
- c) Data transformation process 
- d) Data analysis and manipulation tools

:::::::::::::::::::::::: solution 


 The actual files stored in a storage account

 ::::::::::::::::::::::::


## Challenge 2: What is the difference between physical storage and logical representation of data? 
- a) Physical storage is the process of transforming data, while logical representation refers to the actual files. 
- b) Physical storage involves storing different file formats, while logical representation refers to the folders and containers. 
- c) Physical storage is the raw format of files, while logical representation provides a view that can be accessed and analyzed. 
- d) Physical storage is used for data wrangling, while logical representation is used for data cleaning.
  
:::::::::::::::::::::::: solution 

d) Physical storage is the raw format of files, while logical representation provides a view that can be accessed and analyzed.

:::::::::::::::::::::::::::::::::
