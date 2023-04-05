#Record
This script is a simple database management tool that allows users to insert, search, update and delete records from a text file. The records are composed of two fields: a name and an amount. The text file is organized as a comma-separated values (CSV) file. The script provides a command-line interface that guides the user through the different options.

To use this script, simply run the bash script and follow the menu prompts. The menu options available are:

Insert: This option allows the user to add a new record to the database. If the record already exists, the script will prompt the user to update its amount instead.

Search: This option allows the user to search for a record by name. If the record is found, the script will display it along with its amount.

Update: This option allows the user to update an existing record. The user can choose to update the name or the amount of the record. If the name is updated, the script will check if the new name already exists in the database.

Delete: This option allows the user to delete an existing record. The user can choose to delete the record or update its name or amount.

Print Amount: This option allows the user to print the total amount of all records in the database.

The script also performs some error checking to ensure that the user inputs valid data. For example, the user cannot input a negative amount or a non-numeric value for the amount.

To use this script, you need to have bash installed on your system. The script has been tested on Linux systems.
