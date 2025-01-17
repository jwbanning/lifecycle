---
name: CI/CD Pipeline
description: 
  - Like other aspects of the software development lifecycle, APIs benefit from well defined, repeatable CI/CD pipelines to deploy, test, automate, and orchestrate throughout the API lifecycle, publishing APIs to development, staging, production, and other stages, but then also ensuring other elements like publishing of documentation, and tests are baked into the process. 
links:
    - title: Continuous Integration (CI) with Postman API
      url: https://learning.postman.com/docs/running-collections/using-newman-cli/continuous-integration/
    - title: Running collections on the command line with Newman
      url: https://learning.postman.com/docs/running-collections/using-newman-cli/command-line-integration-with-newman/         
video: ''
screenshots:
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png          
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png  
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png   
...
CI/CD pipelines are an essential part of automating the delivery of APIs, and there are multiple ways they can be used in conjunction with the Postman platform from deployment, to testing and governance. Postman collections are executable units that can be run individually and sequentially as part of a CI/CD pipeline, publishing documentation, running contract, integration, and performance tests, or leverage infrastructure APIs behind our APIs to automate any part of the API lifecycle. Jenkins, Github Actions, and other CI/CD solutions allow for the execution of manually created or dynamically generated Postman collections, providing an excellent mechanism for standardizing how API lifecycle automation occurs across many different APIs, while also utilizing a standardized approach to moving APIs forward as part of an agreed upon API lifecycle.
