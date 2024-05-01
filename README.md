# Python_Namaste_Kart
This project is part of Namaste Python course


# Libraries I used :

Openpyxl
Datetime
Shutil
Os
Sys
Random

# Validations.py

# Functions :

column_values(file_path,file_name,column_name) -> requires file's path, file name, column_name and it returns the columunar values. Column can exist any where, function will search index based on column name and grab column values.

validate_product_id_existed(product_id) -> checks where file's product_id existed in master table and returns boolean value

validate_sales(product_id,product_quantity,product_sales) ->  checks total sales amount should be (product price from product master table * quantity) and returns boolean value

validate_order_date(order_date) -> checks the order date should not be in future and returns boolean value.

validate_emptiness(row_values) -> checks any field should not be empty and returns boolean value.

validate_city(city) -> checks The orders should be from Mumbai or Bangalore only and returns boolean value

validations(file_path,file_name,reject_path) -> receives the file and validate the above conditions. If all conditions are met then it moved to success folder and if any condition fails, it fall under reject folder with name error_filename.



# Main.py

Paths declared.

Checks length of incoming folder, and validates all conditions, if any failed then moved to rejected folder with same name and it succeed then move to success folder.




