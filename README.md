# Serverless-tutorial
Serverless tutorial for AWS Amazon platform

## Lets talk about the serverless technology

### What is *Serverless*?

In fact, serverless computing simply means that you, the developer, do not have to deal with the server. A serverless computing platform like AWS Lambda allows you to build your code and deploy it without ever needing to configure or manage underlying servers. Your unit of deployment is your code; not the container that hosts the code, or the server that runs the code, but simply the code itself. From a productivity standpoint, there are obvious benefits to offloading the details of where code is stored and how the execution environment is managed. Serverless computing is also priced based on execution metrics, so there is a financial advantage, as well. 

### What is FaaS?

Sometimes serverless computing is called Function as a Service (FaaS), because the granularity of the code that you build is a function. The platform executes your function on its own server and orchestrates the process between function requests and function responses.
Here's the serverless execution model in a nutshell:
1.	A client makes a request to the serverless computing platform to execute a specific function.
2.	The serverless computing platform first checks to see if the function is running on any of its servers. If the function isn't already running, then the platform loads the function from a data store.
3.	The platform then deploys the function to one of its servers, which are preconfigured with an execution environment that can run the function.
4.	It executes the function and captures the result.
5.	It returns the result back to the client.
Theses functions are stateless. That means they are taking input and generate output without cache or memorystack. Each instance of a FaaS is destoyed after usage.

##Architecture

Like (Haines, 2018) said, « The term "nanoservices" is not an industry recognized term, but the idea is simple: each nanoservice should implement a single action or responsibility.”
As you can see in the next pictures, the idea of “nanoservices” represents an smaller entity then microservice. 





**Please read [Presentation de la technologie](https://github.com/team35mazda/Serverless-tutorial/blob/master/Pr%C3%A9sentation%20de%20la%20technologie.pdf) first and then [create your AWS account](https://github.com/team35mazda/Serverless-tutorial/blob/master/Cr%C3%A9ation%20compte%20AWS.pdf).**

Video of the tutorial is available [Here](https://youtu.be/7YXbP4EtYwU)


## Tutorial objective
The objectives of this tutorial is to implement a Stack of AWS amazon plateform ressources to provide a Serverless service with a Rest API. This tutorial is based on GUI for AWS Toolkit in Eclipse for Java.

You will see through this vidéo how to generate a template for a Get / Post API using services like:
- DynamoDB (noSQL database)
- Amazon AWS API
- S3 bucket (object cloud container)
- Lambda (*Function as a service* cloud service)

After this tutorial, you may reuse this *Blueprint* of Java serverless project to build many other one by changing only the java code of the handeler of a function. Usage of POJO for input / output http request help developper stay focus on the function code.

##Creating an AWS account

Follow the instructions from the 



##Bibliography

- Haines, S. (2018, jan 11). Serverless computing with AWS Lambda, part 1. Récupéré sur Javaword: https://www.javaworld.com/article/3210726/serverless-computing-with-aws-lambda.html
- Muens, P. (2016, jun 1). Nanoservices,Microservices,Monolith -- Serverless architectures by example. Récupéré sur medium.com: https://medium.com/@pmuens/nanoservices-microservices-monolith-serverless-architectures-by-example-2e95365a0f6f



