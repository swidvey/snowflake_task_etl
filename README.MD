<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.netguru.com%2Fhs-fs%2Fhubfs%2FSnowflake%2520logo.jpg%3Fwidth%3D653%26name%3DSnowflake%2520logo.jpg&f=1&nofb=1" alt="Snowflake ETL" title="Snowflake ETL">

### Snowflake Task ETL Example
```
This is an example of a basic snowflake ETL task process.
This file shows a basic in take from an AWS to Snowflake. 


A task can execute a single SQL statement or a call to a stored procedure. 
Tasks can be combined with table streams for continuous ELT workflows to process recently changed table rows. Streams ensure exactly once semantics for new or changed data in a table.

```
______________________________________________________________________
______________________________________________________________________
### Files
```
ddl.sql:
    Shows how to create a table in snowflake and define table values

snowflake_task_etl.sql:
    Shows how to create file format, drop tasks, and create tasks.
```

______________________________________________________________________
______________________________________________________________________
### Data Example

| EMAIL    | BIRTH_YEAR | BIRTH_MONTH | BIRTH_DAY  | GENDER     |   ZIP_CODE | TRACKING_ID | VENDER_ID
|----------|:----------:|------------:|-----------:|-----------:|-----------:|------------:|------------:|
| abc@fake.com |   1963 |          01 |         15 |   male     |      60026 |   123456789 |       12abt |
| def@fake.com |   2004 |          12 |         23 | female     |      81126 |   223456789 |       72ahc |
| ghi@fake.com |   1990 |          09 |         04 | non-binary |  14216-123 |   323456789 |       62awj |

    