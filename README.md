# booktracker

## db schema

isbnValue is a 13-digit number generally found on the back of the book.
category helps to classify the books in three categories as shown below.

```realtime database schema
{
    "isbnValue":{
        "name":"name of the book",
        "category:"possible values are toread,reading,read"
    }
}
```