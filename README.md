# Google Calendar Clone

This is a web application designed to replicate some functionalities of Google Calendar. Users can sign up, log in, create events, view events for specific dates, update events, delete events, and log out.

## Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js, MongoDB
- Authentication: JSON Web Tokens (JWT)


## Deployed link

- Backend - https://hyperface-rdk3.onrender.com/

## Features

- User authentication (sign up, log in, log out)
- Create, update, view, and delete events
- Recurring events support
- Support for all-day events


## API Endpoints

- POST /users/signup - Register a new user
- POST users/login - Log in a user
- POST /events - Create a new event
- GET events - Get all events
- GET events/date/:date - Get events for a specific date
- GET /events/month/:year/:month - Get events for a specific month
- GET /events/day/:dayOfWeek - Get events for a specific day of the week
- PUT /events/:id - Update an existing event
- DELETE /events/:id - Delete an event by ID


