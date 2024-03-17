---
Title: DBS101 Flipped Class 4
Categories: [DBS101, Flipped_Class4]
Tages: [DBS101]
---

### Topic : Advanced Aggregation Functions
---
During flip class I learned about **Ranking**,**Pivoting** and **Rollup and club**. 
The rank function it allocates a rank that is an integer number to each row within a group of data sets. Moreover the frequent use case of the **RANK()** function is creating reports for the top N or bottom N records. Rank function is used with the **OVER()** clause. **RANK() OVER()**. On top of that the rank function allows us to rank the rows based on the provied columns instead of retrieving the consecutive integers. 

The **Pivot** function is used to convert rows into columns by presenting the data in a tabular form. To create a pivot table it uses the **crosstab** function to convert rows into columns.

The **Rollup and club** function makes it possible for the values to be aggregated on the several different axes satisfying more detailed reporting needs. **Rollup** summarizes against a hierarchy of columns used in the group by clause. **CLUB** groups all the combinations of the values.

During the flip class we discuss about the **windowed aggretion**. It is used for task such as calculating totals, moving averages and ranking within the data. It uses the key components such as **Partition by** that divides the set into partion. **order by** that determines the order of rows in each partion. **rows between/ range between** that specifies the window frame. The **rows between** it is based on the number of rows and **range between** it based on the values of the rows.

No comment on the improvement because every thing is going well in flip class. since we did parctical in the filp class. we are able to take more information.