# Deloitte Digital Coding Exercise -  "Loyalty Program Prototype"
 
## Business Context
 
Our client is building a loyalty program for its customers that allows accumulating points through sales which can be later redeemed for a reward to encourage purchasing in the future. Since the loyalty program functionality will be deployed and updated independently of the core offerings of the company, it needs to be built as a standalone web service available over HTTP, which will be consumed by other services of the platform. Your task is to implement the first prototype of this service.
 
## Functional Requirements
 
The service prototype must support the following two use cases:
 
1) Register points after a purchase has been made. The sales subsystem of the company should be able to submit the points earned by the customer when an online purchase is happening. The data supplied by the core sales service for a transaction should contain the following fields:
- Customer ID
- Date of purchase
- Points earned
 
2) Retrieve number of total earned points. To support displaying the number of points collected on the company’s product website, the service must be able to return the sum of loyalty points collected by a certain customer, identified by Customer ID. To encourage customers to spend their points, the company decided that points earned earlier than 6 months should automatically expire hence the service must not include those in the sum of the available points.
 
The API and business logic of the service prototype must be designed and implemented in accordance with these requirements.
 
## Out of scope
 
Since the first prototype will be used for demonstrational purposes only, it is not necessary to permanently store data (e.g. in RDBMS), in-memory storage will suffice as long as it is clearly separated from business logic with appropriate interface(s). 

Similarly, security or performance is also not a concern at the moment.
 
## Expectations
 
For the submission we expect:
- The code to be available in an online repository (e.g. GitHub, Bitbucket, GitLab) OR shared online via cloud storage archive (e.g. zip file in Google Drive, OneDrive, Dropbox)
- The solution to be implemented in a widely used programming language e.g. Java, JavaScript, Python or .NET Core
 
You will be judged on
- Whether the solution fulfils the requirements
- How the service contract (aka API) looks like
- Simplicity, quality, and readability of the code
- The good use of OO principles and design patterns
- The presence and quality of automated test(s)
 
## Any questions?
Feel free to contact Mr. Andras Berke at aberke@deloitte.at.
