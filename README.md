EventHub — Event Management Platform
Project Overview
EventHub is a web application designed to help users organize and discover events. The platform focuses on leisure and educational activities, such as movie screenings, board game nights, student meetups, and more. It simplifies the process of event planning and community building through an intuitive user interface.

Tech Stack
Framework: Django (Python)

Database: SQLite (default) / PostgreSQL support

Environment: Python Virtual Environment

Core Features
User Authentication: Secure registration and login system.

Event Creation: Organize events by specifying the title, description, date, time, location, and maximum participant capacity.

Participant Management: View a real-time list of attendees for each event.

Personalized Dashboard: A dedicated user profile page to manage booked tickets, track participation history, and view "liked" events.

Booking System: Integrated ticket booking functionality.

Smart Filtering: Quickly find events by category, date, or format (online/offline).

Future Scalability: Designed with a modular architecture to allow for further feature expansions.


Setup Instructions
Follow these steps to set up the development environment locally:
1. Clone the repository:
    git clone https://github.com/SvirinaDasha/Test_EventHub.git
2. Navigate to the project directory:
   cd django-event-hub
3. Create a virtual environment:
   python3 -m venv env
4. Activate the virtual environment:
   For Windows: .\env\Scripts\activate
5.Install dependencies from requirements.txt:
   pip install -r requirements.txt
6.Apply database migrations:
   python manage.py migrate
7.Create a Superuser:
   python manage.py createsuperuser
  Note: A default user (username: admin, password: admin) may already exist in the database. It is recommended to create a new user with a unique name for your local setup.
8. Run the development server:
   python manage.py runserver


Вимоги до версій:
asgiref==3.8.1
asttokens==2.4.1
attrs==23.2.0
backcall==0.2.0
beautifulsoup4==4.12.3
bleach==6.1.0
build==1.2.1
CacheControl==0.14.0
certifi==2024.2.2
charset-normalizer==3.3.2
cleo==2.1.0
colorama==0.4.6
crashtest==0.4.1
crispy-bootstrap4==2024.1
decorator==5.1.1
defusedxml==0.7.1
distlib==0.3.8
Django==5.0.4
django-betterforms==2.0.0
django-ckeditor==6.7.1
django-ckeditor-5==0.2.12
django-crispy-forms==2.1
django-js-asset==2.2.0
django-mapbox-location-field==2.1.0
docopt==0.6.2
dulwich==0.21.7
executing==2.0.1
fastjsonschema==2.19.1
filelock==3.13.3
idna==3.6
installer==0.7.0
ipython==8.12.3
jaraco.classes==3.4.0
jedi==0.19.1
Jinja2==3.1.3
jsonschema==4.21.1
jsonschema-specifications==2023.12.1
jupyter_client==8.6.1
jupyter_core==5.7.2
jupyterlab_pygments==0.3.0
keyring==24.3.1
MarkupSafe==2.1.5
matplotlib-inline==0.1.6
mistune==3.0.2
more-itertools==10.2.0
msgpack==1.0.8
nbclient==0.10.0
nbconvert==7.16.3
nbformat==5.10.4
packaging==24.0
pandocfilters==1.5.1
parso==0.8.4
pexpect==4.9.0
pickleshare==0.7.5
pillow==10.3.0
pkginfo==1.10.0
platformdirs==4.2.0
poetry==1.8.2
poetry-core==1.9.0
poetry-plugin-export==1.7.1
prompt-toolkit==3.0.43
ptyprocess==0.7.0
pure-eval==0.2.2
Pygments==2.17.2
pyproject_hooks==1.0.0
python-dateutil==2.9.0.post0
pywin32==306
pywin32-ctypes==0.2.2
pyzmq==25.1.2
rapidfuzz==3.7.0
referencing==0.34.0
requests==2.31.0
requests-toolbelt==1.0.0
rpds-py==0.18.0
setuptools==69.2.0
shellingham==1.5.4
six==1.16.0
soupsieve==2.5
sqlparse==0.4.4
stack-data==0.6.3
tinycss2==1.2.1
tomlkit==0.12.4
tornado==6.4
traitlets==5.14.2
trove-classifiers==2024.3.25
tzdata==2024.1
urllib3==2.2.1
virtualenv==20.25.1
wcwidth==0.2.13
webencodings==0.5.1
yarg==0.1.9
