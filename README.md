# Building the AIRE Framework

This repo is the companion repo for the Building the AIRE Framework livestream series.

In this series, we'll build a complete AI Reliability Engineering (AIRE) framework from the ground up. We'll show you how to transform traditional automation into context-aware AI agents that understand your systems, follow best practices, and work alongside human engineers to enhance reliability.
Throughout this series, we'll progressively develop AI agents that generate Terraform configurations, integrate with GitHub for version control, and validate AWS resource deployments—creating a full-circle AIRE system. Whether you're an SRE looking to reduce alert fatigue or a platform engineer interested in more resilient systems, this series will show you practical ways to implement AIRE principles that make both your infrastructure and your team more dependable.

## Part 1: Building a Terraform AI Agent

In the first session of the AIRE Framework series, we'll build a Terraform AI agent using kagent and MCP.
Join us as we:
- Introduce the concept of AI Reliability Engineering and how it differs from traditional automation
- Create and refine agent instructions in real-time to generate Terraform configurations
- Integrate with the AWS Labs Terraform MCP server to ensure adherence to infrastructure best practices

Watch the recording here: https://www.youtube.com/watch?v=paqxLLotp3k

## Part 2: Building an IaC Agent

We're back for the second session of the AIRE Framework series! Last time, we built a Terraform AI agent, and this time we're levelling it up! 

In this stream, we'll create an IaC agent that combines the Terraform AI Agent and a GitHub MCP server. This will allow us to take the generated Terraform config and create a PR on GitHub.

Watch the recording here: https://www.youtube.com/watch?v=UUFuL-XRINU


## Part 3: Building an AWS Validation Agent

Time to build the last agent in the AIRE series! 

During the past two streams we've built:
Terraform agent that uses AWS Terraform MCP and generates a Terraform configuration
Git PR agent that uses Git PR MCP server and can clone repositories, create branches, commits, and PRs.

We also have an overarching AWS IaC agent that delegates work to Terraform and Git PR agents. 

In this last stream of the series, we'll build an AWS Validation Agent. Once a GitHub PR is created and approved, the GitHub Action runs the plan and apply commands to deploy the resources.  

The AWS Validation Agent will check that PR and use an AWS MCP server to check whether the resources were deployed, and give us an overview.

Watch the recording here: https://www.youtube.com/watch?v=iSXqlVc684s