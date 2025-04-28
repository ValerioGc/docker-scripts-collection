## Docker Scripts

*A collection of useful scripts ready to use for deployment, building, and managing Docker front-end projects based on Node.js, PHP, Laravel and Java, databases and redis.*


### Prerequisites
- **Docker** installed on your machine.
- **Docker Desktop + WSL2** installed on your machine if you are using Windows.

<br/>


### Front end Scripts:

- **Node dev server**:
  - Build and run the Node.js container.
  - Run the dev server on port 3000.
- **Nitro dev server**:[TODO]
  - Build and run the Nitro container.
  - Run the dev server on port 3000.
- **Static server httpd**: [TODO]
  - Build and run the httpd container.
  - Run the static server on port 80.

---

### Back end Scripts:

#### **PHP**:
  - **server**:
    - Build and run the PHP container.
    - Run the dev server on port 80.

  - **LAMP**:
    - Build and run the LAMP container.
    - Run the Apache HTTPD server on port 80/443.
    - Run the MySQL server on port 3306.
    - Run the phpMyAdmin server on port 8080.

#### **Laravel**:
  - **Laravel dev server**:
    - Run the Laravel dev server on port 8000.
  - **Laravel LAMP**:
    - Build and run the LAMP container.
    - Run the Apache HTTPD server on port 80/443.
    - Run the MySQL server on port 3306.
    - Run the phpMyAdmin server on port 8080.
    - Install laravel and dependencies.
    - Run the Laravel dev server on port 8000.


### License
This project is licensed under the 0BSD License - see the [LICENSE](LICENSE) file for details.