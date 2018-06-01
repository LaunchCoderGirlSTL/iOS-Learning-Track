Swift Syntax
============

Objectives
----------

- Become familiar with using tableView delegates and dataSources
- Understand how to create a segue to another storyboard by using a storyboardReference
- Know how to transition to another storyboard using a storyboard segue in code, and pass data to the storyboard's view controller

Requirements
------------

- Create a project that has a tableview with at least 5 cells (but only one prototype cell!)
- These cells should be flashcard-esque, in that they will prompt the user to think of some common Swift Syntax
- A user should be able to tap on a cell, which will transition to another view controller where the answer will be displayed

Hints
-----

- Remember to create a Struct with the "question" and "answer" as variables, which will be passed via the segue.
- Don't forget to embed your main view controller in a NavigationViewController
- Don't forget to add a cellIdentifier and segueIdentifier to the prototype cell on the table view, and the segue, respectively
- Think of ways to make your code easier to read by using MARKS, and putting code you can group together in extensions, like this::

   //MARK - tableView dataSource
   extension UIViewController: tableViewDataSource {
      ...
   }
