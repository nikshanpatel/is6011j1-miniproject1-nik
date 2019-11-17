16.	**Reading Files**

Rather than deal with a list of individual String elements, you can read CSV data directly into a dictionary (technically, an Ordered Dictionary) as well.

Example: input file, employee_birthday.txt is as follows:
name,department,birthday month

John Smith,Accounting,November

Erica Meyers,IT,March
……………
Here’s the code to read it in as a dictionary this time:

import csv

with open('employee_birthday.txt', mode='r') as csv_file:
    
    csv_reader = csv.DictReader(csv_file)
    
    line_count = 0
   
   for row in csv_reader:
       
       if line_count == 0:
            
            print(f'Column names are {", ".join(row)}')
           
           line_count += 1
        
        print(f'\t{row["name"]} works in the {row["department"]} department, and was born in {row["birthday month"]}.')
        
        line_count += 1
    
    print(f'Processed {line_count} lines.')
