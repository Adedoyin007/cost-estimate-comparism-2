# cost-estimate-comparism-2
my-lab
Cloud Cost Comparison Project (Azure vs AWS)

Overview

This project presents a cost comparison between Microsoft Azure and Amazon Web Services (AWS) for a basic cloud infrastructure setup. It highlights pricing differences, key cost drivers, and how cloud pricing calculators can be used to estimate expenses.

⸻

Project Objectives

* Compare cloud service costs across Azure and AWS
* Analyze pricing for compute resources
* Demonstrate the use of pricing calculators
* Provide a clear and transparent cost breakdown for decision-making

⸻

Architecture Summary

The infrastructure used for this comparison includes:

* 1 Virtual Machine / EC2 Instance
* Minimal or no storage usage
* Basic outbound data transfer
* Pay-as-you-go pricing model

⸻

Azure Cost Breakdown

Summary

* Total Monthly Cost: $10.22
* Upfront Cost: $0.00

Services Used

Compute (Virtual Machine)

* Instance Type: B1s (1 vCPU, 1 GB RAM)
* Region: East US
* Usage: 730 hours/month
* Operating System: Windows (license included)
* Estimated Cost: $10.22/month

Storage

* No storage usage included

Support

* No support plan selected

⸻

AWS Cost Breakdown

Summary

* Total Monthly Cost: (Add your value)
* Upfront Cost: (Add your value)

Services Used

Compute (EC2)

* Instance equivalent to Azure B1s (e.g., t2.micro or t3.micro)
* Region: (Specify region)
* Pricing model: Pay-as-you-go

Storage

* (Specify if used, e.g., EBS volume)

Data Transfer

* (Specify outbound data if included)

⸻

Key Observations

* Compute resources are the primary cost driver in both platforms
* Azure provides a straightforward pricing model for low-tier VMs
* AWS pricing may vary depending on instance type and region
* Additional services like storage and support can increase total cost significantly

⸻

Tools Used

* Azure Pricing Calculator
* AWS Pricing Calculator
* Markdown for documentation

⸻

Repository Structure

├── azure_cost_report.md
├── ExportedEstimate.xlsx
├── README.md

⸻

How to Reproduce

Azure

1. Open Azure Pricing Calculator
2. Add a Virtual Machine
3. Select B1s instance
4. Set usage to 730 hours/month
5. Export the estimate

AWS

1. Open AWS Pricing Calculator
2. Add an EC2 instance
3. Choose a comparable instance (e.g., t2.micro)
4. Set usage to 730 hours/month
5. Review the estimated cost

⸻

Future Improvements

* Include more instance types for broader comparison
* Add storage and database services
* Compare reserved vs on-demand pricing
* Automate cost estimation

⸻

Author

Adedoyin007

⸻

License

This project is for educational purposes only.
