Objectives
----------

   - Understand the order of operations for adding and removing a child view controller from a container view

   - Get to know gestures implemented from the storyboard

   - Learn more about the layer property (CALayer) on a view and the style changes that can be made (see the end of the readme on Github for a good reference)

   - Continue using MVC design pattern when expanding model logic

   - Refresh your knowledge on table views and segues


Requirements
------------

Build a better flashcard app!

   - Use the subclassed UIView ContainerView from the in class project

   - Customize the ContainerView to appear like a card

      - Rounded corners

      - Border

      - Drop shadow

   - Feel free to use the PuppyData and RateMyPuppyModel classes from the base project from in class.

   - Show the puppy image in the container view as the front side of the flashcard, with the image taking up the entire container view (as shown in class).

   - Show the puppy image, name, and description on the other side of the flashcard. You will need to make the picture smaller in order to allow room for the labels for description and name. Use Autolayout to ensure the content fits in the container view by using constraints against Superview (not the default Safe Area).

   - You will need to expand functionality on RateMyPuppyModel to complete the assignment.

      - Track the number of times each card is viewed

      - find a way to allow the user to remove any card from the review list. This is up to you, but feel free to reach out to me if you're stumped. The user should be allowed to remove all cards from review, leaving no flashcards left.

   - When the user has no flashcards left, segue to a new full-screen view controller (not a child view controller of the container view).

   - The new full-screen view controller should contain a table view which shows the puppy name and number of times the card was viewed. If you want to, add a thumbnail of the puppy image to the cell as well.

      - BONUS: Consider embedding this controller in a navigation view controller so the user can return to the flashcard screen. Change the name of the 'back' button to 'reset'. When returning from the table view, reinstate all flashcards and reset the tracking.

   - Use the swipe gesture to move between cards.

   - Use the tap gesture to flip the card.

   - Use double tap to trigger the report segue early.
