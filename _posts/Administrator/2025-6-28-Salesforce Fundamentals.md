---
title: 1.Salesforce Fundamentals
date: 2025-06-28
categories: 
tags:
---
### 1. Explorer Salesforce

- Easy to integrate new applications, and build your own custom applications

- Salesforce Platform  
	Sales Cloud: Manages ==leads== and ==opportunities== - helps predict customer needs.  
	Service Cloud: Support ==personalized customer service== and helps manage support requests.   
	Marketing Cloud: ==Automates== marketing through ==email, mobile, web== channels.   
	Experience Cloud: Builds ==portals== for handling customer ==complaints== and interactions.  #experiencecloud   
	Tableau:  Assists in ==quick decision-making== with data analysis.  
	Commerce Cloud: Enables ==automation==, delivers a personalized commerce experience.  

- Multi-Tenant Cloud
	Single instance of the sw, db and supporting infrastructure serves multiple customers, while each tenant's data is isolated and remains invisible to other tenants.

![[Pasted image 20250512113032.png]]


### 2. Salesforce Architecture

###### Standard Objects

Account: A ==business== or (nonprofit) ==organization==  
Contact: An ==individual== associated with an account.
Opportunity: A potential sales deal or revenue-generating event.  
Lead: A potential customer or ==prospect==.
Campaign: A marketing initiative, such as an ==email== promotion.  
Case: ==A customer inquiry== or issue that requires resolution.  
User: Could be employees or partner users

###### Standard Object Relationships

- Lookup Relationship(Parent-Child):  One Object references another - the parent object holds the reference

- A Campaign(like an email, ad campaign) is not directly connected to Lead or Contact. But they are linked through a ==Campaign Member== object.

### 3. Preparing For Changes

###### What is a Sandbox?
A copy of your production environment used for development, testing, training.
It's isolated from the live environment and not visible to end users.
Once changes are made in the sandbox, they must be deployed.

You can create a developer sandbox from:
Setup -> Sandbox 


