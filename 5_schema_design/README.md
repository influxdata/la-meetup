# 5. Schema design (45-60 min) 2:00-3:00
* A little bit deeper with the InfluxDB Data Model (RP's and Databases)
* Continuous Queries and Retention policies
* Schema Design (Project)

## By the end of this section students will be able to...

* Identify poorly designed schemas
* Design a basic schema for a common use case and query it efficiently.
* Explain what a continuous query is and why they are used.
* Create their own continuous queries.
* Describe what a retention policy is and its relations to databases and series.
* Create a retention policy.
* Combine retention policies and continuous queries in novel ways to manage their data's lifecycle.

## Quiz (20 min) 3:00-3:20

* Design a schema

# 1. What would happen if I wrote the following points into InfluxDB? And why does it happen?
```
mem,location=us-west host="server1",value=0.5 1444234986000
mem,location=us-west host="server2",value=4 1444234982000
mem,location=us-west host="server2",value=1 1444234982000
```

# 2. What is the problem with having a large number of independent tags?

```
random,week=10,weekday=tues,meowmix=k,birthday=july,...,host=api0 value=2 144423498200
```
# 3. What is a retention policy?

# 4. What is the relationship between retention policies, databases, and series.

# 5. What is a continuous query? How are they used?

# 6. Design a schema

The following information is emitted to InfluxDB every 10 seconds from 10,000 unique devices.

* zipcode
* city
* latitude
* longitude
* device_id
* smog_level
* co2_ppm
* lead
* so2_level

