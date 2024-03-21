# Billing application

A simple command line based bill calculator using Go

The application then saves the bill to a file in the bills folder

## Usage

To run the application, in the command line type,

```
go run main.go bill.go
```

## Example

```
Create a new bill name: Bala's bill
Created the bill -  Bala's bill
Choose option (a - add item, s - save bill, t = add tip): a
Item name: cake
Item price: 5.99
item added -  cake 5.99
Choose option (a - add item, s - save bill, t = add tip): a
Item name: pie
Item price: 3.99
item added -  pie 3.99
Choose option (a - add item, s - save bill, t = add tip): t
Enter tip amount ($): 10
tip added -  10
Choose option (a - add item, s - save bill, t = add tip): s
Bill was saved to file
you saved the file -  Bala's bill.txt
```

## Output
```
Bill breakdown 
cake:                     ...$5.99 
pie:                      ...$3.99 
tip:                      ...$10.00
total:                    ...$19.98
```

## Credits
[Go Tutorial by NetNinja](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gC88BEo9czgyS72A3doDeM)