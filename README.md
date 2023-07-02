# Job Application Form

The Job Application Form is a web application developed using Django. It allows job applicants to fill out a form with their personal information and submit it. The submitted form data is stored in a database, and an email notification is sent to the applicant with the submitted details.

## Features

- **Form Submission**: Users can fill out the job application form by providing their first name, last name, email, available start date, and current occupation.
- **Database Storage**: The submitted form data is stored in a database using Django's ORM.
- **Email Notification**: After successful form submission, an email is sent to the applicant's provided email address using Django's email backend.
- **Flash Messages**: Flash messages are used to display a success message to the applicant after form submission.
- **Responsive Design**: The form is designed using Bootstrap to ensure a responsive and user-friendly interface.

## Requirements

The application requires the following dependencies:

- Django==4.2.2

Please refer to the `requirements.txt` file for detailed version information.

## How to Run

To run the Job Application Form:

1. Make sure you have the required dependencies installed in your Python environment.
2. Execute the `manage.py runserver` command in the project's root directory.
3. The application will start running locally.
4. Open a web browser and go to `http://localhost:8000` to access the form.
5. Fill out the form fields with the required information.
6. **Note: Replace the `EMAIL_HOST_USER` and `EMAIL_HOST_PASSWORD` in `settings.py` with your own email address and password to enable email notifications.**
7. Click the "Submit" button to submit the form.
8. If the form submission is successful, a success message will be displayed, and an email notification will be sent to the provided email address.

## Database

The submitted form data is stored in a database. The database configuration can be found in the `settings.py` file. By default, the application uses a SQLite database.

## Templates

The application uses several HTML templates to render different pages:

- `base.html`: The base template that provides the common layout and navigation for all pages.
- `index.html`: The template that renders the job application form.
- `about.html`: The template that renders the "About Us" page.
- `contact.html`: The template that renders the "Contact Us" page.

These templates are located in the `templates` directory and are designed using HTML and Bootstrap to provide an intuitive and responsive form interface.

## Admin Panel

The Django admin panel is used to manage the submitted form data. To access the admin panel:

1. Run the command `manage.py createsuperuser` to create a superuser account.
2. Enter the desired username, email, and password for the admin account.
3. Run the command `manage.py runserver` to start the development server.
4. Go to `http://localhost:8000/admin` in your web browser.
5. Log in with the superuser account credentials.
6. You can now view and manage the submitted form data in the admin panel.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to acknowledge the developers and contributors of the open-source libraries used in this project. Their contributions and dedication have greatly facilitated the development of this Job Application Form. We express our gratitude to the following projects:

- [Django](https://www.djangoproject.com/)

Their efforts have played a vital role in making this project possible.

## Contact Information

If you have any questions or need further assistance, please feel free to reach out to us. You can contact us via email at [subhojitguin2004@gmail.com](mailto:subhojitguin2004@gmail.com).

We appreciate your interest in our Job Application Form and look forward to hearing from you.

Thank you!

Best regards,

Subhojit Guin
Creator of Job Application Form