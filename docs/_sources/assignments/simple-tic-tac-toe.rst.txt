Objectives
----------

- Become comfortable with making IBActions and IBOutlets from the Storyboard to the associated view controller
- Become familiar with UIViews, UILabels, and UIButtons
- Use optional unwrapping using guard statements
- Become familiar with type casting between Strings and Ints

Requirements
------------

- A Tic-Tac-Toe Board that display correctly on 1 type of iOS Device
- 9 Buttons with text that rotate between "", "X", and "O" when pressed
- The 9 buttons should all be connected to one function that performs the action

Hints
-----

- The line of code for changing the text of a UIButton is a little strange, so here it is:

  - ```myButton.setTitle("X", forControlState: .normal)```
  
- Once you connect one button to the view controller with an IBAction, you can control+drag the additional buttons to that same function
- Don't forget:

  - If you change the name of the Main.storyboard, you need to change the Project Settings(Blue Icon at top of the Project Navigator)/(Make sure the first option under "Targets" is selected)/General /Deployment Info/Main Interface to the re-named storyboard
  - Make sure your actions are connected properly or your app will crash! Remember to either right-click elements in the storyboard, or use the Connections Inspector in the Storyboard file (Right Pane, far-right symbol)
