**Hello World Django Application**

**Prerequisites**
Before running this project, ensure you have the following installed on your system:

i)Python 3.x
ii)Django (Refer to the steps below for installing Django)

**OverView:**

This is a sample django application which returns a JSON object with a "Hello World" message.

****How to run the project** **

1)**Clone the repository**: Clone the project respository and navigate to the project folder by using below commands
git clone https://github.com/Akhila-Parvathaneni/Software-Architecture-Design-HelloWorld.git
cd Software-Architecture-Design-HelloWorld/akhila_prj

**2)Create a virtual environment:** It's recommended to create a virtual environment for isolating the dependencies.
python3 -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

**3)Install Django:** As we need django to run the web app install it by using below command
pip install django

**4)Running the Application**

   i)First navigate to the project directory : cd akhila_prj
   ii)Run the initial migrations to setup the database : python manage.py migrate
   iii)Start the development Server python manage.py runserver
   iv)Once the server is running, open a browser and navigate to http://127.0.0.1:8000/hello/ this will return the JSON response.

**Sample Output:**
<img width="599" alt="image" src="https://github.com/user-attachments/assets/c74a1a29-2592-4cf0-b1c9-81df7a485aa5">

