# Overtime App

## Key requirement: Company needs documentation that salaried employees did or did not get overtime each week

## Models

- Post -> date:date rationale:text
  x User -> Devise
- AdminUser -> Single Table Inheritance (STI)

## Features

- Approval Workflow
- SMS Sending (Twilio) -> Link to approval or overtime input
- Administrate admin dashboard
- Email summary to managers for approval
- Needs to be documented if employee (user) did not log overtime

## UI

- Bootstrap -> formatting

## Testing

- RSpec
- Capybara -> Integration Tests
