#GONManagedObjectObserver
Easily build NSAttributedString from XML/HTML like strings.

When using CoreData, it is often difficult to handle objects deletion / updates.
NSFetchedResultsController are greate for list, but to observe only one object, they are overkill.
A lot of application crash can occurs is you access to a previously deleted NSManagedObject.
Also, your UI can be outdated if you are updateing your NSManagedObject in a background thread for example.
This class simplify NSManagedObject update / deletion, providing a block syntaxe and some useful categories.


#WIP#

##Versions
0.5   : Initial release<br/>
