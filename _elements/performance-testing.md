---
name: Performance Testing
description: 
  - Performance tests can be defined as individual tests using collections, pulling from one or many individual API paths and measuring the time it takes for the response to be sent, providing a test that can be run manually, scheduled across multiple geographic regions, or executed as part of a CI/CD pipeline, helping ensure an API is always meeting it's expected performance benchmarks.
links:
    - title: Link Title
      url: http://example.com
    - title: Link Title
      url: http://example.com
    - title: Link Title
      url: http://example.com            
video: ''
screenshots:
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png          
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png  
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png   
...
Performance testing establishes a benchmark for what can be expected when it comes to the response time for each API. The OpenAPI for each API can be used to generate collections that provide 100% coverage for all of the API paths present, or performance tests can be applied to just a subset of API paths. It makes sense to have performance test collections separate from other types of testing so that they can be run independently from contract, integration, or other types of tests. Helping establish that the performance levels are met from potentially different regions that reflect actual application usage of APIs. Providing a comprehensive look at the performance of an API from across multiple regions for 100%, or a sensible sampling of API paths, ensuring that APIs and the teams behind them are meeting their SLAs over time and across the entire API lifecycle.
