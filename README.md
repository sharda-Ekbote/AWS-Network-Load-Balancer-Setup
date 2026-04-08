AWS-Network-Load-Balancer-Setup

The configuration of an AWS Network Load Balancer (NLB). Unlike the Application Load Balancer, the NLB operates at the transport layer
(Layer 4) and is designed to handle millions of requests per second with ultra-low latency, making it ideal for high-performance TCP,
UDP, and TLS traffic distribution across multiple availability zones.

Architecture Components
->Network Load Balancer (NLB): A high-performance load balancer for Layer 4 traffic.

->Target Groups: Groups of backend resources (instances or IP addresses) that receive traffic on specific ports.

->Listeners: The process that checks for connection requests using the configured protocol and port.

->Availability Zones: Multi-AZ deployment (us-east-1a and us-east-1b) for fault tolerance.
