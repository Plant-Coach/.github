## What is Plant Coach?
- Plant Coach allows a user to plan and organize a vegetable garden through a series of tools based on 3rd-party weather APIs, custom planting logic, plant schedules, and periodic reminders.
- Plant Coach is is a distributed application, deployed on a Kubernetes cluster which is created and managed through my own automation in Terraform modules, Helm Charts and GitHub Actions/Pipelines.
- While I sought to make Plant Coach a remarkable organization tool for gardeners such as myself, it is also a playground for me to explore and learn what it takes to create a thoughtful experience for the end-user as well as for other developers who may work on it.

- Plant Coach's code repos are divided into 2 categories: *application* and *infrastructure*.
### Application
  - [Plant Coach Backend](https://github.com/Plant-Coach/plant_coach_be) - *Ruby on Rails*
  - [Plant Coach Frontend](https://github.com/Plant-Coach/plant_coach_fe) - *Ruby on Rails*
  - [Plant Coach Weather API](https://github.com/Plant-Coach/plant_coach_weather_api) - *Ruby on Rails*
### Infrastructure
  - [Plant Coach Helm](https://github.com/Plant-Coach/plant-coach-helm) - *Helm Chart*
  - [Nginx Ingress Maintainer](https://github.com/Plant-Coach/nginx-ingress-maintainer) - *Helm Chart*
  - [DOKS Manager (DigitalOcean Kubernetes Manager)](https://github.com/Plant-Coach/doks_manager) - *Terraform Module*

### Upcoming Technical Priorities
  - [x] Containerize backend service.
  - [x] Move backend repo from Heroku to Kubernetes.
  - [x] Containerize frontend service.
  - [x] Move frontend repo from Heroku to Kubernetes.
  - [x] Containerize frontend service.
  - [x] Move weather API service from Heroku to Kubernetes.
  - [x] Resume normal Rails development after app is deployed again.
  - [x] Automate helm publishing
  - [ ] Create testing environment in separate K8s cluster.
  
  
### Built With:
<img src="https://img.shields.io/badge/-Ruby%20on%20Rails-CC0000?logo=ruby%20on%20rails&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Postgresql-4169E1?logo=postgresql&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-CircleCI-8669AE?logo=circleci&logoColor=white&style=for-the-badge"/>

<img src="https://img.shields.io/badge/-Sidekiq-FF6A00?logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Redis-DC382D?logo=redis&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Heroku-430098?logo=heroku&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Postman-FF6C37?logo=postman&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Faraday-CC0000?&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Figaro-CC0000?&style=for-the-badge"/>

### Tested with:
<img src="https://img.shields.io/badge/-RSpec-CC0000?&style=for-the-badge"/> <img src="https://img.shields.io/badge/-SimpleCov-CC0000?&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Shoulda%20Matchers-CC0000?&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Capybara-CC0000?&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Factorybot-CC0000?&style=for-the-badge"/> 


---


Thank you for visiting!  Please feel free to visit my repos to see how my code works so far or to offer a code review. 🤓
