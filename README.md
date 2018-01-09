# Sambhavam (Possible)

## An Open source application framework for Job Consultancies and Outsourcing to rely upon automatiing daily repeated tasks.

### Examples

* Reading the Mail from Consultant describing the requirement of Job Profile they are looking for.

### Key Functionalities

* Extract Keywords from different input methods
    * Mail Body
    * Mail Attachment

### Getting Started

* Follow the Installation Documentation [here](Install.md)
* For Running the Application for the first time
    * Run the Migration

        ```sh
        $ python manage.py migrate
        ```

    * Creating Admin User

        ```sh
        $ python manage.py createsuperuser --email admin@sambhavam.com --username admin
        ```

* Start the Server
    ```sh
    $ python manage.py runserver
    ```
* Access the Application on http://localhost:8000/ which will open the Django Rest Framework API explorer.