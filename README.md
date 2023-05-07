Download Link: https://assignmentchef.com/product/solved-linked-list-class-to-hold-a-series-of-integers
<br>
Using the material in the textbook (NumberList) as a sample, <u>design your own linked list class</u> to hold a series of integers. The class should have the following member functions:

<em>append, insert</em> (at a specific position, return -1 if that position doesn’t exist), <em>delete</em> (at a specific position, return -1 if that position doesn’t exist), <em>print, reverse</em> (which rearranges the nodes in the list so that their order is reversed), and <em>search</em> (which returns the position of a specific value in the list. Assume the first node is position 0. If the items is not found, then return a -1 which will tell the calling function that that value does not exist)

<u>High level validation</u>

Numerical data input from the user should be validated before sending to the mutator function. While a non-integer is entered, display error and get data.

<u>Low level validation</u>

Mutator functions which are told to access a node that doesn’t exist should return a -1 so that the calling function can handle the problem.

menu-driven program to demonstrate your linked list capabilities. Make sure that you have proper constructors and destructors (a destructor must delete every node). Make your input and output professional. Break your code down into functions so as to maintain modular design. No global variables.

Demo your program as follows:

append node

append node

append node

append node

append node

print list

insert at position

print list

delete at position

print list

reverse

print list

search list

—————

int displayMenu()

{

cout &lt;&lt; ” n” &lt;&lt; endl;

cout &lt;&lt; “**********************************MENU*************************” &lt;&lt; endl;

cout &lt;&lt; “* 1) Append Node                                             *” &lt;&lt; endl;

cout &lt;&lt; “* 2) Insert at Position                                      *” &lt;&lt; endl;

cout &lt;&lt; “* 3) Delete at Position                                      *” &lt;&lt; endl;

cout &lt;&lt; “* 4) Print List                                              *” &lt;&lt; endl;

cout &lt;&lt; “* 5) Reverse List                                            *” &lt;&lt; endl;

cout &lt;&lt; “* 6) Search List                                             *” &lt;&lt; endl;

cout &lt;&lt; “* 7) End Program                                             *n” &lt;&lt; endl;