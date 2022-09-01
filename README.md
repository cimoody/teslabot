# teslabot
Model Serving with FourthBrain


## Learning Objective
Deploy a production environment as a serverless application via AWS Lambda

<img title="Setting up deployment" alt="Setting up deployment" src="/images/00_SettingDefaultArguementsFor_sam-deploy.png">

<img title="Initializing deployment" alt="Initiating deployment" src="/images/01_Initiating_Deployment.png">

<img title="Proof of deployment" alt="Proof of deployment" src="/images/02_SentimentFunctionIamRole.png">

## Interview Readiness Questions
What is the definition of a serverless application?
A serverless application is an application that runs on the cloud with infrastructure provided by the cloud service provider. It is for developers to work in a space that does not require an onsite server, does not require backend infrastructure involving computer maintenance or software maintenance, and does not require any work by the developer for scaling the application. It only requires a developer to write their code and deploy it to containers managed by the cloud service provided. Also, according to IBM, “developers never pay for idle capacity” referenced [What is Serverless Computing? | IBM](https://www.ibm.com/cloud/learn/serverless), which is the ideal business usage. It not only saves money on the backend (no need to buy or maintain a server), it is cost efficient when in use.

### What is the definition of model serving and what are the two types?
Model serving is a way to take a machine learning application and make it available to clients via multiple applications. The two types of model serving are batch and online. Batch serving takes in data at specified intervals and produces an updated output (in a format such as a table). Online serving allows an application to use a model live by inputting a request and receiving an output answer in a short time frame referenced [(What is Model Serving | Iguazio](https://www.iguazio.com/glossary/model-serving/).

### What are 3 advantages of deploying using Model Serving methods Vs. deploying on GitHub Pages or HuggingFace for free?
	Using model serving methods provides support with backend infrastructure, scaling, security, monitoring model drift, and  traffic management referenced [(What is Model Serving | Iguazio](https://www.iguazio.com/glossary/model-serving/).

### What Is Machine Learning Inference? 
Machine learning inference is the point at which a machine learning model is made operational and moved into production.

### How Does Machine Learning Inference Work? 
	Machine learning inference uses a fully trained machine learning model, deploys this model into online production and then processes live, unseen data.

### Please walk us through an example?
	An example of model inference is the use of a natural language model that determines the subject of a tweet or request. A trained model in natural language processing would be deployed to an endpoint for user input. Then a user would provide a tweet or request live. The input would be fed back to the model, the model would evaluate the input, and return a prediction for the subject. This would be sent to the user through the deployment application.

