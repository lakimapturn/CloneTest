# Assignment2 - TodoListApp

The main goal of this assignment is to test your SwiftUI knowledge while ensuring that you're able to adhere to a set of conventions. You have complete control over the design of this sample app, however you must implement the app using the instructions below. Try to be creative! The last SwiftUI tutorial should contain hints to help.

## Instructions

1. You must have two accessible screens: Todo-list screen, Todo-list Item View. 
2. Todo-list screen:
  - Has the header text "Todo-list".
  - Will contain all the tappable todo items added by some user. Tapping on the item should navigate the user to the Todo-list Item View with information regarding this particular item.
  - Has functionality enabling the user to add items (as text) to the todo-list. Hint: the list should be updated **the moment** a user adds the item.
4. Todo-list Item screen:
  - Must contain the text of that to-do item.
  - Has functionality enabling the user to edit the text. This can be implemented in several ways on the frontend, we won't restrict you.
  - Optional: display the time this item was added.
5. REQUIRED features to use in implementation, this list is NOT exhaustive:
  - The given classes/structs, which you have to fill out and edit. They're useful for figuring out the approach.
  - @State
  - @StateObject
  - Environment Objects
  - Protocols: ObservableObject, Identifiable
  - ScrollView (for the list of notes) 
  - Navigation
  - Optional: use Enums to aid in implementing optional functionality allowing the user to set a task priority between low-moderate-high.
