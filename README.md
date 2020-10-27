# Find a Standardized Workflow/Pipeline Product
> finding an enterprise workflow orchestration engine that can coordinate Continuous Integration pipelines and managee Continuous Deployment in a way that flexible and scalable enough to meet then needs of most teams in our ecosystem.   

## Problem Statement
- High performing teams practice continuous integration with trunk based development, automated testing of code, behavior and compliance for security and other governance. 
- These "Hardened" pipelines require standardization, stability and predictability, but must also fit the needs of multiple teams, products and technial stacks. Currently, every team in CVP seems to have their own pipeline of varying quality.
- How do we maintain team autonomy, while having a standard pipeline that can provide the safety and confidence of good governnance, while enabling teams to deliver value un-interrupted? 

## Expected Use Cases Covered by Solutions
> Identify which use case to cover and which are excluded
### Use Case: Embedded Systems Integration and Delivery
-Merge, Build, Scan, Test, Deploy to HIL/SIL
-Merge, Build, Scan, Test, Deploy to Bench
-Merge, Build, Scan, Test, Deploy to Vehicles

### Use Case: Mobile Application Integration and Delivery
- Merge, Build, Scan, Test, Certify, Deploy to Android
- Merge, Build, Scan, Test, Certify, Deploy to iOS

### Use Case: SDPR
- Merge, Build, Scan, Test, Deploy to Environments

### Other Functional Requirements
 - Enablement/Governance for Architecture Requirements using As Code
 - Enablement Security as Code
 - Enablement Policy Compliance as Code

## Proposed Solutions
### Solution 1: Concord
 [Open Sourced Concord From Walmart Labs](https://concord.walmartlabs.com/)
 Concord is a workflow server. It is the orchestration engine that connects different systems together using scenarios and plugins created by users.

>  Concord can be customized to execute any workflow, but here are a few specific examples of how Concord is used and tasks > it performs:
>  - Orchestrate numerous CI builds to create complex release artifacts
> - Create release, test and roll out pipelines
>  - Provision cloud infrastructure based on user input
>  - Deploy applications on Point of Sale and other hardware systems
> - Execute Ansible playbooks
> - Create, deploy and update OneOps assemblies and environments
> - Automatically create issues
> - Notify process-related parties via email and messaging
> Find out more details such as benefits and use cases in the overview section, learn about installing and using Concord from > the documentation and check out our overview and user training material.

[![](https://api.gh-polls.com/poll/01EN5T52PGSKQA42VT9MYBGE0F/I%20Approve%20of%20this%20solution)](https://api.gh-polls.com/poll/01EN5T52PGSKQA42VT9MYBGE0F/I%20Approve%20of%20this%20solution/vote)
[![](https://api.gh-polls.com/poll/01EN5T52PGSKQA42VT9MYBGE0F/I%20approve%2C%20but%20some%20questions%20or%20issues)](https://api.gh-polls.com/poll/01EN5T52PGSKQA42VT9MYBGE0F/I%20approve%2C%20but%20some%20questions%20or%20issues/vote)
[![](https://api.gh-polls.com/poll/01EN5T52PGSKQA42VT9MYBGE0F/I%20am%20uncertain%20about%20this%20solution)](https://api.gh-polls.com/poll/01EN5T52PGSKQA42VT9MYBGE0F/I%20am%20uncertain%20about%20this%20solution/vote)
[![](https://api.gh-polls.com/poll/01EN5T52PGSKQA42VT9MYBGE0F/This%20is%20not%20the%20right%20solution)](https://api.gh-polls.com/poll/01EN5T52PGSKQA42VT9MYBGE0F/This%20is%20not%20the%20right%20solution/vote)


### Solution 2: Gitlab
Gartner Recommends using Gitlab. 

GitLab CI/CD is a tool built into Git for software development through the continuous methodologies:

Continuous Integration (CI)
Continuous Delivery (CD)
Continuous Deployment (CD)

[![](https://api.gh-polls.com/poll/01EN5X5RQ18FCZ6YKH3TQM7HJE/I%20Approve%20of%20GitRobbed)](https://api.gh-polls.com/poll/01EN5X5RQ18FCZ6YKH3TQM7HJE/I%20Approve%20of%20GitRobbed/vote)
[![](https://api.gh-polls.com/poll/01EN5X5RQ18FCZ6YKH3TQM7HJE/I%20approve%20of%20GitRobbed%20with%20Some%20Issues%20or%20Questions)](https://api.gh-polls.com/poll/01EN5X5RQ18FCZ6YKH3TQM7HJE/I%20approve%20of%20GitRobbed%20with%20Some%20Issues%20or%20Questions/vote)
[![](https://api.gh-polls.com/poll/01EN5X5RQ18FCZ6YKH3TQM7HJE/I%20do%20not%20approve%20of%20GitRobbed)](https://api.gh-polls.com/poll/01EN5X5RQ18FCZ6YKH3TQM7HJE/I%20do%20not%20approve%20of%20GitRobbed/vote)

## Decision
> This is TBD and will be updated at the end of the process

## Consequences of Decision
> This is TBD and will be updated by the end of the deciion process
