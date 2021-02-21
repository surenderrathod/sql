## Import data from csv file to postgresql table 

Importing data from windows server

```sql
 \copy "Customers" from 'C:\Users\admin\Desktop\Customers.csv' with delimiter ',' csv header encoding 'windows-1251';
```
