# gbd-bug-collection

# hive

* HIVE-11837
comments do not support unicode characters well.

* HIVE-14959
Fix DISTINCT with windowing when CBO is enabled/disabled

* HIVE-11097
HiveInputFormat uses String.startsWith to compare splitPath and PathToAliases

* HIVE-13120
propagate doAs when generating ORC splits

* HIVE-14556
Load data into text table fail caused by IndexOutOfBoundsException

* HIVE-13749
Memory leak in Hive Metastore

* HIVE-11927
Implement/Enable constant related optimization rules in Calcite: enable HiveReduceExpressionsRule to fold constants

# spark

* SPARK-14495
Distinct aggregation cannot be used in the having clause
