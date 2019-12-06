---
title: "Learning"
date: 2019-12-05T21:51:56+02:00
draft: false
tags: ["markdown", "DevOps", "blog", "learning"]
---
## learning 086
During this course, I have learned many new concepts and have come to understand concepts I knew beforehand more in-depth.

The first things I learned are the **_three ways_**, the goals of DevOps: 
* **Systems Thinking**: Moving the product through the system as quickly as possible from one end to the other (cf. factory production line). Global optimizations of flow through the system are prioritized over local ones. 
* **Feedback Loops**: Shortening and amplifying feedback loops. Any feedback (e.g. measuring throughput of work in the system) should be processed and signalled efficiently from the end to the beginning of the system, in order to improve and optimize system flow. 
* **Culture of Experimentation**: Continual experimentation and learning from failure. Experimenting with SW and infrastructure allows us to learn from any mistakes made on each iteration and to master our craft through repetition, perhaps even breaking new ground on the way.  

Next, I learned about the **_CAMS model_**, which represents the core approaches of DevOps: 
* **Culture**: Adopting a business culture that aims to improve various aspects of the business. DevOps SW development life-cycles, technical debt grooming, destructive testing, hack events and cross-functional teams (e.g. via Scrum) are all part of the culture aspect of CAMS. (cf. Culture of Experimentation)
* **Automation**: Automating parts of the system flow for efficiency and better quality. Configuration management focuses on the establishing and maintaining consistency of product performance and functional/physical attributes, and continuous delivery aims for building, testing and releasing SW at greater speed and frequency. (cf. Systems Thinking)
* **Measurement**: Measuring system flow in various ways allows for keeping benchmarks, based on which the business tries to optimize and improve its system. (cf. Feedback Loops)  
* **Sharing**: Visibility, transparency and knowledge transfer are key components of sharing within a business. Everyone should be able to see what the current progress is in different parts of the organization, how the progress has been made and the processes involved to make that progress.  

Finally, I learned various things by doing this **_advanced project_**:
* **Continuous Integration/Delivery**: I have used Jenkins before at work, but it was very educational to configure everything myself via Travis CI. The project showed me that it can be very simple to utilize CI/CD in my hobby projects if I wish to do so and will help a great deal in automating the menial tasks, such as testing and deployment.
* **Markdown**: A simple, lightweight markup language that could be very useful in documentation or writing blogs, for example.
* **Combining Technologies**: Combining Hugo, GitHub Pages, Travis CI and various file formats to create website through CI/CD was very fun!
* **Google is Your Friend**: Whenever I came across a problem, Google came to my help. Just about any question already has an existing answer. The most challenging part of the project was probably setting up the .travis.yml file, but after consulting a few articles I was able to do it without problems.