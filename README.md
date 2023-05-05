Download Link: https://assignmentchef.com/product/solved-cse222_505-assignment-3
<br>
In this homework, reuse the same scenario of Homework 1 and implement the same system using several implementations of the List abstract data structure.

<ul>

 <li>You should complete the ArrayList and LinkedList implementations in the textbook.</li>

 <li>You should implement a HybridList class that keeps a LinkedList as a component and the elements stored in the LinkedList are ArrayLists. The number of elements in each ArrayList should be less than MAX_NUMBER. When the number of elements in an ArrayList exceeds MAX_NUMBER a new ArrayList should be generated in the LinkedList. When there is no element in an ArrayList it should be removed from the LinkedList.</li>

</ul>

Use

<ul>

 <li>LinkedList in the textbook for information about branches</li>

 <li>ArrayList in the textbook for users of the automation system</li>

 <li>HybridList you implemented for the furnitures <strong><u>PART 2:</u></strong></li>

</ul>

Analyze the time complexity (in most appropriate asymptotic notation) of all methods in your implementation of automation system for this homework. Attach the code just before its analysis.




<strong>RESTRICTIONS: </strong>

<ul>

 <li>Use ArrayList and LinkedList</li>

 <li>Can be only one main class in project</li>

 <li>Don’t use any other third part library</li>

</ul>

<strong>GENERAL RULES: </strong>

<ul>

 <li>For any question firstly use course news forum in Moodle, and then the contact TA.</li>

 <li>You can submit assignment one day late and will be evaluated over sixty percent (%60).</li>

</ul>

<strong>TECHNICAL RULES: </strong>

<ul>

 <li>You must write a driver function that demonstrates all possible actions in your homework. For example, if you are asked to implement an array list and perform an iterative search on the list then, you must at least provide the following in the driver function:

  <ul>

   <li>Create an array list and add items to the list. Append items to head, tail, and <em>k<sup>th</sup></em> index of the list.</li>

   <li>Perform at least two different searches by using two items in the list and print the index of the items.</li>

   <li>Perform another search with an item that isn’t in the array list and inform the user that the item doesn’t exist in the array list.</li>

   <li>Delete an existing item from the list and repeat the searches.</li>

   <li>Try to delete an item that is not on the array list and throw an exception for this situation.</li>

  </ul></li>

</ul>

The driver function should run when the code file is executed.

<ul>

 <li>Implement <a href="https://www.google.com.tr/search?q=clean+code+standart&amp;oq=clean+code+standart&amp;aqs=chrome..69i57j0.3015j0j4&amp;sourceid=chrome&amp;es_sm=122&amp;ie=UTF-8">clean code standards</a> in your code; o Classes, methods and variables names must be meaningful and related with the functionality.

  <ul>

   <li>Your functions and classes must be simple, general, reusable and focus on one topic. o Use standard <a href="https://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html">java code name conventions</a><a href="https://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html">.</a></li>

  </ul></li>

</ul>