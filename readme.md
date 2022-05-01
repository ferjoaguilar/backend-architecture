<p align="center">
  <a href="https://platzi.com/cursos/next-2020/" target="_blank">
    <img alt="Utec-meeting" src="https://res.cloudinary.com/dohkdu219/image/upload/v1651360417/backend-architecture/backend_ctnjwr.png" width="85" />
  </a>
</p>
<h1 align="center">
  Backend architecture
</h1>
<p align="center">Created by Fernando Jose Aguilar Rivas</p>


# Introduction

Backend architecture show a resolution problem using Golang, PostgreSQL and MongoDB databases. However, implementations diagrams, problems and posible solutions.

# Index

1. Objetives [go now](#objectives)
2. Client Requirement [go now](#client_requirement)
3. Definitions and Acronyms [go now](#definitions-and-acronyms)
4. Supported use-cases [go now](#supported-use-cases)
5. Out of scope [go now](#out-of-scope)
6. Architecture [go now](#architecture)
7. Limitations [go now](#limitations)
8. Cost [go now](#costs)

# Objectives

Learn to development backend architecture and define "business requirements" to implementation itself.

# Client Requirements
The #RandomCameraReviews need a backend systems to management camera reviews (search cameras states and buy cameras in website) to differents parts of the word. 

The company has developer teams programmers in Frontend's developer will to create a professional website to use we backend systems. The api system need to show the next features.

* Upload cameras reviews
* Get the content to reviews in website and posible mobile application.
* Drive users to editor cameras reviews.

**IMPORTANT** : The company #RandomCameraReviews plans to expand the South America is the bigger market, also sells in Noth America and little sells in Asian.

# Definitions and Acronyms

**Note: The definitions and acronyms is using to backend developers to #RandomCameraReviews.**

* API: Application program interface.
* MongoDB: No-SQL database.
* PostgreSQL: SQL database.
* AWS: Amazon Web Services.
* Kubernetes: Open source platform for managing containerized workloads and services.
* S3: Amazon S3 storage service.

# Supported use-cases

* Backend systems running around the world.
* Multiples user connected.
* Supports to differents users categories.
* API's always avaliables.

# Out of scope

* Error handling
* Automation of setup for adding support of cities.
* Notifications on areas that are not located in the world.
* Notifications messages specific to an individual "station" within a city.

# Architecture

## Diagrams

![GENERAL DIAGRAM](https://res.cloudinary.com/dohkdu219/image/upload/v1651366661/backend-architecture/general_qsl51a.jpg "GENERAL DIAGRAM")

## Data models

![RELATIONSHIP ENTITY](https://res.cloudinary.com/dohkdu219/image/upload/v1651368794/backend-architecture/database_lpnx20.jpg "RELATIONSHIP ENTITY")

# Limitations

* In South America minimum 500ms latency to request http petition.
* In South America minimum 500ms latency to response http petition.
* General API to word North America, Europa and Asian minimum latency 600ms to request and response.

# Costs


| SERVICE | DETAILS  | AMOUNT  | UNIT COST  |  TOTAL  |
| ------- | ------- | ------- | ------- |------- |
| Amazon Lightsail | [[show details]][1]  | 2 | $160/month | $320/month |
| Amazon Lightsail | [[show details]][1]  | 3 | $80/month | $240/month |
| Amazon S3 | [[show details]][2]  | 1 | NaN | NaN |
|  |  |  | **TOTAL** | $560/month |


[1]: https://aws.amazon.com/es/lightsail/pricing/ "Amazon Lightsail"
[2]: https://aws.amazon.com/es/s3/?nc=sn&loc=0 "Amazon S3"


