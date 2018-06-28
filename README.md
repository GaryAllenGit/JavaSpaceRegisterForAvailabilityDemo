This is a demo of the "registerForAvailability" method in the JavaSpace05 specification.

Written by Dr Gary Allen, University of Huddersfield.


The "registerForAvailability" method will accept a collection of templates (rather than a single template) and call the local "notify" method when an object arrives in the space which matches any of those templates.  When calling "notify" it will also provide a copy of the object that caused the notification to fire.


As usual, if using an IDE like IntelliJ you need to create a java project with the correct classes added as libraries, then paste the code in and run it.


If running from a command line, set up the classpath with:

	. jinicl

then compile with

	javac *.java

and run with:

	java RegisterForAvailabilityTest


Look at the code, which has extensive comments, to see what is happening.


