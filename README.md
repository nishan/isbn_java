isbn_java
=========

A java utility class for validating ISBN numbers

		// Using ISBN.java
		ISBN.isValid("1107666392"); // returns true
		ISBN.isValid("1107666393"); // returns false

		ISBN.isValid("9781107666399"); // returns true
		ISBN.isValid("9781107666398"); // returns false

		ISBN.toISBN13("1107666392"); // returns 9789382618348
		ISBN.toISBN10("9781107666399"); // returns 9382618341
