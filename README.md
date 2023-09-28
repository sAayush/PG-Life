# PG-Life

> This project was made while I was doing the web development course in internshala website.

It is a full-stack website with the concept of finding pg's in a city you want.

It is made suing XAMPP so it must be installed to actually use the project

### **TO INSTALL**

```
XAMPP Software
```

### **Dummy data for database**

```
'data' Folder
```

## Xampp Stuff

Once you have installed Xampp go to the file location and browse to htdocs named folder.
For me its in
```E:\Softwares\XAMPP\htdocs```

But if you have default then it should be:

```C:\XAMPP\htdocs```

**Once you are on the folder**
**Make sure to Clone this project there or move it there it is essential for it to be in `htdocs` folder.**

## **Steps to run**

There are two major things that you need to do before the project will work completly.

- Creating tables for data.
- Inserting data into tables.

### Creating tables

1. Run XAMPP
2. Run the apache server and MySQL Server
3. Go to the **`Table.sql`** file
4. Copy the contents.
5. Go to MySQL admin in XAMPP
    - Select the SQL tab from top
    - Type the command:
    ```CREATE DATABASE pglife;```
    - Press run.
    - Now, type the command:
    ```USE pglife;```
6. Finnally paste the contents of the file.
7. Press run (ctrl + enter).

### Inserting data

1. You Should still be on SQL page.
2. Go to **`dummy_data.sql`** file.
3. Copy the contents.
4. Paste it in the SQL area.
5. Click run (ctrl + enter).

## Run the project

Make sure you have MySQL and Apache servers on.

1. Click on Admin for Apache server.
2. Click on the `PG-Life` hyperlink.

And bamm it should work.

> I hope this was helpful.
