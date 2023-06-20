# Employment-Analytics-of-Disabled-Using-Tableau

**Project Scope and Subsequent Changes**

**Initial Scope:**

To determine how much of the immigrant population is facing difficulty with regards to employment and income, especially disabled. The earlier estimate was to identify each race that is recognized in the US census. The earlier data bank was decided to be the US census, but after many meetings with the client, it was decided to focus on getting the required datasets from US Census Beta as more robust and refined samples were being created.

**Initial Project Overview:** 

Employment Database for Disabled people based on race, citizenship, ancestry and gender for their upliftment and empowerment.

**Intermediate Scope:** 

To determine the employment and income disparity for disabled people between the Immigrant Population vs the Native Born. This would analyze how ancestry, race and language play a pivotal role even among the disabled population.

**Final Scope:** 

We gathered data for the population having South and East Asian descent based on ancestry, language, marital status, gender, education to analyze the employment and income for disabled population.
After several analyses, it was decided to focus majorly on the South Asian diaspora with countries including India, China, Pakistan, Nepal etc. This demographic especially India provides a very diverse group of categories for language and ancestry. The number of immigrants from this region is high but people from this region find it more difficult to land a job that is too skilled. Thus, the project was to find the statistics of immigrants from South Asian countries, especially disabled and how they have fared in society regarding income and employment.

**Data Sources:** 

The US Census and the US Census Public Use Microdata Sample (PUMS) Beta, both of the United States Census Bureau, were considered as potential data sources as they serve different purposes and have different characteristics.
The US Census gathers demographic and socioeconomic information from every family and person in the country every ten years. The data gathered from the census is used for a variety of purposes, including allocating seats in the US House of Representatives, defining electoral district boundaries, and allocating federal funding. It is intended to provide a comprehensive picture of the US population and its characteristics.
On the other hand, the US Census PUMS Beta is a subset of the data gathered in the US Census that is made accessible to the general public and scholars for analysis. Public Use Microdata Sample, or PUMS, is a term that denotes that the data has been anonymised to preserve the privacy of the subjects while still revealing specific information about the demographics of the community.
The entire US Census dataset differs from the PUMS Beta in a number of ways. 

●	Rather than being a full enumeration, it is a sampling of the population, which means that just a representative fraction of houses and individuals' data are included. 

●	Compared to the Census Bureau's summary statistics, the PUMS Beta has more in-depth data about people and households, such as details on their income, occupation, and level of education. 

●	Rather than restricting researchers to pre-made tables and reports, the PUMS Beta is made available in a format that enables researchers to do individualized analysis of the data.
Research uses the US Census Public Use Microdata Sample (PUMS) primarily because it gives researchers access to comprehensive data on the demographics of the US population. PUMS enables researchers to explore a wide range of social, economic, and demographic topics in a way that would not be possible with merely the summary data made available by the Census Bureau. This is done by allowing them to do customized analyses of the data.
Researchers from many different fields, including sociology, economics, public health, and urban planning, use PUMS data. The distribution of poverty across the United States, the impact of education on incomes, or the association between race and homeownership, are just a few examples of the research topics that might be studied using the PUMS data. These and other problems can be investigated in much more detail utilizing the detailed information offered by PUMS than would be possible with merely summary statistics.
The fact that working with the data with PUMS takes some level of technical competence is another factor in why it is largely employed in research. Despite the anonymization of the PUMS data for privacy reasons, it is still a sizable and complicated dataset that needs specialist software and statistical methods to evaluate. As a result, researchers who are trained and skilled to work with enormous datasets and perform intricate statistical analysis are the ones that primarily use PUMS data. It is for these precise reasons that we made use of the US Census PUMS Beta as our data source.

**Database Technologies:**

Once we finalized the data source, our next task was to select the technology to handle our data. We considered the following types of database technologies:

1)	File system (Eg. MS Excel): In order to organize and store files on a computer or other digital device, a file system is used. In a file system, data is kept in separate files, each of which contains one or more tables. Although file systems are simple to use and don't require any technical knowledge, they aren't very good at handling vast amounts of data or complex relationships between data. tiny datasets that may be readily maintained in a single file, such spreadsheets or tiny databases, are frequently stored in file systems.

2)	Relational Model (Eg. MySQL): An example of a relational database is one that divides data into one or more tables, each of which has rows and columns. Each column represents a specific characteristic of that entity, such as the name of the client or the date of the transaction, and each row represents a singular instance of that entity, such as a customer or an order. Structured query language (SQL) is used by relational databases to obtain and change data. Relational databases are made to manage enormous volumes of data and complicated relationships between data. Large datasets with complex links, such as customer information or financial transactions, are frequently stored in relational databases.

3)	NoSQL (Eg. MongoDB): Non-relational data models are used by NoSQL databases to store and retrieve data. NoSQL databases are made to manage unstructured or semi-structured data, such as documents or key-value pairs, in contrast to relational databases, which arrange data into tables with predetermined associations. NoSQL databases are frequently used in applications that need high performance, scalability, and flexibility, like online applications and big data analytics. Document-oriented databases like MongoDB and key-value stores like Redis are just two types of NoSQL databases.

In conclusion, relational databases are made for large datasets with complicated relationships, whereas NoSQL databases are best suited for unstructured or semi-structured data and high-performance applications. File systems are best suited for tiny datasets that can be readily managed in a single file. The specific needs of the application or project at hand must be taken into consideration when deciding which data storage technology to use.
The following were our needs and criteria based on which we decided the technology to handle our data:

●	Data Security.

●	Potentially large amount of semistructured data.

●	Dynamically handles changes in modeled data without impacting the front end visualizations.

●	Accessible remotely through the cloud.

●	Data Consistency.

●	Ease of administration.

Due to our requirements, we decided to go with the NoSQL database technologies to handle our Data.
Out of all the NoSQL technologies considered, we decided to select MongoDB for the following reasons:

●	In order to protect data, MongoDB offers a number of security features, including access control, auditing, and data encryption both during storage and transmission. Additionally, it offers sophisticated security capabilities like role-based access control and authentication that make it possible to build detailed security policies.

●	A document-oriented database called MongoDB is capable of handling semi-structured data like JSON or BSON documents. It can easily manage huge volumes of data and is made to scale horizontally.

●	Because of the flexible schema design capabilities of MongoDB's document model, modifications to the data model can be performed without impairing the front-end visualizations. The underlying database schema does not need to be changed in order for the application to adapt over time as the data does.

●	MongoDB is a great solution for applications that need dispersed, remote access because it can be set up in the cloud and accessed remotely through the internet.

●	Data consistency in multi-document transactions is guaranteed by MongoDB's ACID (Atomicity, Consistency, Isolation, Durability) transactions. This aids in avoiding data errors or inconsistencies that may arise when using eventual consistency models.

●	MongoDB makes it simple to manage and keep an eye on the database because of its user-friendly interface and simple-to-use administration tools. Large, distributed databases can be scaled and managed more easily because of its automatic load balancing and sharding features.

**Challenges:**

This project started off with different scope and ended with a more enhanced scope.During this period we faced various challenges which we tackled quite comfortably with help of each team member , sponsor and professor's guidance.

1. Deciding dataset- To complete the project's aim, it was necessary that the data was easily accessible and quite accurate. One of the biggest challenges in this project was the availability and quality of the data.We faced difficulty in finding appropriate datasets that contained information on ESR (employment status rate) of disabled people based on their ancestry and other variables.

2. Data Cleaning and Preprocessing: Data cleaning and preprocessing was an essential step in any data analysis project. However, it was a time-consuming and challenging process, especially because of the format of the data we got in through the website, where we had to download multiple datasets and mix them into one and do that process several times and form multiple datasets as per the requirement of our project.

3. Interpreting Results: Once the datasets were finalized, interpreting the results and presenting them in a clear and concise manner was a little complicated. It is essential to communicate the results accurately and to avoid misinterpretation. Because of multiple datasets, the data had to be thoroughly examined and results were to be presented in the best and helpful manner.

**Results and Insights:**

●	Out of all the people with disabilities employed at work, the highest percentage of employment is observed in females having Tibetan ancestry with an employment rate of 90.1%. Whereas the highest rate of employment for males with disabilities is found in men with Sri Lankan ancestry who have an employment rate of 68.1%. It is thus observed that females with disabilities have a higher rate of employment than males.

●	The rate of employment for women having tibetan ancestry is higher than the rate of employment of women with tibetan ancestry having no disability.

●	The highest percentage of people by descent with disabilities who are employed but do not work are just 6.6% (Indonesian Women). This is a relatively low number and indicates that the majority of people having disability and a job work in spite of being handicapped.

●	It is observed in a lot of ancestries that men and women having a disability and a source of employment are more likely to work at their jobs as compared to their abled counterparts.

●	The unemployment rates of people with disabilities are higher in men than women.

●	Disabled unemployed women of burmese, cantonese, indonesian, vietnamese and laotian ancestry earn more than their non disabled counterparts.

●	The percentage of women and men not in the workforce is slightly higher in females than males. The highest rates of exclusion from the workforce are observed in bhutanese women and hmong men in their respective genders.

●	The average income earned by disabled men who are not in the workforce is  higher than disabled women who are not in the workforce.

