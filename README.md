# AWS_Lambda_Initialization_duration 
| Runtime | Avg initialization duration (ms) | Cold start rate |
|---------|:--------------------------------:|:---------------:|
| Java    |              362.99              |      0.036      |
| Go      |              207.57              |      0.0115     |
| C#      |              168.17              |      0.0075     |
| Ruby    |              141.30              |      0.013      |
| Node.js |              124.85              |      0.0335     |
| Python  |              119.67              |      0.0125     |

# AWS_Lambda_benchmark
| Runtime | Avg duration (ms) | Med duration (ms) | Errors | Max memmory used (MB) |
|---------|:-----------------:|:-----------------:|:------:|:---------------------:|
| C\#     |     0.87168766    |        0.81       |    0   |           72          |
| Python  |     1.42800914    |        1.4        |    0   |           50          |
| Node.js |     1.06222969    |        0.99       |    0   |           70          |
| Go      |     0.47596358    |        0.46       |    0   |           38          |
| Java    |     1.62852697    |        1.37       |    0   |          120          |
| Ruby    |     3.63998976    |        1.87       |    0   |           47          |
# Two version comparison
|           | Avg duration (ms) | Initial duration(ms) | Avg memory used (MB) |
|-----------|:-----------------:|:--------------------:|:--------------------:|
| Version 1 |    2003.946825    |      123.2357407     |         49.36        |
| Version 2 |     2030.47912    |      130.6162963     |         52.56        |
| Version 3 |    1030.418485    |      130.9151111     |         54.50        |
