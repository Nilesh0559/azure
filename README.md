# Types of cloud services –

## IaaS (Infrastructure as a Service) –

1. Cloud provides underlying platform and client handles or is responsible for rest.
2. Eg. VM (Cloud provides host machine, networking and disks while client installs software and is responsible for maintaining and patching it)

## PaaS (Platform as a Service) –

1. Cloud provides host machine, networking, disks and also runtime environment for running and hosting applications and also maintains and patches it while client only brings code and run it on compute environment.
2. Eg. Web Apps

## SaaS (Software as a Service) –

1. It's software that is running completely in cloud and cloud is responsible for maintaining and patching all the necessary things required for the software. Client doesn't need to install anything on-premises and will only use the software.
2. Eg. MS Office 365, Salesforce

# Types of cloud –

## Public –

1. Public Cloud is set up in public network and available to all clients and users throught network.
2. Eg. AWS, Azure, Google

## Private –

1. Private cloud is set up in organization's premises which is managed by IT team of the organization and is accessible through organization's network only.
2. Eg. VMware, Red Had Open Shift, Azure Stack

## Hybrid –

1. Hybrid cloud is combination of both public and private cloud.
2. Eg. Azure Arc, AWS Outposts

# Important basic concepts of cloud/azure

## Regions –

• Geographical location of datacenter is called region. Region may have single datacenter or group of datacenters in case if any single datacenter fails.
• Factors to consider while selecting region –

1. Client/User location
2. Service availability
3. Availability zones
4. Pricing
5. Paired region

## Zones –

• Each datacenter is called zone. When there is more than one datacenter in region, region is said to have Availability Zones.

## Paired Regions –

• Some regions have designated pair of regions so that if one region fails, the other paired region can fill the place of failed region which increases the availability.

## Account –

• Account is an identity to access the resources in subscription.
• Single account can be attached to multiple subscriptions.

## Subscription –

• Subscription is a logical container for all resources you provision in cloud (VM, network, disks,...)
• Single subscription can be attached to multiple accounts.

## Resource Groups –

• It's logical container for resources and used for grouping resources using logic boundary.
• Eg. dev/test/prod
• While defining resource group, it's best practice to use 'rg' or 'RG' as prefix or suffix.
• Eg. my-rg, RG-Project-Dev

## Storage Account –

• Storage account is resource in azure which is used to store almost anything in azure.
• Storage account can contain stuff like - database backups, VM disks, diagnostic data, explicit data storage etc.

## SLA (Service Level Agreement) –

• SLA defines the up-time percent of azure services.
• SLA plays an important role while creating service.
• To calculate the SLA of whole system, multiply the individual SLA of each service used in that system.
• One of the online tools to calculate SLA: [SLA Tool](https://uptime.is/)

## Costs –

• Almost everything in cloud except for some, costs money.
• Costs depends on pricing model –

1. Per resource (eg. VM)
2. Per consumption (eg. Function Apps)
3. Reservation (Upfront payment on resource for certain period which benifits discount)
   • Azure calculator: [Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/)
