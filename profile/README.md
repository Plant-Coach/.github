### What is Plant Coach?
- An application that allows a user to plan and maintain an organic garden through a series of tools based on 3rd-party weather APIs, custom planting advice, plant schedules, and periodic reminders.

### Built With:
<img src="https://img.shields.io/badge/-Ruby%20on%20Rails-CC0000?logo=ruby%20on%20rails&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Postgresql-4169E1?logo=postgresql&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-CircleCI-8669AE?logo=circleci&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Bootstrap-7952B3?logo=bootstrap&logoColor=white&style=for-the-badge"/>

<img src="https://img.shields.io/badge/-Sidekiq-FF6A00?logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Redis-DC382D?logo=redis&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Heroku-430098?logo=heroku&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Postman-FF6C37?logo=postman&logoColor=white&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Faraday-CC0000?&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Figaro-CC0000?&style=for-the-badge"/>

### Tested with:
<img src="https://img.shields.io/badge/-RSpec-CC0000?&style=for-the-badge"/> <img src="https://img.shields.io/badge/-SimpleCov-CC0000?&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Shoulda%20Matchers-CC0000?&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Capybara-CC0000?&style=for-the-badge"/> <img src="https://img.shields.io/badge/-Factorybot-CC0000?&style=for-the-badge"/> 


## Information about each repository:
  <details>
    <summary> `plant_coach_fe` </summary>
    
    - Main tech: 
      - Rails
      - Bootstrap
    - Frontend application for the user interface.
  </details>
  
  <details>
    <summary> `plant_coach_be` </summary>
    
    - Main tech:
      - Rails
      - PostgreSQL
      - Faraday
      - Figaro
      - Circle CI
      - REST APIs
      - Heroku
      - JWT
    - Backend application containing most of the application logic
    - Manages the microservices
  </details>

  <details>
    <summary> `plant_coach_weather_api` </summary>
    
    - Main tech:
      - Rails
      - RSpec
    - Consumes the Open Weather API for weather data.
    - Consumes the Frost Date API to help a user determine when they can plan their garden.
  </details>

  <details>
    <summary> `plant_coach_background_jobs_service` </summary>
    
    - Main tech stack:
      - Rails
      - RSpec
      - Sidekiq
      - Redis
    - Schedules background worker jobs and managers the queues for sending users alerts.
  </details>


### Want to see my tests pass with RSpec?
1. run `git clone <repo_of_your_choice>`.
2. `cd <repo_name>` into the repo's directory.
3. run `bundle install`
4. run `bundle exec rspec`
