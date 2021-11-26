# server-less-security
Serverless Security Guides

Protecting Serverless Applications

Effective serverless security focuses on ensuring code integrity, tight permissions and behavioral analysis.

Access and permissions: Maintain least-privileged access for serverless functions and other services. For example, if an AWS Lambda function needs to access a DynamoDB table, make sure it can only perform the specific action the business logic requires.

Vulnerability scanning: Ensure code and infrastructure-as-code template integrity by regularly scanning for vulnerable third-party dependencies, configuration errors, and over-permissive roles.

Runtime protection: Use runtime protection to detect malicious event inputs and anomalous function behavior, and limit as necessary each function’s ability to access files, hosts, the internet and spawn child processes.

SOURCE: https://www.paloaltonetworks.com/cyberpedia/what-is-serverless-security

Organized in order of risk factor, with SAS-1 being the most critical, the list breaks down as the following:

SAS-1: Function Event Data Injection

SAS-2: Broken Authentication

SAS-3: Insecure Serverless Deployment Configuration

SAS-4: Over-Privileged Function Permissions & Roles

SAS-5: Inadequate Function Monitoring and Logging

SAS-6: Insecure Third-Party Dependencies

SAS-7: Insecure Application Secrets Storage

SAS-8: Denial of Service & Financial Resource Exhaustion

SAS-9: Serverless Business Logic Manipulation

SAS-10: Improper Exception Handling and Verbose Error Messages

SAS-11: Obsolete Functions, Cloud Resources and Event Triggers

SAS-12: Cross-Execution Data Persistency

SOURCE: https://cloudsecurityalliance.org/blog/2019/02/11/critical-risks-serverless-applications/
