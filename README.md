# booktracker

### Announcement
Booktracker is now open source!

### TODO for later development and for open source 
 . styling and working on ui/ux
 . include firebase.auth() support
 . link to a github repo which contains three files reading.txt toread.txt read.txt for people who like to maintain their book track     in a github repo.
 include more and submit a pr 
 

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