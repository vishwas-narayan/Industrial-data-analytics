# Detect Product Faults with a Smart Quality System at Kruse GmbH - Industrial Data Analytics

### Problem Statement:
Kruse GmbH is struggling with increasing quality problems and inefficiencies in maintenance in production of their highest-selling product, the washing machine.The front panels are particularly affected by the quality problems. Embossing with subsequent printing by a stamp results in a reject rate of 5-10%. Another problem is the frequent stoppage of the conveyor belts. This has resulted in a very expensive regular replacement of the bearings.

### Task: 
Help the Kruse GmbH and develop a monitoring system, that identifies the quality of the printing on the product using the historical vibration data and the quality and production log-data.

### Dataset Description: 
There is data for one bearing with 2 acceleration sensors. The data set consists of individual files that are 1-second vibration signal snapshots recorded at specific intervals. Each file consists of a time series with 20.480 points at a sampling rate of ~20 kHz. The file name indicates when the data was collected. Each record (file) represents a production process and a corresponding product (row in production or quality log respectively).
