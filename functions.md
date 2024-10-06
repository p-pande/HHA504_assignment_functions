## Serverless Function Deployment in Azure and GCP

It was a fairly straightforward process to create serverless functions in both Azure and GCP

**GCP**
- Start by heading to Cloud Run functions
- Create function
- Trigger type is defaulted to HTTPS
- There are two files: main and requirements
- The main.py had a simple python code that took name as an argument. Upon entering, World! for name and the test ran successfully once deployed.  

**Azure**
- Start by heading to Function App
- Select hosting plan as consumption
- Go through storage, networking, monitoring details and depoloy the app
- This also had the same basic python code that took name parameter and printed Hello World! successfully as well. 

## Serverless Computing

- With automatic scaling based on demand in both Azure and GCP, FaaS eliminates the need for server management.

- You only pay for execution time than traditional VM-based environments.

- Designated for tasks triggered by events like file uploads, HTTP requests, or message queue updates.

- Useful for data processing, microservices, IoT applications, and real-time APIs.

- Did notice that Azure Functions support more languages and both Windows/Linux environments, while GCP Cloud Functions offer better integration with Google’s ecosystem.

- Both GCP and Azure platforms charge based on execution time and offer seamless scaling to handle varying traffic loads.