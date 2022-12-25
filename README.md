# Django Polls App (with some of my thoughts)

## Why make a git repo for a tutorial that has already been done countless times?

In my learning and work as a full-stack software engineer, I have to evaluate the best options to implement features and solve technical problems that different frameworks offer. Lately, I have taken a liking to opinionated frameworks like Django because I'm curious about their "batteries included" approach vs. installing and configuring packages like I would usually do for a MERN-Stack App. Django comes built-in with solutions for implementing core functionalities for applications like Authentication/Authorization and an ORM for SQL databases. Using these tools from Django, I could create a simple full-CRUD web application very very quickly.

However, as convenient as Django's included features are for quickly implementing a feature or even reaching MVP, there are tradeoffs that can quickly make building with Django feel bloated and clunky. For example, for defining core functionalities of a web application like routing paths or models, Django typically uses a single file where all instances of that functionality are defined. With routing, all routes for a Django app are typically defined in a `urls.py` file. Additionally Django routes do not follow RESTful route nomenclature, but instead point to different view functions that carry out DB interactions that would be considered "controller actions" in MVC. Coming from a mostly Express.js background, this was a major hurdle to overcome. Django's ORM also was a double-edged sword. Defining models as classes was mostly intuitive, but using automatically generated methods on model objects was not. I would frequently have to refresh myself on how query sets worked and which model in a relationship would actually call the method. Like most other frameworks, reading documentation can provide a more in-depth explanation than a quick tutorial would be able to offer. Luckily, Django's docs are very thorough.

## Main Takeaways

- to be written out

## Additional Notes:

This will be the first of a series I will continue to write througout the next year about how different frameworks introduce themselves with their "Getting Started" tutorials. I enjoy learning about different approaches to building web applications, and I think it would be helpful for me to reflect on my own understanding of what I have learned by evaluating different frameworks in my own development toolkit.
