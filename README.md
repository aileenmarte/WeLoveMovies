# WeLoveMovies

## Description
WeLoveMovies is a backend API application designed to manage and retrieve information about movies, theaters, and reviews. This project focuses on providing a robust API for movie-related data, allowing users to interact with various endpoints for creating, reading, updating, and deleting information.

## Features
- Manage movies, theaters, and reviews
- Retrieve movie details, including related theaters and reviews
- Update and delete movie reviews
- Comprehensive API documentation

## Technologies Used
- Node.js
- Express
- Knex.js
- PostgreSQL

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/aileenmarte/WeLoveMovies.git

2. Navigate to the project directory:
    cd WeLoveMovies

3. Install the dependencies:
    npm install

## Database Setup
1. Create a PostgreSQL database and update the knexfile.js with your database credentials.

2. Run the migrations:
    npx knex migrate:latest
3. Seed the database:
    npx knex seed:run

## Usage
1. Start the development server:
    npm start
2. The API will be available at 'http://localhost:5000'.

## API Endpoints
- GET /movies: Retrieve a list of movies
- GET /movies/:movieId: Retrieve details of a specific movie
- GET /theaters: Retrieve a list of theaters
- GET /reviews: Retrieve a list of reviews
- POST /reviews: Create a new review
- PUT /reviews/:reviewId: Update a specific review
- DELETE /reviews/:reviewId: Delete a specific review

## Contributing
1. Fork the repository.

2. Create a new branch:
    git checkout -b feature-name

3. Make your changes and commit them:
    git commit -m 'Add feature'

4. Push to the branch:
    git push origin feature-name

5. Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or suggestions, please contact Aileen Marte.

Feel free to modify it further to better fit the specific details and requirements of your project.
