# RichardsonrjP06
This repository contains two programs that read user input values. The first sorts them in a LinkedList using java collections, and the second sorts them in an array and pushes them to a stack.

LinkedListReader.java:

-public class LinkedListReader:
  - Contains addAll() method.
    - Parameters: allValues- Integer values inputed by the user, each separated by a space.
                 linkedList- linked list created from java collections where the integers are sorted.
    - Adds all values to a linked list using java collections, then sorts the linked list.
  - main() method.
    - Creates an instance of a linked list.
    - Asks for an input of integers separated by a space (example: 1 4 3 9)
    - Adds integer values to the linkedlist.
    - Sorts and prints linked list using collections.sort().
    - upon execution this statement will be displayed and values should be input:
        - "Enter integers followed by a space (Ex: 1 4 3 9): "
          - Example output: [1, 3, 4, 9]
   
StackReader.java:

-public class StackReader:
  - Contains addAll() method.
    - Parameters: allValues- Integer values inputed by the user, each separated by a space.
                  stack- a stack created from java collections where the integers are pushed after being sorted.
    - Adds all values to a stack using java collections, integers will already be sorted and the stack will be in ascending         order.
  - main() method.
    - Creates an instance of a stack.
    - Asks for an input of integers separated by a space (example: 1 4 3 9)
    - Sorts integer values in an array..
    - pushes sorted elements to the stack and prints it out.
    - upon execution this statement will be displayed and values should be input:
      - "Enter integers followed by a space (Ex: 1 4 3 9): "
        - Example output: [1, 3, 4, 9]


