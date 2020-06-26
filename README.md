## Written submission
Please provide written answers to / explanations on the following topics.

Make a PR with your submission to this repository.

## Product/System features
Please explain the steps you think are necessary to perform to get a feature done, from an idea to an implemented solution that is running in production. Be as detailed as possible.


---> Answer:
First, you need to create a User story. This user story covers the purpose of this feature. 
User story answer the question of : why should i do this and who will affect.
Then, you set some acceptance criterias. This is a detailed approach that helps your implementation step by step.
Once this is done, if you are working in a team, it is important that everyone is on board about the 2 previous steps so it is important to vote on the complexity of the task.
Then you implement it in your code. First by writting a test that will cover the happy path and the sad path, then you implement it in your code.
Once this is done, you can run your feature live (or you can merge it to already existing application if you have one) and if there is no bug to fix and it's running smoothly then you will deploy it.



## Scrum vs Kanban
Please explain the major differences between the named Agile frameworks. Which one did we practice during the bootcamp? Can you see any arguments for using a different framework in a specific project or projects?
answer --->
Kanban is all about visualizing your work, limiting work in progress, and maximizing efficiency(or flow). Kanban teams focus on reducing the time it takes to take a project(or user story) from start to finish. They do this by using a kanban board and continuously improving their flow of work. 


Scrum teams commit to ship working software through set intervals called sprints. Their goal is to create learning loops to quickly gather and integrate customer feedback. Scrum teams adopt specific roles, create special artifacts, and hold regular ceremonies to keep things moving forward. Scrum is best defined in The Scrum Guide.


## Continuous Integration
Explain what continuous integration is and what benefits you can see it brings for teams development workflow. Please refer to your own experience.

Answer--->
Continous integration allows smaller code changes, faster time to resolution and therefore smaller backlog. It facilitates testing reliabity as well. During the bootcamp, we made the mistake of first project to not deploy on a regular basis and it led us to have to deal with a lot of problem for deploying our app closer to the deadline. It increased stress within our team and led us to poor delivery of the project


## Automated tests
What are the various types of testing strategies covered under automated testing? What benefits do each of them bring to the table?

Answer ----> 
On the front end, Cypress is a good tool for feature test. It is easy to use when you start coding(fairly easy for non technical people) and in my opinion a great educative tool. With that type of test you must have a good understanding of the flow of your app, you need to write clear sentence that will test one part of your feature, anticipate wrong behavior from user (sad path). Also, it is a great tool for your client as it is very easy to read and understand.

On the front end you can also have Unit test/ component test. They allow you to test your component in isolation. Your technical skills needs to be sharper and a non techical client will have no understanding of it. It will take time in your development.

On the backend with rails, RSpec is a good tools. It is easy to use and mainly developper friendly as the error messages are very helpul. Also the TDD way is a powerful way to make sure you are building an application correctly, step by step and not ending with a lot of bugs after hours of work.

####