## Part B: Hibernate CRUD Operations

### Description

* Performs **Create, Read, Update, Delete** operations on `Student` entity.
* Uses Hibernate ORM with MySQL database.
* Hibernate configuration in `hibernate.cfg.xml`.

### How to Run

1. Make sure MySQL is running and `nimbusdb` exists. Update `hibernate.cfg.xml` with your username/password.
2. Navigate to `PartB_HibernateCRUD/src/main/java`.
3. Compile all Java files:

```bash
javac -cp "path_to_hibernate_jars/*:path_to_jpa_jars/*:path_to_mysql_connector/*" com/example/hibernatecrud/*.java com/example/hibernatecrud/model/*.java com/example/hibernatecrud/dao/*.java
```

4. Run the application:

```bash
java -cp ".:path_to_hibernate_jars/*:path_to_jpa_jars/*:path_to_mysql_connector/*" com.example.hibernatecrud.MainApp
```

**Expected Output:**

* Adds sample students
* Displays all students
* Updates a student
* Deletes a student
* Shows final student list
