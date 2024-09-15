# Project Showcase

## Overview

Project Showcase is a web application designed to streamline the process of project selection based on various criteria such as department and mentor. It provides an interactive platform for users to explore, search, and engage with projects through features like project search and Q&A functionality.

## Features

- **Project Filtering**: Users can filter projects based on department and mentor.
- **Search Functionality**: Enables users to search for specific projects.
- **Interactive Q&A**: Users can engage in Q&A sessions related to projects.
- **User Authentication**: Secure login and registration system using Firebase.
- **Responsive Design**: Fully responsive interface for seamless use across devices.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Django
- **UI Libraries**: Material UI, React Bootstrap
- **Authentication & Database**: Firebase

## Installation

1. Fork the repository.
2. Clone the repository:
```git clone https://github.com/yourusername/project-showcase.git```
3. Install frontend dependencies:
   ```
   cd frontend
   npm install
   ```
4. Install backend dependencies:
    ```
   cd ../backend
   pip install -r requirements.txt
   ```

5. Set up Firebase:
- Create a Firebase project.
- Add your Firebase configuration to `frontend/src/firebase/config.js`.

6. Run the development servers:
- For frontend:
  ```
  cd frontend
  npm start
  ```
- For backend:
  ```
  cd backend
  python manage.py runserver
  ```

## Usage

1. Register or log in to your account.
2. Browse projects using the filter options or search bar.
3. Click on a project to view details and participate in Q&A.

## Future Enhancements

- Implementation of predictive modeling for personalized project recommendations.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).
