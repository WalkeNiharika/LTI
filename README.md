# LTI

Normalization : Normalization is a technique for designing relational database tables to minimize duplication (data redundancy) and in so doing reduce the risk of data anomalies (ie. deletion, update and insertion anomalies). 

There are a few problems with tables that are not normalized: There is a risk of an update anomaly. Because data is repeated, when we update we must update all occurrences. There are fields left empty – meaning space is wasted. There are repeating groups (or columns). If one student wanted to play for a fourth team we would need to add Team4, Coach4 and NMatch4 columns for all students.  

First normal form (1NF) sets the very basic rules for an organized database: Eliminate duplicative columns (repeating groups) from the same table. Identify primary keys.  

Second normal form (2NF) further addresses the concept of removing the need for duplicative data: Meet all the requirements of the first normal form. Remove subsets of data that apply to multiple rows of a table and place them in separate tables. Create relationships between these new tables and their predecessors through the use of foreign keys.  

Third normal form (3NF) goes one large step further to further reduce data redundancy: Meet all the requirements of the second normal form. Remove columns that are not dependent upon the primary key.
