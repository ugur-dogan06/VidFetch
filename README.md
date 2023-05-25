# VideoFetch

VideoFetch is a web application that allows users to download YouTube videos. It is built using React, Django, Bootstrap, MySQL, and MongoDB.

## Features

- Fetches and downloads YouTube videos in various formats and quality options.
- User-friendly interface with a responsive design powered by Bootstrap.
- Supports storing downloaded video metadata and user preferences in MySQL and MongoDB databases.
- Easy setup and deployment using Docker.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- Django: A high-level Python web framework for backend development.
- Bootstrap: A popular CSS framework for responsive web design.
- MySQL: A relational database management system for storing video metadata and user preferences.
- MongoDB: A NoSQL document database for flexible data storage.

## Installation

1. Clone the repository:

`git clone https://github.com/your-username/videofetch.git`

2. Install the required dependencies for the frontend and backend:

#### Frontend (React)
`cd vidfetch/frontend`
`npm install`
#### Backend (Django)
`cd ../backend`
`pip install -r requirements.txt`

3. Configure the databases:

- MySQL:
  - Create a new MySQL database and update the database credentials in `backend/settings.py`.

- MongoDB:
  - Install and run MongoDB.
  - Update the MongoDB connection details in `backend/settings.py`.

4. Build and run the application:

#### Frontend (React)
`cd videofetch/frontend`
`npm run build`

#### Backend (Django)
`cd ../backend`
`python manage.py migrate`
`python manage.py runserver`


5. Access the application in your browser at `http://localhost:8000`.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, please submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).