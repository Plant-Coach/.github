### What is Plant Coach?
- An application that allows a user to plan and maintain an organic garden through a series of tools based on 3rd-party weather APIs, custom planting advice, plant schedules, and periodic reminders.

## What roles do the different repositories play?
- `plant_coach_fe`
  - Frontend application for the user interface.
  - Built with:
    - Ruby on Rails
    - Bootstrap
- `plant_coach_be`
  - Backend application that houses most of the application's logic and databases.
  - Manages the microservices.
  - Main tech stack:
    - Ruby on Rails
    - PostgreSQL
- `plant_coach_weather_api`
  - Consumes the Open Weather API for weather data.
  - Consumes the Frost Date API to help a user determine when they can plan their garden.
- `plant_coach_background_jobs_service`
  - Schedules background worker jobs and managers the queues for sending users alerts.

### Tech Stack
- Ruby on Rails 
- RSpec
- PostgreSQL
- SideKiq
- Redis
- Faraday 

### Testing 
- RSpec
  - Coderay Gem
  - Documentation Formatting
- Capybara
- Shoulda Matchers
