# C-Hash-table-demo

### Personal project hash table in C demonstration

- Included "names.txt" serves as demo file can be read into the hash table by running ./hash_table.exe "names.txt"
- "names.txt" contains a list of 18,239 people's names 

### Menu Options
- Option 1 - Prints all items currently in the table
- Option 2 - Prints 'n' number of items in order from the table
- Option 3/4/5 - Search / Add / Delete items from the hash table
- Option 6 - Can add any text file you want to hash table with command line argument or using built in menu
  - asked to provide the path and the number of items you want to take from there
- Option 7 - Exit, End program
- Option 8 - 'Timing Test' performs a search of 'n' items from file and records the time taken to look up items
  - This was run with different sized hash tables for optimisation puposes
  - Diminished returns for tables over 1000 in size