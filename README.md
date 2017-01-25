# BookStoreSystem

This is the final and completed version of the Book Store Management System, initially laid out by Professor Christine Lauredneau with everything being statically allocated.

With the the collaboration of myself and Yin Yeun Leng, the program was converted to become fully dynamically allocated, and also more usable with newer features and a "Checkout System"

For instructions reegarding the program, keep reading:

THIS WAS WORKED ON BY THE FOLLOWING PARTNERS:
- MUHAMMAD AWAIS QURESHI
- YIN YUEN LENG

PURPOSE:  Modifying the bookstore management program to implement a templated collection class. Also, to incorprate polymorphism and an abstract class into our program

SOURCE FILES: UImanager.cc, BMScontrol.cc, Dlist.cc, Course.cc, BookArray.cc, Book.cc, BookstorInventory.cc, Technology.cc, Games.cc, Apparel.cc, Buy.cc, BookRentalPeriod.cc, Reserve.cc, Return.cc, main.cc.

HEADER FILES: UImanager.h, BMScontrol.h, Dlist.h, Course.h, BookArray.h, Book.h, BookstoreInventory.h, Games.h, Apparel.h, Technology.h, Buy.h, Return.h, BookRentalPeriod.h, Reserve.h defs.h .


OUR FEATURE MIMICS THE REGULAR TRANSACTIONS THAT GO ON IN A BOOKSTORE
WE HAVE: ~ BUYING PRODUCTS -> GETS THE PRODUCT INFO, REMOVES IT FROM THE PRODUCT ARRAY & 				   					  CALCULATES THE CHANGE THAT IS DUE ON THE PURSCHASE.

		 ~ RESERVING A PRODUCT -> GETS THE PRODUCT INFO, AND RESERVES THAT PRODUCT

		 ~ RETURNING A PRODUCT -> GETS THE PRODUCT INFO , ADDS IT TO THE PRODUCT ARRAY & 								CALCULATES THE REFUND ON THAT PRODUCT

		 ~ RENTING A BOOK  -> ALLOWS THE RENTING OF A BOOK FOR SOME AMOUNT OF TIME

	THE BASE ABSTRACT CLASS IS CALLED TRANSACTION. IT CONTAINS A PURE VIRTUAL FUNCTION CALLED transactionHandle, WHICH RETURNS A STRING WHICH IS PRINTED ONTO THE CONSOLE FOR THE USER TO SEE. EACH CLASS' FUNCTION IS DOCUMENTED IN EACH HEADER FILE. THE transactionHandle FUNCTION IS CALLED IN OPTION #15, WHERE IT ALSO REMOVES AND ADDS EVERYTHING IF A BUY/RETURN OPTION HAS BEEN CHOSEN. 





Thank you,
Muhammad Awais Qureshi

