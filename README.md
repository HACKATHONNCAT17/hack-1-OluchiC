# Hack #1
The repository contains the problem statement for Hack #1 provided by Oracle.

## Problem Statement:

Deploy a microservice which generates unique names based on a naming convention that is both human and machine friendly.

## Background:

The modern world of software development is guided by the principles of good Microservice Architecture in the cloud. Each service has an independent lifecycle from the rest of the services in its ecosystem, serves a distinct purpose, and strives to be as stateless and ephemeral as possible.

The adage which governs the operations of services such as these is to treat all instances, whether they be virtual machines or containers, as “Cattle, not pets.” That is, every instance should be viewed as a disposable unit which may be quickly replaced or substituted.

This new view of infrastructure as cheaply expendable comes with a host of advantages, but inevitably a problem arises. How do you keep track of dozens, hundreds, or even thousands of instances? 

A new microservice could help deal with this problem…



## Scoring Rubric:

These are a series of questions which will influence the scoring of each hack. Not all questions are of equal weight, and many will require real-world trade-offs to maximize for the type of solution implemented.

### Design:

- What data source is used to create the names?
- Can a human request names? A machine?
- Can the naming convention be supplied by the user?
- Can a theme for the names be supplied by the user?

### Construction:

- How many lines of code were needed?
- What is the highest cyclomatic complexity in the code?
- Was source control used effectively?
- Were any common design patterns effectively leveraged?

### Testing: 

- What is the level of test coverage?
- Is there a Continuous Integration / Delivery / Deployment pipeline?

### Operational Characteristics:

- How is the microservice deployed or updated?
- Can the microservice be self-hosted?
- Is the microservice available over the internet?
- How performant is the microservice providing N-number of names?


### User Experience:

- Is the interface with this microservice intuitive?
- Was humor effectively used to help with human engagement / memory?
- Are usage docs provided, or ultimately unnecessary?


### Security:

- Is communication with this microservice secured and encrypted?
- What is done to protect any user provided data?
- How is risk distributed in the service?
- Is the service highly available? Does it have a disaster recovery plan?

