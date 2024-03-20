# microservice_monitoring
Microservice monitoring for Ericsson


microservices, cloud, monitoring


Cloudification and cloud native applications are the main drivers for SW architectures based on microservices. Easy access to big amount of computational power and capacity given by online platform-as-a-service are pushing the explosion of the complexity of those applications.
The simplification in growing applications in term of scalability leads to an increasing need for automated monitoring systems able to collect and present the health status and to notify about unexpected conditions. 


This project assumes to use of a reference microservice framework (SpringBoot) to implement a simple application spawning a few microservices interacting among them. The application must be instrumented (extractors) to be monitored through an external application (Prometheus) in order to collect the relevant metrics and 
to present them on a GUI (Grafana).
The metrics must include the health and status of the services, dedicated performance KPI, and the capability to perform message tracing exchanged across the services showing the topological relationship among them. 


## Linux, SpringBoot, Java, Prometheus, Grafana , Zipkin


What did we do?
At first we installed Docker Framwork and then we ran Prometheus and Grafana tools on it. these two show us the status of metrics that mentioned above. After that we want to start coding on Eclipse IDE. 
