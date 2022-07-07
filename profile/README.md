### What is Plant Coach?
- An application that allows a user to plan and maintain an organic garden through a series of tools based on 3rd-party weather APIs, custom planting advice, plant schedules, and periodic reminders.

## Information about each repository:
  <details>
    <summary> `plant_coach_fe` </summary>

    - Frontend application for the user interface.
    - Built with:
    - Ruby on Rails
    - Bootstrap
  </details>
  
  <details>
    <summary> `plant_coach_be` </summary>

    - Backend application containing most of the application logic
    - Interacts with the microservices
    - Built with:
      - Ruby on Rails
      - PostgreSQL
  </details>

  <details>
    <summary> `plant_coach_weather_api` </summary>

    - Consumes the Open Weather API for weather data.
    - Consumes the Frost Date API to help a user determine when they can plan their garden.
  </details>

  <details>
    <summary> `plant_coach_background_jobs_service` </summary>

    - Schedules background worker jobs and managers the queues for sending users alerts.
  </details>


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
