# Python - Cloud Services - Intro into Cloud

## Task 1. Calculate costs difference between on-premises one server vs cloud solutions (IaaS - infrastructure as a service).

Take into consideration things like: 
* costs of hardware
* power consumption
* space

Chose one cloud provider (e.g. Google Cloud Platform, Amazon AWS, Microsoft Azure). Take into consideration a period of 1 month work. 

Asumme:
* price per kWh as 11 cents
* space cost as $100 per square meter

To calculate the cost difference between an on-premises server and a cloud solution (IaaS), we'll consider the following factors: hardware costs, power consumption, and space costs. We'll compare the expenses for a period of 1 month of operation.

For an on-premises server, we'll assume the following:

Hardware cost: $5,000 (one-time cost)
Power consumption: 200 watts
Space occupied: 2 square meters
For the cloud solution, we'll choose Amazon Web Services (AWS) as the provider and use their pricing information. Keep in mind that cloud prices can vary based on factors like region, instance type, and usage patterns. The example below provides a rough estimate based on general pricing assumptions.

For AWS, we'll assume the following:

Instance type: t3.medium (2 vCPUs, 4 GB RAM)
On-Demand Instance Pricing: $0.0416 per hour (as of September 2021, prices are subject to change)
Now, let's calculate the costs:

On-Premises Server:

Hardware cost: $5,000 (one-time cost)
Power consumption: 200 watts = 0.2 kilowatts
Power consumption per month: 0.2 kW * 24 hours/day * 30 days = 144 kWh
Power cost per month: 144 kWh * $0.11/kWh = $15.84
Space cost: 2 square meters * $100/square meter = $200
Total cost for on-premises server in 1 month: $5,000 (hardware) + $15.84 (power) + $200 (space) = $5,215.84

Cloud Solution (AWS):

Instance cost per hour: $0.0416
Instance cost per month: $0.0416 * 24 hours/day * 30 days = $29.952
Note: Additional costs may apply for storage, data transfer, and other services depending on your specific usage requirements.
Total cost for AWS cloud solution (IaaS) in 1 month: $29.952

Please note that this cost estimation is simplified and doesn't consider other factors like networking costs, data transfer fees, software licensing, and potential discounts or reserved instances. The actual costs can vary depending on your specific requirements, usage patterns, and the pricing structure of the cloud provider. It's always recommended to consult the specific pricing documentation 


## Task 2. Name pros and cons for using cloud vs on-premises.
