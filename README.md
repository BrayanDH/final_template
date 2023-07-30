# Online Courses App (Django)

This project is an Online Courses App developed using Django, a popular web framework for Python. The primary objective of this project is to provide users with a platform to access and enroll in online courses.

## Features

- Course Listings: Users can view a list of available online courses.
- Enroll in Courses: Users can enroll in courses they are interested in.
- User Authentication: Secure user authentication to access enrolled courses and manage their account.

## Getting Started

To run the Online Courses App locally, follow these steps:

1. Clone this repository:

   ```
   git clone https://github.com/BrayanDH/online_courses_app_django.git
   ```

2. Navigate to the project directory:

   ```
   cd online_courses_app_django
   ```

3. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Apply database migrations(only the first time):

   ```
   python manage.py migrate
   ```

5. Create a superuser (Admin) to manage the app(only the first time):

   ```
   python manage.py createsuperuser
   ```

6. Start the development server:

   ```
   python manage.py runserver
   ```

7. Open your web browser and visit http://localhost:8000 to access the Online Courses App.

## Dependencies

The Online Courses App utilizes the following dependencies:

- Django
- Django Rest Framework

Please refer to the `requirements.txt` file for the complete list of dependencies and their versions.

**ER Diagram**
For your reference, we have prepared the ER diagram design for the new assesement feature.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)

## Contributing

Contributions to the Online Courses App are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Special thanks to the creators and maintainers of the libraries and frameworks used in this project.

- this project belongs to the Developing Applications with SQL, Databases, and Django course in cursera and is the final test of this course.
