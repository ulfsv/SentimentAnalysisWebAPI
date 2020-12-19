# SentimentAnalysisWebAPI

![predict from command line](https://github.com/ulfsv/SentimentAnalysisWebAPI/blob/master/predict.png)
### Deploy a model in an ASP.NET Core Web API
I have deployed a pre-trained ML.NET machine learning model on the web using an ASP.NET Core Web API. 
Serving a model over a web API enables predictions via standard HTTP methods.

Prerequisites

Visual Studio 2019 or later or Visual Studio 2017 version 15.6 or later with the ".NET Core cross-platform development" workload installed.
PowerShell.
Pre-trained model. Use the ML.NET Sentiment Analysis tutorial to build your own model or download this pre-trained sentiment analysis machine learning model.

# How the data was prepared

A pretrained model was used based on UCI Sentiment Labeled Sentences dataset. The hyperparameter training values and accuracy on the test set are unknown. The quality of the data and correct classification in to negative and positive classification are th most important part of getting a model with good accuracy.
The training data looks similar to this:
SentimentText 	                            Sentiment (Label)
Waitress was a little slow in service. 	     0
Crust is not good. 	                         0
Wow... Loved this place.                     1
Service was very prompt.                  	 1

# Showing the swagger API documentation with Swashbuckle
![predict from command line](https://github.com/ulfsv/SentimentAnalysisWebAPI/blob/master/swaggeer_doc.png)

There are three main components to Swashbuckle:

Swashbuckle.AspNetCore.Swagger: a Swagger object model and middleware to expose SwaggerDocument objects as JSON endpoints.

Swashbuckle.AspNetCore.SwaggerGen: a Swagger generator that builds SwaggerDocument objects directly from your routes, controllers, and models. It's typically combined with the Swagger endpoint middleware to automatically expose Swagger JSON.

Swashbuckle.AspNetCore.SwaggerUI: an embedded version of the Swagger UI tool. It interprets Swagger JSON to build a rich, customizable experience for describing the web API functionality. It includes built-in test harnesses for the public methods.


