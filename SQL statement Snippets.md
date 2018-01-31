##### Add default value to a column
```sql
ALTER table Country
ADD CONSTRAINT defaultvalue_countryid DEFAULT(NEWID()) FOR CountryId
```

