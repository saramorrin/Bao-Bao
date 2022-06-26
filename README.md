Introduction


A live website can be found here

Website Preview

# 1. UX


1.1. Strategy
Project Goals


User Goals:
First Time Visitor Goals



User Stories

1.2. Structure
1.3. Skeleton
Wireframes


1.4. Surface
# 2. Features
# 3. Technologies Used
HTML5
The project uses HyperText Markup Language.
CSS3
The project uses Cascading Style Sheets.
JavaScript
The project uses JavaScript.
Python
The project uses Python.
Boostrap 5
The project uses Bootstrap 5.
PostgreSQL
The project uses PostgreSQL as a database.
Gitpod
The project uses Gitpod.
Chrome
The project uses Chrome to debug and test the source code using HTML5.
Balsamiq
Balsamiq was used to create the wireframes during the design process.
Google Fonts
Google fonts were used to import the "Be Vietnam Pro" font into the style.css file which is used on all pages throughout the project.
GitHub
GitHub was used to store the project's code after being pushed from Git.

# 4. Testing

# 5. Development Cycle
Project Checklist
Install Django and the supporting libraries
Install Django and Gunicorn. Gunicorn is the server I am using to run Django on Heroku.
Install support libraries including psycopg2, this is used to connect the PostgreSQL database
Install Cloudinary libraries, this is a host provider service that stores images
Create the requirements.txt file. This includes the project's dependencies allowing us to run the project in Heroku.
Create a new, blank Django Project
Create a new project
Create the app
Add restaurant_booking to the installed apps in settings.py
Migrate all new changes to the database
Run the server to test
Setup project to use Cloudinary and PostgreSQL
Create new Heroku app
Sign into Heroku
Select New
Select create new app
Enter a relevant app name
Select appropriate region
Select the create app button
Attach PostgreSQL database
In Heroku go to resources
Search for Postgres in the add-ons box
Select Heroku Postgres
Submit order form
Prepare the environment and settings.py file
Create env.py file
Add DATABASE_URL with the Postgres URL from Heroku
Add SECRET_KEY with a randomly generated key
Add SECRET_KEY and generated key to the config vars in Heroku
Add if statement to settings.py to prevent the production server from erroring
Replace insecure key with the environment variable for the SECRET_KEY
Add Heroku database as the back end
Migrate changes to new database
Get static media files stored on Cloudinary
Create a Cloudinary account
From the dashboard, copy the API Environment variable
In the settings.py file create a new environment variable for CLOUDINARY_URL
Add the CLOUDINARY_URL variable to Heroku
Add a temporary config var for DISABLE_COLLECTSTATIC
In settings.py add Cloudinary as an installed app
Add static and media file variables
Add templates directory
Change DIR's key to point to TEMPALTES_DIR
Add Heroku hostname to allowed hosts
Create directories for media, static and templates in the project workspace
Create a Procfile
Deploy new empty project to Heroku
Deployed Heroku

# 6. Deployment
I used the terminal to deploy my project locally. To do this I had to:

Create a repository on GitHub.
Clone the repository on your chosen source code editor (GitPod in my case) using the clone link.
Open the terminal within GitPod
Enter "python3 manage.py runserver into the terminal.
Go to local host address on my web browser.
All locally saved changes will show up here.
For the final deployment to Heroku, I had to:

Uncomment the PostgreSQL databse from my settings.py file.
Set debug = False in my settings.py file.
Commit and push all files to GitHub
In Heroku, remove the DISABLE_COLLECTSTATIC config var.
In the deploy tab, go to the manual deploy sections and click deploy branch.

# 7. End Product


# 8. Known Bugs

# 9. Credits
Cloudinary for image urls