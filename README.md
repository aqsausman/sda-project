
# Running Project

1 Open the project with Visual Studio.
2 in `web.config`file change the connection string according to your system.
  ```
  <connectionString><add name="ClinicDB" connectionString="data source=Your data source; initial catalog=ClinicDB;Integrated Security=True" providerName="System.Data.SqlClient" /></connectionString>
  ```
3 In package manager console run the following commands 
    ```
    - enable-migrations
    -  add-migration "InitialDb"
    -  update-database
   ```
4 Open the database
5 In `AspNetRoles` table add  Administrator and Doctor.
6 Run the project.