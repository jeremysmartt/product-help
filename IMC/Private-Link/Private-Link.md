### PrivateLink

AWS PrivateLink lets you access AWS and third-party services hosted within AWS privately and securely. Add AWS accounts to allow traffic between your Virtual Private Cloud (VPC) and your Vantage site.

After you add an account, you must set up an AWS service endpoint for it using the Amazon VPC console.

#### Setting Up an AWS Service Endpoint

1. Log on to the target AWS account.
1. From the Amazon VPC console, go to **Security Groups** in the **Security** section.
1. Update the database security group to allow the inbound ports for the database (port 1025)
and Teradata Viewpoint (ports 80 and 443) from the VPC CIDR.
1. Go to **Endpoints** > **Create Endpoint**.
1. In **Service Category**, select **Find service by name**.
1. In **Service Name**, paste or type the **Endpoint** displayed in the Console.
1. Select **Verify**. If the PrivateLink Service Endpoint is active, the message **Service name found** appears.
1. Select the VPC, subnet, and security group you’ll use to connect.
1. Select **Create Endpoin**t.
1. Report the status by logging a support ticket.
1. After the status shows available, use telnet to validate connectivity between your VPC and the
Vantage site for each port number using the format *telnet DNSName PortNumber*.



