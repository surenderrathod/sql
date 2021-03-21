## Import data from csv file to postgresql table 

Importing data from windows server

```sql
 \copy "Customers" from 'C:\Users\admin\Desktop\Customers.csv' with delimiter ',' csv header encoding 'windows-1251';
 
 \copy "Suppliers"("SupplierID","SupplierName","ContactName","Address","City","PostalCode","Country","Phone") from 'C:\Users\admin\Downloads\Suppliers.csv' with delimiter ',' csv header encoding 'windows-1251';
```

## Update query in sql

UPDATE "Customers" SET "Country" = 'United Kingdom' WHERE "Country"='UK' 

## WHERE CONDITIONS

```sql
SELECT * FROM "Customers" WHERE "Country"='United Kingdom'
```

## Left Join
```sql
select * from "Categories"
left join "Products" on "Products"."CategoryID" = "Categories"."CategoryID"
```
