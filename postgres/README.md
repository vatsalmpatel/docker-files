How to Use It
Launch the containers:
Open your terminal in the folder where the file is saved and run:

Bash
docker-compose up -d
Access pgAdmin:
Open your browser and go to http://localhost:8080. Log in using the credentials from the file:

Email: admin@admin.com

Password: adminpassword

Connect pgAdmin to PostgreSQL:
Once logged into pgAdmin, you need to register the server:

Right-click Servers > Register > Server...

General Tab: Set Name to Local Postgres.

Connection Tab:

Host name/address: db (This is the service name from the compose file).

Port: 5432

Username: admin

Password: password123

Click Save.