# Week 5 Homework Codebook

### Libraries used:
- data.table

### Objects created
- df: data.table object
  - All names from yob2016.txt
  - Columns: name(character), gender(character), count(numeric)
  
- y2016: data.table object
  - df without the erroneous "Fionayyy" row

- y2015: data.table object
  - all names from yob2015.txt
  - same column names as df; name, gender, count
  
- final: data.table object
  - 2015 and 2016 names merged on the name as key
  - Columns: name(character), gender(character), count_2015(numeric), count_2016(numeric), total(numeric)
  
### Outputs
- top_10_girls_names.csv
  - Contains the 10 most popular girls names, by total names in 2015 and 2016