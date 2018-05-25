Objectives
----------

   - Become familiar with collection view delegate methods.

   - Understand formatting tiles in a collection view using flow layouts.

   - Becoming comfortable with creating collection views inside of a collection view controller and setting up delegate and data source to the view controller.


Requirements
------------

   - Create a project that has a collection view with at least 10 cells

   - Create your own custom UICollectionView cell ( These can be just a single label in the center or you can use an image view like we did in class. Or, come up with an entirely new design for your flash card cell).

   - A user should be able to tap on a cell to "flip" the card to show the other side of the cell, similar to the MVC Flash Card app that you all have made.

   - Bonus points if you're able to use UI View Animations to transition between front and back of the card.


Hints
-----

   - Think about the data structure that well store the information for each of your cards, it might be valuable to create a struct for the front and back of your cell.

   - // You will use this to register a user tapping on a cell

      - ```func collectionView(_ collectionView: UICollectionView, didSelectItemAt indexPath: IndexPath) {

      }```
