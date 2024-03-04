Major Accomplishments for the Week
	- Provisioned Infrastructure Stack for GenAI SDK Project
	- Completed Infrastructure Onboarding Form
	- Met with Viswanath About Load Balancing OpenAI Service
	- Attended Overview of EFF Platform led by Ajit 

What to Work on Next Week
	1. Complete formatting for Infrastructure Onboarding Form and prepare for presentation. Discuss with Ravi what I need to say in the presentation. 
	2. Consolidate all infrastruture provisioned into one form for the GenAI SDK team. Create Jira story for checking off that each one of these connects as planned.


Detailed Accomplishments

Provisioned Infrastructure Stack for GenAI SDK Project
Last week, a spent a lot of time troubleshooting the EFF project getting up and running. It seems pretty clear that there needs to be significantly more detailed documentation to make this process easier for that team, and any other teams that we choose to onboard. Although I started making an "Azure DevOps" guide, this documentation starts to get made, but it becomes unformatted, and gets sprawled everyway, with different conventions. This week - I should prioritize writing the Confluence documentation for Azure DevOps deployments at least, and begin the process of building out the platform knowledge base. 

As that freed up, I had more time to spend provisioning infrastructure for the GenAI project. At night, in the afternoons, I used my personal computer to provision infrastructure stacks. This was very helpful for completing this project I provisioned a Key Vault, CMK for customer managed keys for encrypting data, Storage Account, Storage Container, Azure Files Share, Cluster Identity for using Managed Pod Identity.  I ended spending, what is probably too much time, focusing on the issue of injecting Azure Files as volumes, which would allow the GenAI SDK team to be able to have the same file as a volume, in Azure Files. It may be time to pass that onto someone else though, for now. I could encourage them to use a local volume until I get this sorted out and we have something for them, and give them an estimate of a few weeks. 

I think a good next step is to consolidate all infrastructure provisioned into one document, and create a Jira story for 

Situation - I have never used Terragrunt - and the GenAI SDK team had a need for this infrastructure
Task - needed to provision infrastructure
Action - Steped up as lead, took ownership of their project, and gave them tools
Response - we were able to deploy the LLM Gateway 

Other Reflection

I need to spend more time recording after meetings with Ravi.
One important thing that Ravi said is that Dushant's team was going to be using Databricks for vector DB capabilities, etc, for performing "Smart Research". 
I think it is important to collaborate on building out a Platform Topology board. 
I should prioritize writing the Confluence documentation for Azure DevOps deployments at least, and begin the process of building out the platform knowledge base. I should also write documentation on using Workload Identity / AAD Pod Identity. I should talk with Sriram about that this week - but first, I should prioritize understanding it. I already provisioned and successfully accessed Azure Key Vault using Workload Identity by creating a Federated Identity. 
I am curious about our network topology - I should research this more.
It is becoming more obvious that I NEED to understand Azure AD / Azure RM, and the distinction between these two. Although I have a tentative grasp on MI, role assignments, etc, I still don't understand the concepts of SPN, etc, fully to the point that I don't keep running into trouble. This should be prioritized above all else in my personal learning, even though it does not have a direct impact on the work that I am performing... It will very much come into play.
I should discuss with Sriram how we are managing and monitoring Kubernetes workloads. This is also where I think that Kubernetes knowledge would come into play (and I forgot, I studied this!) is limiting the amount a resource can take.
I need to reconnect with Viswananth about the Azure OpenAI load balancing. 

I should make a list of priorities and rank them. 

I think that the work that I have been doing on Terraform / Kubernetes on my own time has been very helpful. Understanding selectors and labels, how to go into the nodes of a cluster to debug events, etc, these have all been helpful as I've been going through that book. This includes the networking I've learned, use of LAW, role assignments, etc, have been helpful. I've been able to develop a process for learning these concepts, and it has paid off greatly. I also like how I was able to report on their infrastructure - 

Agenda for GenAI SDK Meeting
	- Go over infrastructure form that consolidates the infrastructure their team has been provisioned. Let them understand that I need to know soon whether components work as intended, and create action items for validating this. 
	- Set dates for how this will be deployed going forward. Discuss the deployment schedule with code review.
	- Discuss how their team provisioned an "Ingress" resource. Did they package this with their helm chart? Are they using one ingress resource? Should I be the one provisioning this resource?
	- Discuss their strategy for Load Balancing calls to the OpenAI service and provider.
	- Provide the team the Infrastructure Onboarding Form, and discuss its completion, and the timeline for its completion. Who will be responsible for what? What dates will these items be due?
	- Are they using a Secret Class Provider for injecting their secrets? Are they using Pod Identity?  
Introduce further things like limits, pod managed identity, health checks, readiness checks, 
