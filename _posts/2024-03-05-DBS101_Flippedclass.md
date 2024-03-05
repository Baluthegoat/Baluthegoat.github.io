---
Title: DBS101 Flipped Class 3
Categories: [DBS101, Flipped_Class3]
Tages: [DBS101]
---

### Topic : SQL set operation and null values
---
During the flip class I learn about the SQL set operation. SQL set operation is used to combine the two or more SQL statement. There are mainly 4 types of set operations namely **union**,**union all**,**intersect**,**minus**.

![alt text](sql.png)

**Union** in this operation when two table is joined the output will be combined into one result set. If there is duplicate value in the table it will be eliminated.

![alt text](union.png)

**Union All** in this operation when two table is joined the output will is shown without eliminating the duplicates values in the table.

![alt text](unionall.png)

**Intersect** in this operation the output shown will be those values in the rows that are common to both the table.

![alt text](intersect.png)

**Minus** in this operation the output shown will be the column that are unique in the first query.

![alt text](minus.png)

During the flip class we discuss about the **Null values** in SQL. Null values are filed that are kept blank during the time of record creation because the information might not be available and also null value is different from every other null value. To test the null values it is not possible to use operator such as **=**,**<**,**>**, or **<>**. Instead we have to use **IS NULL** to test the empty values and **IS NOT NULL** to test the non-empty values. Moreover null values and zero value is completely different. On top of that null values has three interpretations. **The unknown value**,**Value not available**,**Attribute not applicable**.

To improve the flip class I think if we can do the database practical because we can learn more when doing the practical than the theory.
