# Remote Jobs Connect
 In this job portal, the applicants and companies can register themselves. Both are provided with different roles. The applicant can see a list of jobs available and can apply to any that matches his/her skill set. Similarly, the companies can add new jobs and select the applicants who have applied for that job by seeing their resume. It is designed to be a simple, easy-to-use platform for both job seekers and employers.

## Features
- Employers can create a profile and post job openings, including details such as the job title, location, salary, and required qualifications.
- Job seekers can search for jobs using keywords and filters, and apply to openings by submitting their resume and cover letter.
- The application includes a built-in messaging system that allows employers and job seekers to communicate with each other directly.
- User dashboard allows users to manage their job search and application process.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
You will need to have the following software installed on your system:

- Python (3.9 or later)
- Django (2.2 or later)

### Installation

1. Clone the repository to your local machine:

```
git clone git@github.com/Victor-Amonde/RemoteJobsConnect.git
```

2. Navigate to the project directory:

```
cd RemoteJobsConnect
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

4. Run the migrations to set up the database:

```
python manage.py migrate
```

5. Create a superuser to access the admin panel:

```
python manage.py createsuperuser
```

6. Run the development server:

```
python manage.py runserver
```

7. Open a web browser and go to `http://localhost:8000` to view the application.

## Deployment
To deploy Remote Jobs Connect on a production server, you will need to set up a web server such as Apache or nginx, and a database server such as PostgreSQL. Please refer to the Django documentation for more information on deploying Django applications.

## Contributing
If you would like to contribute to the development of Remote Jobs Connect, please fork the repository and create a pull request with your changes. All contributions are welcome and appreciated.

## License
This project is licensed under the MIT License - see the <u>**LICENSE**</u> file for details.

