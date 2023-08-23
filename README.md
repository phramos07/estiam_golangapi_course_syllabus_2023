## Golang API - Building a web backend in Golang (@ Estiam)

Welcome to the Golang API course. 

### Before we start

Please answer this quick form so I can get to know you better. This will help us throughout the course.

https://forms.gle/f2CMsQtpdvNAapTz9

### Goals

At the end of this course, you'll be able to understand the basics of the Go language, as well as writing a backend server in Golang using go frameworks and libraries. 

The main objective of this course is to learn GOLANG, a static typed imperative multi-purpose language focused on solving problems fastly and efficiently. 

### Final Project and assessment

❗ UPDATE (23/08/2023): There will be two assessments in the course.

1. 40 Multiple-choice test

Students will undergo a 40 question-test on Thursday (24/08/2023) during the afternoon turn that covers the basics of the language and API development.

2. Project assignment

The project will cover all the topics we will learn throughout the course. It asks you to develop a web-backend in Golang. It is a simple CRUD, integrated with PostgreSQL. All detais on the final assessment should be found here:

:warning:	[LINK PROJECT ASSIGNMENT](https://github.com/phramos07/estiam_golang_api_course_finalproject) :warning:	

### The instructor

I will be the instructor carrying out the course. My name is Pedro Ramos, I am a software engineer from Brazil. I hold a bachelor and a master's degrees in Computer Science. Although I am a generalist developer, I am focused on backend and low-level coding, and I have been working with golang in the past 4 years or so.

Please reach me out if there are any doubts during the course, I'll be fully available for students.

> Email: pedro.ramos@estiam.com

> Linkedin: https://www.linkedin.com/in/phramos07/

### Course Syllabus

This course will take 4 days. We understand that it is a short time to learn a new language plus some backend frameworks. We will focus on getting to know the basics of the language and some advanced concepts, as well as how to develop a simple but complete web backend in Golang.

#### Day 1 (21/08/2023)

We will try to cover the basics of the language on day 1. We will do it by solving some problems together.

❗ **[All problems for day 1 are available in here](https://github.com/phramos07/estiam_golang_api_course_day1)**

* What is a computer. How memory works as pairs of addresses and values.
* Getting to know the language. Package concept. Basic "fmt" package.
* Variables and types. Slices, arrays, maps. Standard I/O
* Conditionals. If/else, dynamic switch.
* Loops
* Functions
* Manipulating files.
* Manipulating strings.
* Basic error handling in go. Difference between Panic and returning an error.
* Abstract types (structs) and methods. Receiver concept. Pointers and references.

#### Day 2 (22/08/2023)

On day 2, we will start tackling the final project. We will start by HTTP basics.

* Interface oriented programming. Pointers and references.
* Web-development. How the HTTP protocol works. RESTFul concept. Error handling in REST (status codes).
* Implementing HTTP endpoints (CRUD)
* Adding a database to our backend. PostgreSQL. Adding tables and ORM (*)

#### Day 3 (23/08/2023)

* Middlewares. Adding logging middleware and error middleware.
* Adding a security layer to our backend. Login endpoint and auth middleware.

#### Day 4 (24/08/2023)

* Concurrency: goroutines and gochannels.
* Final project development time.

(*) Some of this topics may change due to priorization and time constraints.

### What won't be taught here

4 days is a very constrained time to cover some of the topics that are left out from this course. These are the topics that we won't be covering in live classes, but students are encouraged to implement these features on their final project assignment.

* docker and docker-compose for local development. We will be using containers, but we're not gonna focus on best practices on deployment, CICD pipelines, and devops tools such as Grafana, Datadog, Rancher, terraform.
* microservices. Splitting the backend into minor services. Splitting API from database writer service. Use of tools such as Kafka or RabbitMQ
* git

### What you actually need to follow the course

In order to follow this course, the student will need

1. Golang installed on version 1.19 or higher

>Instructions: https://go.dev/doc/install

2. A code-editor or a IDE. We recommend the use of VSCode (free), but GoLand (paid) is also available for a student subscription.

> VSCode: https://code.visualstudio.com/download

> GoLand: https://www.jetbrains.com/go/download/

3. We might need docker installed for our DB to work

> Docker: https://docs.docker.com/engine/install/

_For windows users, you might need to allow for virtualization in your BIOS in order for docker to work_

4. A Github account. The project will be delivered as a **pull request**. 

> git basics: https://www.atlassian.com/git

### Course material

We'll be doing mostly live-coding and solving exercises. Here are our references for the course:

1. Golang docs: https://go.dev/doc/
2. What is considered to be the Golang bible, The Go Programming Language - Alan A. A. Donovan, Brian W. Kernighan: [Download](http://www.cs.uniroma2.it/upload/2017/TSC/The%20Go%20Programming%20Language.pdf) (7mb)
3. [Echo framework](https://echo.labstack.com/) for the http client
4. [JWT-go](https://pkg.go.dev/github.com/golang-jwt/jwt/v4) for authorization middleware

_Slide presentations and excalidraw presentations will be shared during the course here in this repository_

### Final words

I hope this short experience is enough for you to know more about the Go language and allows you to go deeper into the world of the backend development using go as a powerful tool. Don't rush, don't focus on knowing it all, just give it your best and what you are capable of. I understand programming is not an easy feat. Don't panic! Everything will be just fine. 

Please reach me at my email (described at the top of this readme file) at any time of the day.
