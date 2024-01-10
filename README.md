# AWS-PROJECT-
![vpc-example-private-subnets (1)](https://github.com/ankitabhadani/AWS-PROJECT-/assets/121809266/8f5d66ff-5528-4432-9b50-459ca19b48a6)

## Project: Two-Tier Deployment on AWS


**Description:**

This project illustrates a two-tier deployment architecture on AWS with segregated public and private subnets across two Availability Zones.

**Features:**

- :cloud: **VPC Configuration:** Established Virtual Private Cloud with segregated subnets.
- :electric_plug: **NAT Gateway Setup:** Enabled secure internet access for private subnet servers.
- :balance_scale: **Load Balancer Nodes:** Efficiently managed traffic distribution.
- :computer: **Auto Scaling Groups:** Implemented for automatic server scaling based on demand.
- :link: **Connectivity:** Established seamless connections between servers and load balancers.

### Implementation Steps

1. **VPC Setup:**
   - Created distinct public and private subnets across multiple Availability Zones.
   - Configured NAT gateways in public subnets for secure internet access.

2. **Load Balancer & Auto Scaling:**
   - Implemented load balancers for traffic distribution.
   - Set up Auto Scaling groups for automated scaling based on demand.

3. **Server-Load Balancer Connectivity:**
   - Established connections for effective request handling.

### Results

Successfully deployed a secure, scalable two-tier architecture on AWS, ensuring efficient traffic management and reliable server performance.

### Tools & Skills Utilized

- AWS (VPC, NAT Gateways, Load Balancers, Auto Scaling Groups)
- Networking
- Security
- Infrastructure Management

*Note: Utilized a jump server for secure access and management within the infrastructure.*

