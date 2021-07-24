# Kubernetes-CKAD-Notes
All the notes for CKAD preparation exam 

**Google free tier use** 
300 dollars free for 12 months with any GCP services 

**AWS Nodes**
aws.amazon.com 

Management Console -> Check Region 
Launch a virtual machine - EC2 - Ubuntu 18.04 -> 2 proc and 8GB Memory - M5a large 

2 instances 
Storage - 8 to 20GB - Delete on terminations 

lfclass 
Configure security group - All code 

lfclass - key pair 

one instance - master node 
one instance - worker node 

username - ubuntu 

### Exercise 2.1: Overview and Prelimnaries 
- 2 CPU 
- 8 GB Memory 
- 20 GB disk space 
- Don't use 192.168 network for nodes 
- No firewall 
- Disable swap 
- Disable SELinux and AppArmor 

### Exerrcise 2.2: Deploy a new Cluster 

** Deploy a Control Plane Node using Kubeadm 

### Exercise 2.3: Create a Basic Pod 

The smallest unit we directly control with Kubernetes is the pod 

### Exercise 2.4: Multi Container Pods 

Composite Containers 

### Exercise 2.5: Create a Simple Deployment 

Creating a pod does not take advantage of orchestration abilities of Kubernetes. We will now create a Deployment which gives us scalability, reliability and updates 

### Exercise 2.6: Domain Review 


