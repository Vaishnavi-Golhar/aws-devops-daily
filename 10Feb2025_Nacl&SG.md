🚀 NACL vs. Security Groups in AWS 🌐
*********************************************
🔒 Security Group (SG): Think of it as a virtual firewall for your instances (EC2). Controls inbound and outbound traffic at the instance level. 
Stateful — when traffic is allowed in, the response is automatically allowed out.

🔑 Network ACL (NACL): Acts as a firewall for your subnet. Controls inbound and outbound traffic at the subnet level. 
Stateless — traffic rules need to be defined both ways (in and out).

💡 Use SG for instance-specific security and NACL for additional subnet-level protection!
