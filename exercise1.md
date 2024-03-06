The application is coded in Ruby programming language.

1/ 
Linting: 
    RuboCop (Ruby code style checker and formatter)
    Reek (tool that examines Ruby classes, modules and methods)
Testing: 
    RSpec (testing tool that allow to write automated test suite)Capybara (help test web application by simulating how user interact with app)
    Cucumber (tool for running automated tests written in plain language)
Building: 
    Rake (build automation tool)
    Capistrano (remote server automation and deployment tool)

2/ Some alternatives to set up the CI are Travis CI, CircleCI, GitLab CI/CD, Bitbucket Pipelines, TeamCity, AWS CodePipeline, Drone.

3/ In my opinion, the setup for this Ruby application would be better in a cloud-based environment. In the context of a team working in Ruby application project, I think that team of 6 people is considered a small team. With cloud-based solution, it comes with easier setup and simpler configuration, cost-effectiveness and offer built-in support for Ruby programming language. Also some software maintenance tasks such as software updates, patching and infrastructure management, ... are handled by the cloud-based platform. So when choosing cloud-based solution the developers can focus on application developement and feature than assigning another team member to configure and setup the CI/CD.
