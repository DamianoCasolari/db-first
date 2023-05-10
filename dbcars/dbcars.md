# Database Cars

## data types

    - Strings: varchar(number) (max255), char(number), text, longtext
    - numbers: tinyint, small/medium int , int, bigint
    - decimals: float(i,d), double(i,d), decimal(i,d)
    - dates: DATETIME, DATE, YEAR, TIME, TIMESTAMP


## Entity name: Car

## Table name : Cars

## Table column 

  - *id* : bigint, primarykey, auto increment, notnull, unique, index
  - *car* model : varchar(200), notnull, index
  - *car* brand : varchar(100), nullable, index
  - *country* : varchar(60) nullable
  - *price* : smallint, nullable
  - *date_of_enrollment* : date, notnull
  - *km* : mediumint, nullable
  - *fuel type* : varchar(50), nullable, index
  - *color* : varchar(50), nullable, index
  - *transmission* : varchar(50), nullable
  - *number of doors* : tinyint, nullable
  - *number of seats* : tinyint, nullable
  - *engine displacement* : decimal(6,2), nullable
  - *horsepower* : smallint, nullable
