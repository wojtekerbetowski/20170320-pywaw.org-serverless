footer: Wojtek Erbetowski, PyWaw, 20.03.2017 t: @erbetowski www:erbetowski.pl 
theme: Ostrich, 6
[.hide-footer]

# Serverless

## PyWaw, 20.03.2017
Wojtek Erbetowski

---
[.hide-footer]
![fit](https://pbs.twimg.com/profile_images/451185078073171968/T4QKBj-E.jpeg)

---
* FogBugz
* StackOverflow (& SE)
* Trello

---
* FogBugz
* StackOverflow (& SE)
* Trello
* Glitch

---
Serverless?

---
Function as a Service [FaaS]

^ The need
^ the pattern

---
[.hide-footer]
![fit](https://media.licdn.com/mpr/mpr/AAEAAQAAAAAAAAihAAAAJGEwMDA2OTBjLWQwNDItNDdlMS05NjM4LWYxNDY3Y2VlMmMyNA.png)

---
[.hide-footer]
![fit](https://specify.io/assets/serverless-automation-7265d1b1cc7ae92e9559995db6dd680fce120ab97f65a5c70edbd7fa71e41acd.png)

---
[.hide-footer]
![fit](https://media.licdn.com/mpr/mpr/AAEAAQAAAAAAAAc2AAAAJGViZTdjNGY5LTc4ZmEtNGFhMy04OWEzLTAyNmM1OTdjNTgzNw.png)

---
* AWS Lambda
* Google Cloud Functions
* Azure Functions

---
[.hide-footer]
![inline](https://www.dropbox.com/s/718vk0riii3hngn/Screenshot%202017-03-20%2009.21.54.png?dl=1)

---
[.hide-footer]
![inline](https://www.dropbox.com/s/xsin3s8h8ar5jou/Screenshot%202017-03-20%2009.23.49.png?dl=1)

---
Triggers include:
* SNS
* HTTP (API Gateway)
* S3
* DynamoDB
* CodeCommit

---
Hello world:

* 3 services
* ~ 25 steps

---
Great wins?

---
Great wins:

* Scalability
* Pricing
* NoOps

---
Great wins:

* Scalability, but...
* Pricing
* NoOps

---
Great wins:

* Scalability, but...
* Pricing, but...
* NoOps

---
Great wins:

* Scalability, but...
* Pricing, but...
* NoOps, but...

---
Challenges?

---
BaaIDE [Browser as an IDE] :fearful:

---
`.zip` deployment
also via CLI, CD-friendly

---
~~BaaIDE [Browser as an IDE]~~ :relieved:

---
Unit and integration testing :weary:

---
AWS Lambda has a tiny API

```python
def lambda_handler(event, context):
```

---
Tiny, but troublesome...

---
~~Unit and integration testing~~ :confused:

---
Complex domain in tiny app :fearful:

---
Sharing codebase (not a microservice anymore)

---
Extracting scaling parts only

---
~~Complex domain in tiny app~~

---
Steep learning curve

^ AWS is building blocks

---
Higher level frameworks
Serverless, Python-lambda, Zappa

---
Warming up :sleeping:

---
Limits

* how to avoid them?
* should you avoid them?

---
Python 2.7 :fearful:

---
Lack of contenerization

---
Multitenancy

---
and all of the problems of microservices


---
Sources

```
https://martinfowler.com/articles/serverless.html

https://github.com/Miserlou/Zappa
https://serverless.com/

https://aws.amazon.com/lambda/
https://cloud.google.com/functions/
https://azure.microsoft.com/en-us/services/functions/
```

