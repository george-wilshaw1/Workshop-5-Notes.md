# Workshop-5-Notes.md
Segues
What is a segue
A way to move to a new view controller.

What is a segue identifier?
string value 

How do you create segue from a button?
ctrl click and then show but there is no way to trigger it

How do you create from a view controller without a button?
ctrl click from the main view controller

What is the method to perfrom a segue called and what argument does it take?
performSegue(with identifier

What method is called immediatly before a segue is performed?
prepare(for segue

How do you assign a new view controller class?
Identity inspector and change the name to a new file called DetailViewController

How do you pass data between two view controllers? (this will need a few sentances to explain)


You dont link a segue "backwards", why?
The view controllers don't disappear they are stuck behind the new one so eventually the phone will run out of memory and crash 
