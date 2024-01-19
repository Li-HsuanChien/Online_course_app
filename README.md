<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

# Online Course app

### Built With

* [![Django][Django]][Django-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Overview

[![Product Name Screen Shot One][product-screenshot-one]](https://github.com/Li-HsuanChien/Online_course_app)

[![Product Name Screen Shot Two][product-screenshot-two]](https://github.com/Li-HsuanChien/Online_course_app)

[![Product Name Screen Shot Three][product-screenshot-three]](https://github.com/Li-HsuanChien/Online_course_app)

A Django-based Learning Management System that simulates the online learning experience. Key features are registering users, instructors, students, courses, course lectures, functional online quizes, with django admin.Users are allowed to enroll courses, inspect them and take quizes on site. The web application supports authentication and authorization.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

### Prerequisites

- [Python](https://www.python.org/) installed
- [Pip](https://pip.pypa.io/en/stable/) installed on your machine.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Running the App

**Manual commands**

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/Li-HsuanChien/Online_course_app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Online_course_app
    ```

3.  Set up a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

    ```bash
    venv\Scripts\activate
    ```

    - On Linux/macOS:

    ```bash 
    source venv/bin/activate
    ```

5. Install the required dependencies:

    ```bash
    pip install -U -r requirements.txt
    ```

6. Run the application:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver
    ```
7. The application will be listening to `http://localhost:8000/` by default.

8. Create super user by executing:

    ```bash
    python manage.py createsuperuser
    ```

8. Direct to `http://localhost:8000/admin` to utilize django admin tool to set up courses and users.

9. Direct to `http://localhost:8000/onlinecourse` to use the main application

<p align="right">(<a href="#readme-top">back to top</a>)</p>

**Using Docker Containers**

1. Login to Docker Hub:

    - Open a terminal or command prompt and run the following command to log in to Docker Hub:

    ```bash
    docker login
    ```
    - Enter your Docker Hub username and password when prompted.

2. Pull the Online Course App Image:

    - Run the following command to pull the Online Course App Docker image from Docker Hub:

    ```bash
    docker pull shanechien/online_course_app
    ```

3. Run the Container:

    - Once the image is successfully pulled, you can run a container using the following command:
    
    ```bash
    docker run -p 8000:8000 shanechien/online_course_app
    ```
4. The application will be listening to `http://localhost:8000/` by default.

5. Create super user by executing:

    ```bash
    python manage.py createsuperuser
    ```

6. Direct to `http://localhost:8000/admin` to utilize django admin tool to set up courses and users.

7. Direct to `http://localhost:8000/onlinecourse` to use the main application

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage
  **Course Management:**
  
  -Add and customize courses with details such as name, description, duration, and prerequisites.
  -Organize course lectures, allowing instructors to upload multimedia content and presentations.

  **Quiz Hosting:**

    -Utilize Django Admin features to create and manage quizzes with varying complexities.
    -Define quiz parameters, set answers, grade values, with diverse question types, then calulate results when submitted.
    -Allow reviewing right and wrong answers.

**User Authentication and Roles:**

    -Robust authentication mechanisms ensure secure access with customizable user roles.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Awaiting Updates

**Role focused functions**
    
    -Allow instructors to give feedback, grading, and other features
    -Provide to learners User-friendly dashboards provide information on enrolled courses, upcoming lectures, and assessment deadlines.

**Customization Options:**

    Tailor the platform to your institution's branding with customizable themes and logos.
    Integration capabilities with external systems for a seamless learning ecosystem.

**Scalability and Performance:**

    -Hosting independent sites and data base with cloud, ensuring scalability for growing user bases.
    -Robust performance optimization guarantees a smooth and responsive experience.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Feel free to contribute to the development of this system by creating issues or pull requests.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

This project is licensed under the Apache 2.0 - see the [LICENSE](LICENSE) file for details.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Django]: https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white
[Django-url]: https://www.djangoproject.com/
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[product-screenshot-one]: images/snapshot1.jpg
[product-screenshot-two]: images/snapshot2.jpg
[product-screenshot-three]: images/snapshot3.jpg
[contributors-shield]: https://img.shields.io/github/contributors/Li-HsuanChien/Online_course_app.svg?style=for-the-badge
[contributors-url]: https://github.com/Li-HsuanChien/Online_course_app/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Li-HsuanChien/Online_course_app.svg?style=for-the-badge
[forks-url]: https://github.com/Li-HsuanChien/Online_course_app/network/members
[stars-shield]: https://img.shields.io/github/stars/Li-HsuanChien/Online_course_app.svg?style=for-the-badge
[stars-url]: https://github.com/Li-HsuanChien/Online_course_app/stargazers
[issues-shield]: https://img.shields.io/github/issues/Li-HsuanChien/Online_course_app.svg?style=for-the-badge
[issues-url]: https://github.com/Li-HsuanChien/Online_course_app/issues
[license-shield]: https://img.shields.io/github/license/Li-HsuanChien/Online_course_app.svg?style=for-the-badge
[license-url]: https://github.com/Li-HsuanChien/Online_course_app/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/lihsuan-chien/
