# Cyber Security Club Meeting 2 Notes

## What is Cloud Security

Cloud security is not one thing only, it is a collection of security measures put togther to make the whole thign more secure. Some of the security measures include:
-   Protecting cloud based infastructures
-   Applications
- Data
    - Protecitng user data, passwords etc. 


## Security Building Blocks

-   Software Updates
    - Security vulnerabilities are found in software every day
    - Updating software will remediate some of these vulnerabilites
-   Restrict access to your AWS account
    - Having access to the AWS account is like having keys to the kingdom

- Controlling network traffic to and from your EC2 instances
    -  Allow what ports can be open for incoming and outgoing traffic for virtual machines



- Creating a private network in AWS
    -  You can create subnets that aren't reachable form the internet.
    - VPC = Virtual Private Cloud
        - Public Cloud everyone has access
        - Private cloud you can limit who has access

- Securing your applications

    - How to handle and store confidential information?
        - E.g. Not saving passwords in plain text, using TLS/SSL to encrypt traffic between your VMs (virtual machines) and your users. 
    - You can also use [Amazon Inspector](https://aws.amazon.com/inspector/) to detect vulnerabilites in packages. 

## Who is responsible for security?

### AWS Side
- Protecting the network through autmotaed monitroign systems and robust internet access, to prevent DDos attacks
- Performing background checks on employees who ahve access to sensitive areas
- Decommissiong storage devices by physically destroying them after eof
- Ensurign the physical and enviromental security of data centers, including fire protections and security staff

Security standards can be checked by [compliance checker](https://aws.amazon.com/compliance/)

### Personal Side

- Implementing access management that restricts access to AWS resources like S3 to a minimum, using AWS IAM
- Encrypting network traffic to prevent attackers form reading or manipulating data(use HTTPS instead of HTTP)
- Configuring a firewall for your viryal network that controls incoming and outging traffic with security gorups and ACLs
- Encryoting data at rest. For example, enable data encryption for your database or other storage systems
- Manafing patches for the OS and additional software on VMs



