### Capstone database installation

1. ##### Requirments

   First create virtual environment:

   ```
   conda create -n strym "python=3.7"
   ```

   install the following modules

   ```
   pip install strym
   pip install SQLAlchemy==1.4.35
   pip install PyMySQL==1.0.2
   ```

2. ##### Create tables

   First create your tables in your database.

   Here is an example

   ```
   m_host='sh-cynosdbmysql-grp-75qwodo8.sql.tencentcdb.com'
   m_port =29563
   m_user='capstone'
   m_password='capstone123!!!'
   m_db='circle_database_version3'
   ```

3.  **Batch insert**

   batch_insert.ipynb will help you inset all the information needed for the project. Make sure all the csv files are in the same dir. you can all change the serach range with the codes follows:

   ```
   can_list, gps_list = get_all_file('.')
   ```

4. **issues**

   





 