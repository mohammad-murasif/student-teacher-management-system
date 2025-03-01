# Student-Teacher Management System  

## Cloning the Repository  
To get started, clone the repository to your local machine:  
```bash
git clone https://github.com/mohammad-murasif/student-teacher-management-system.git
cd student-teacher-management-system
```

## Installing Dependencies  
Ensure you have Python installed, then install the required dependencies:  
```bash
pip install -r requirements.txt
```

## Setting Up MySQL Server Using MySQL Workbench  
Follow these steps to configure MySQL Workbench and create the required database:  

1. **Open MySQL Workbench** and connect to your MySQL server.  
2. In the **Navigator Panel**, go to the **Schemas** tab.  
3. Click the **"Create a New Schema"** button (database icon).  
4. In the **Schema Name** field, enter:  
   ```
   student_db
   ```
5. Click **Apply**, then **Apply** again in the confirmation window.  
6. Once created, refresh the schemas list to verify that `student_db` appears.  
7. Note your **MySQL username and password**, as they will be needed for Django to connect.  

## Running Migrations  
Once MySQL is set up, apply database migrations:  
```bash
python manage.py makemigrations
python manage.py migrate
```

## Running the Development Server  
Start the Django development server:  
```bash
python manage.py runserver
```
Now, open your browser and go to `http://127.0.0.1:8000/` to see your application running.  

---

Let me know if you have any issues! 🚀  
