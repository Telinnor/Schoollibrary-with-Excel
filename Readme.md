# Schoollibrary Excel table

This table is to organize a library with Excel.
The whole Table is in german, if you want an english version just contact me.

## Usage

Activate the Macros on that table. Maybe you need to trust the file in the file explorer.

### How to borrow

To borrow a book, go to the "ausleihen" register and type the corresponding ID for the borrower (more on [Borrower ID](#borrower-id)).
On the next cells, you need to type in the ISBN of the Books. To finish the borrowing just click the "ausleihen" Button.

### Return a book

To return a book, you have to open the "Rückgabe" register. And type or scan the ISBN of the books and click the "Rückgabe" button. You can only return 10 Books at one.

### Borrower ID

The Borrower ID can be seen in the "Benutzer" register. There the ID can be modified. There is also the first and surname of the corresponding person and also the class the student is. A Barcode is shown in the Code_39 format (for that is the font), that Barcode is the ID. The idea is that maybe that can be printed out and be in folder at the desk to be scaned by a Barcodescanner.

### Inventory

At every borrow the book is protocoled in the "Inventur" register. If a book dont have automaticly the correct title just change it there.

### See the active borrows

On the "Ausgeliehen" register you can see the active borrows, from whom and when and what. There is also an indicator when the item have be returned.

### Reset something/everything

There is no automatic reset function you have to do it manually. Unlock the needed register([Password](#passwords)). delete the rows with the information you want to delete. Maybe you have to modify the "gesamtLeihen" counter.

### Passwords

Something is locked with a password. To unlock and do the modification just go on "Datei"->"Information"->"Arbeitsmappe schützen" and click on "Schutz aufheben" for the correct register.
The password is just "Password" :)
To lock it again save, close and open again.

