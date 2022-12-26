Hello everyone! Welcome to the project I'm most proud of; the creation of my manual CI tool.

This is of-course written in Python, using the Flask web-framework. This uses quite a bit of modules and libraries, but at the end of the day, it mostly relies on built-in modules such as 'os', 'sys' and 'requests'. 

Essentially, using Flask's RESTAPI capabilities, I defined an API call to a GitHub Webhook using jSON format. From there on out, it examines the branches, executing the traditional CI Stages (Build, Containerize, Run Tests and move to a Staging environment) based on the branch name.

I hope you guys enjoy reading it!