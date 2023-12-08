# Anode

A solution to Open D/I Hackathon Challenge 3.

## Target of Challenge 3

Build a web application that:

- pull (binary) data from custom APIs
- store them in database
- and send them to both RESTful APIs and WebSockets

This web application should be:

- decentralized
- highly scalable
- high-performance

Things to be remembered:

- **Build a prototype (or a demo) rather than a product.** Focus on software design and software architecture rather than detailed functionalities.
- **Use the pull strategy.** The custom API only supports the pull strategy (not push, but push supports can be added for future development).

## **Technical Requirements (from Google Docs)**

- Develop a solution that is able to receive data from multiple sources. It should be scalable to over 100 sources.
- The solution should process this data in real time. It should be saved to a database and transmitted to all listeners of a WebSocket.
- A frontend should be present that gives insight into the current status of all components of your solution.
- The solution should be able to support both REST API and WebSocket sources.
- It should be easy to automatically deploy the solution. A containerized application (using for example docker) could be used or a setup script to handle installation could be provided.

## Resources (from DevPost)

- Streaming: [https://aws.amazon.com/streaming-data/](https://aws.amazon.com/streaming-data/)
  - Content: Concepts and Amazon solutions of data streaming.
- ETL: [https://www.ibm.com/topics/etl](https://www.ibm.com/topics/etl)
  - Content: Concepts and tools for ETL (a data integration process)
- Scaling and Scalability: [https://www.redswitches.com/blog/server-scaling/](https://www.redswitches.com/blog/server-scaling/)
  - Content: Concepts of scaling

Other resources are mostly useless and can be ignored.