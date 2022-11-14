# Operationalizing Machine Learning

In this project, I will be working on with the Bank Marketing dataset, which contains data about the personal and financial details of customers in a Portugese bank, and the objective is to predict if the customer will subscribe to an advanced offering. I will use Microsoft Azure to configure a cloud-based machine learning production model, deploy it, and consume it. Afterwards, I will create, publish, and consume a pipeline.

## Architectural Diagram
In this section, I will provide an architectual diagram of the project and give an introduction of each step. An architectural diagram is an image that helps visualize the flow of operations from start to finish.

![alt text](rainelimages/ArchitecturalDiagram.png?raw=true)

## Key Steps
Registered Dataset\
![alt text](rainelimages/dataset.jpg?raw=true)

Experiment Completed\
![alt text](rainelimages/experimentoconcluido.jpg?raw=true)

Best Performing Model\
![alt text](rainelimages/bestmodel.jpg?raw=true)

Deploying the Best Model with Authentication\
![alt text](rainelimages/deploy.jpg?raw=true)

Application Insights Enabled\
![alt text](rainelimages/appinstrue.jpg?raw=true)

Logs by logs.py Script\
![alt text](rainelimages/logs.jpg?raw=true)

Swagger Documentation with API Contents\
![alt text](rainelimages/swagger1.jpg?raw=true)

![alt text](rainelimages/swagger2.jpg?raw=true)

![alt text](rainelimages/swagger3.jpg?raw=true)

![alt text](rainelimages/swagger4.jpg?raw=true)

![alt text](rainelimages/swagger5.jpg?raw=true)

![alt text](rainelimages/swagger6.jpg?raw=true)

Model Consumption and JSON output\
![alt text](rainelimages/endpointpy.jpg?raw=true)

![alt text](rainelimages/json.jpg?raw=true)

Benchmarking\
![alt text](rainelimages/apachebenchmark1.jpg?raw=true)

![alt text](rainelimages/apachebenchmark2.jpg?raw=true)

Pipeline Created\
![alt text](rainelimages/pipelinecriadoeendpoint.jpg?raw=true)

Pipeline Endpoint\
![alt text](rainelimages/endpoint.jpg?raw=true)

Bankmarketing Dataset with AutoML Module\
![alt text](rainelimages/datasetandautoml.jpg?raw=true)

Published Pipeline Overview\
![alt text](rainelimages/pipelinerestactive.jpg?raw=true)

Jupyter Notebook\
![alt text](rainelimages/runcomplete.jpg?raw=true)

ML Studio with Scheduled Run\
![alt text](rainelimages/restendpoint.jpg?raw=true)


## Screen Recording
[Link to Screen Recording](https://www.youtube.com/watch?v=KMW5_XrTePU/view?usp=sharing?usp=sharing)

## Standout Suggestions to improve my model
1.1 - Clean the data as this dataset contains outliers which may influence the accuracy of our predictions. When I am not using AutoML, I can manually pick out features that are most important to our prediction. I can consider using a library such as Boruta, which is a feature selection wrapper algorithm that works well with classification problem, to identify weak and/or irrelevant features that can be discarded.
1.2 - Supplement with techniques like k-fold cross-validation to improve my model accuracy.

2 - In Azure, I can leverage batch inference pipeline capabilities. By including a ParallelRunStep to my pipeline via the Azure SDK, I can distribute the workload tasks into mini-batches, which should help to reduce the processing time. This will allow me to perform operations and review results more quickly.
