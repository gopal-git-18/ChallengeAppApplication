# ChallengeApp

A Spring Boot application to manage challenges.

## Features

- ➕ **Add new challenges**  
- 📋 **View all challenges**  
- 📅 **View challenges by month**  
- ✏️ **Update challenges by ID**  
- 🗑️ **Delete challenges by ID**  

## How to Run

1. Clone this repo:
 git clone https://github.com/gopal-git-18/ChallengeAppApplication.git


2. Build the project with Maven:
 
3. Run the app:
  
4. The app will start on [http://localhost:8080](http://localhost:8080)

## API Endpoints

| Method | URL                   | Description            |
|--------|-----------------------|------------------------|
| POST   | `/challenges`         | Create a new challenge  |
| GET    | `/challenges`         | Get all challenges      |
| GET    | `/challenges?month=`  | Get challenges by month |
| PUT    | `/challenges/{id}`    | Update a challenge      |
| DELETE | `/challenges/{id}`    | Delete a challenge      |

## Testing

Test all endpoints using Postman or any REST client.




