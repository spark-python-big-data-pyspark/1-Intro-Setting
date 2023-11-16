# 1-Intro-Setting

1. [What is Spark? Why Python?](#schema1)
2. [Databricks Setup](#schema2)
3. [Primera ejecución en Databricks](#schema3)

<hr>

<a name="schema1"></a>

## 1. What is Spark? Why Python?

![big_data](./img/big_data.png)

### Local versus Distributed

![big_data](./img/big_data_2.png)

### Big Data

![big_data](./img/big_data_3.png)

![big_data](./img/big_data_4.png)

### Hadoop

![big_data](./img/big_data_5.png)

### Distributed Storage - HDFS

![big_data](./img/big_data_6.png)

### MapReduce

![big_data](./img/big_data_7.png)

![big_data](./img/big_data_8.png)

### Big Data

![big_data](./img/big_data_9.png)

### Spark

![big_data](./img/big_data_10.png)

![big_data](./img/big_data_11.png)

### Spark vs MapReduce

![big_data](./img/big_data_12.png)

![big_data](./img/big_data_13.png)


### Spark Rdds

![big_data](./img/big_data_14.png)

![big_data](./img/big_data_15.png)

![big_data](./img/big_data_16.png)

![big_data](./img/big_data_17.png)

![big_data](./img/big_data_18.png)

### Spark DataFrames

![big_data](./img/big_data_19.png)



<hr>

<a name="schema2"></a>
## 2. Databricks Setup

https://databricks.com/try-databricks

Y usar la Comunity Edition y seguir los pasos.

<hr>

<a name="schema3"></a>
## 3. Primera ejecución en Databricks

```
import pyspark
df = sqlContext.sql('SELECT * FROM mytable')

df.show() # similar al print()

```

![databricks](./img/data_b_1.png)




