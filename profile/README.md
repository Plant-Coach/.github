### What is Plant Coach?
- An application that allows a user to plan and maintain an organic garden through a series of tools based on 3rd-party weather APIs, custom planting advice, plant schedules, and periodic reminders.

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
