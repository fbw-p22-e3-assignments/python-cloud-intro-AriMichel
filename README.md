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
Pros:

Scalability: Cloud services offer the ability to easily scale resources up or down based on demand, allowing organizations to quickly adapt to changing needs without upfront hardware investments.
Cost Efficiency: Cloud services operate on a pay-as-you-go or subscription model, eliminating the need for large upfront hardware and infrastructure costs. Organizations only pay for the resources they consume, resulting in potential cost savings.
Accessibility and Mobility: Cloud services can be accessed from anywhere with an internet connection, enabling remote access, collaboration, and flexibility for users to work from various devices.
Reliability and Availability: Cloud service providers often have redundant infrastructure, multiple data centers, and disaster recovery mechanisms in place, ensuring high availability and minimizing downtime.
Maintenance and Updates: Cloud service providers handle maintenance, security, and software updates, relieving organizations of the burden of managing and updating their own infrastructure.
Cons:

Dependence on Internet Connectivity: Cloud services rely on internet connectivity, and disruptions or outages can impact access to data and applications. Organizations must ensure reliable and robust internet connectivity to avoid potential disruptions.
Data Security and Privacy Concerns: Storing data in the cloud raises concerns about data security and privacy. Organizations must carefully choose reputable cloud service providers, implement proper security measures, and adhere to compliance and data protection regulations.
Limited Control and Customization: With cloud services, organizations have limited control over the underlying infrastructure and software stack. Customizing certain aspects of the environment may be more challenging or restricted.
Potential Vendor Lock-In: Moving data and applications to the cloud can create dependencies on specific cloud service providers, making it difficult and costly to switch providers or bring services back in-house.
Potential Cost Over Time: While cloud services can offer cost savings initially, long-term usage can accumulate costs. Organizations must carefully manage their usage and monitor costs to avoid unexpected expenses.
Using On-Premises Solutions:

Pros:

Data Control and Security: With on-premises solutions, organizations have direct control over their data and can implement security measures according to their specific requirements and compliance standards.
Customization and Flexibility: On-premises solutions allow organizations to have full control and customization over their infrastructure and software stack, enabling tailored solutions to meet unique business needs.
Local Data Access: Having data stored locally can provide faster access and reduced latency, which can be beneficial for certain applications and industries.
Potential Cost Savings Over Time: Although on-premises solutions require upfront investments in hardware and infrastructure, over time, they may result in cost savings compared to ongoing cloud service subscription fees.
Regulatory Compliance: In some industries, compliance regulations may require organizations to keep data and applications on-premises for security or legal reasons.
Cons:

Upfront Hardware and Infrastructure Costs: On-premises solutions require significant upfront investments in hardware, data center infrastructure, and ongoing maintenance and upgrades.
Limited Scalability and Agility: Scaling resources in an on-premises environment can be more time-consuming and costly, requiring the purchase of additional hardware and infrastructure.
Maintenance and Updates: Organizations are responsible for maintaining and updating their own hardware, software, and security measures, requiring dedicated IT staff and resources.
Limited Accessibility: On-premises solutions may have limited accessibility, especially for remote workers or distributed teams, requiring additional infrastructure and connectivity solutions.
Disaster Recovery and Business Continuity: On-premises solutions require organizations to implement their own disaster recovery and business continuity plans, which can be complex and costly to set up and maintain.
It's important to note that the decision to use cloud services or on-premises solutions depends on various factors, such as business requirements, security and compliance needs, scalability demands, budget considerations,