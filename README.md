# TechServe4U Transformation Portal

## Field Force Management
**Services**(*Click on the names to view the codes*):
- [Auth](https://gitlab.com/project-transformation/ffm-authentication-service)
- [User Management](https://gitlab.com/project-transformation/ffm-user-management) 
- [Attendance](https://gitlab.com/project-transformation/ffm-attendance-service)
- [Delivery](https://gitlab.com/project-transformation/ffm-delivery-service)
- [Task](https://gitlab.com/project-transformation/ffm-task-service)

### Tech stack

| Section  | Technology / Framework |
| ------------- | ------------- |
| Web Framework  | Flask(Python), NodeJS()  |
| Relational Database  | PostgreSQL  |
| Caching  | Redis  |

### Up and Running with the project
1. Install **docker** and **docker-compose**
```bash
$ sudo apt update 
$ sudo apt install docker.io
$ sudo apt install docker-compose
```
2. Run the **compose**
```bash
$ sudo docker-compose up
```

In about 4-5 mins, the environment will be up and running

### Accessing the services API
- Auth => http://server-ip:5001/api/auth
- User Management => http://server-ip:5004/api/user-management
- Attendance => http://server-ip:5006/api/attendance
- Delivery => http://server-ip:5005/api/delivery
- Task => http://server-ip:5003/api/task

### Steps to get started
1. Go to http://server-ip:5001/api/auth
    - Create Super Admin
    - Login as Super Admin
    - Create a new Company
    - Create new Dashboard User under the Company
    - Register new User under the Company
2. Go to Database Dashboard and watch for the changes

### Accessing the Database Dashboard
**Dashboard Login**

URL: http://server-ip:5050
Email: admin@fieldforce.org
Password: admin

**Database Server Credentials**

Host: postgres
User: postgres
Password: 123TS4UTransformation
