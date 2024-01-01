#Creating VPC peering connection within one region
##
### Step 1 - Create the First VPC:
In the VPC dashboard, click on "Create VPC."
![image1][Lab4-VPC_Peering_OneRegion/images/image1.png]
Enter a name for your VPC (my-vpc-01)and specify the IPv4 CIDR block (10.0.0.0/16).
You can leave the rest of the settings as default or configure them based on your requirements.
Click on "Create VPC"
![image2][images/image2.png]

### Step  -Create the Second VPC:

Follow the same steps as above but provide a different name and IPv4 CIDR block for the second VPC (e.g., 192.168.0.0/16).
Click on "Create VPC"

### step -Create Subnet:
Inside each VPC, you'll need to create subnets. Subnets are logical segments of a VPC's IP address range.
Navigate to the "Subnets" section in the VPC dashboard.
Click on "Create Subnet" and specify the VPC, a name for the subnet, and an IPv4 CIDR block for each subnet.

### step -Create Internet Gateways:

An Internet Gateway allows communication between instances in your VPC and the internet.
In the VPC dashboard, go to "Internet Gateways" and create an internet gateway for each VPC.
