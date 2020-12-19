# SentimentAnalysisWebAPI

![predict from command line](https://github.com/ulfsv/SentimentAnalysisWebAPI/blob/master/predict.png)
### Deploy a model in an ASP.NET Core Web API
I have deployed a pre-trained ML.NET machine learning model on the web using an ASP.NET Core Web API. 
Serving a model over a web API enables predictions via standard HTTP methods.

Prerequisites

    Visual Studio 2019 or later or Visual Studio 2017 version 15.6 or later with the ".NET Core cross-platform development" workload installed.
    PowerShell.
    Pre-trained model. Use the ML.NET Sentiment Analysis tutorial to build your own model or download this pre-trained sentiment analysis machine learning model

# Showing the swagger API documentation with Swashbuckle
![predict from command line](https://github.com/ulfsv/SentimentAnalysisWebAPI/blob/master/2020-12-17swagger.png)

There are three main components to Swashbuckle:

    Swashbuckle.AspNetCore.Swagger: a Swagger object model and middleware to expose SwaggerDocument objects as JSON endpoints.

    Swashbuckle.AspNetCore.SwaggerGen: a Swagger generator that builds SwaggerDocument objects directly from your routes, controllers, and models. It's typically combined with the Swagger endpoint middleware to automatically expose Swagger JSON.

    Swashbuckle.AspNetCore.SwaggerUI: an embedded version of the Swagger UI tool. It interprets Swagger JSON to build a rich, customizable experience for describing the web API functionality. It includes built-in test harnesses for the public methods.


