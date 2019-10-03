# Jenkins Server As A Code
This repo contains the Infra As A Codes (IaaC) to spin-up and operate Jenkins using AWS CloudFormation and Helm/Kubernetes instantly.

# AWS Jenkins Instance Features!
  - 2 Load-balanced, keep-alive Jenkins Masters
  - Zero to Many Auto-Scaling Jenkins Slaves
  - Horizontal Scaling features using Amazon Elastic Container Service. e.g. Add more instances when 70% CPU usage is reached.
  - Automated jobs creation

# Kubernetes Jenkins Instance Features! 
  - 1 Keep-alive Jenkins Master running in Google Cloud
  - Zero to Many Auto-Scaling Jenkins Slaves using Kubernetes Pods
  - **Vertical** and Horizontal Auto-Scaling features
  - Note: Some Vertical IaaC configs are on the Cluster level. Codes are not included in this Repo.
  - Vertical means add more CPU/RAM allocation on both Master and Slaves if needed

# Jenkins Jobs Features!
Installed in Kubernetes Instance
  - Auto-creation of Folders based on TEAMS or ORGANIZATIONS
  - Auto-creation of Jenkins Jobs based on Branches and Pending Pull Requests
  - Auto-deletion of Jenkins Jobs when the branch is deleted

# What should I use?
> If AWS is available in your company, use AWS due to more features available
> If your Servers are VM Based, use Kubernetes
> Note: On Premise AWS cloud is way more expensive compare to Kubernetes

# Demo Links
Email me at <mikael@actnow.earth> so I can spin-up the instances for you and email back the links for hands-on experience.
