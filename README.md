1. Clone the repository:

   ```bash
   git clone https://github.com/Mashrur2020/Cuetlinks.git
   cd Cuetlinks
   ```

2. Start MySQL from the XAMPP control panel.

3. Open phpMyAdmin (`http://localhost/phpmyadmin`) and create a database named `stdlink`, then import the SQL schema (create the tables used by the app).

4. Open the project in NetBeans and add the MySQL **Connector/J** JDBC driver to the project libraries.

5. Update the database credentials (host, port, username, password) in the DB connection code if needed.

6. Run the project — `Ctrl + Shift + F10` in NetBeans.

## 📁 Project Structure

```
├── src/           # Java source code
├── nbproject/     # NetBeans project configuration
├── build/         # Compiled classes
├── build.xml      # Ant build script
└── manifest.mf    # Application manifest
```

## 📄 License

This project is for academic purposes. Feel free to use and modify it for learning.
