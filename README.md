# You need To make database name: todos
# Need to make table name also :todos
# table column: 2
# table columns   id    Title


<!-- 
-- Create the database
CREATE DATABASE IF NOT EXISTS todos;

-- Select the database
USE todos;

-- Create the todos table with the id column as AUTO_INCREMENT
CREATE TABLE IF NOT EXISTS todos (
    id INT AUTO_INCREMENT PRIMARY KEY, -- Auto-incrementing primary key
    Title VARCHAR(255) NOT NULL        -- Title column, cannot be NULL
); -->



<!-- if you want to modify id column in users table to make it AUTO_INCREMENT this is the right command  -->
<!-- ALTER TABLE users MODIFY id INT AUTO_INCREMENT; -->
