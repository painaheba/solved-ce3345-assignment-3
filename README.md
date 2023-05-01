Download Link: https://assignmentchef.com/product/solved-ce3345-assignment-3
<br>
<ol>

 <li>Write pseudocode to swap two adjacent elements by adjusting only the links (and not the data) using [10 Points]

  <ol>

   <li>Singly linked list</li>

   <li>Doubly linked list</li>

  </ol></li>

</ol>

<strong> </strong>

<ol start="2">

 <li>Write pseudocode to implement the contains routine for MyLinkedList [5 Points]</li>

</ol>







<ol start="3">

 <li>The Josephus problem is the following game: N people, numbered 1 to N, are sitting in a circle. Starting at person 1, a hot potato is passed. After M passes, the person holding the potato is eliminated, the circle closes ranks, and the game continues with the person who was sitting after the eliminated person picking up the hot potato. The last remaining person wins. Thus if M =0 and N=5, players are eliminated in order and player 5 wins. If M=1 and N=5, the order of elimination is 2,4,1,5.

  <ol>

   <li>Write a program to solve the Josephus problem for general (integer) values of M and N.</li>

  </ol></li>

</ol>

Try to make your program as efficient as possible. Make sure you dispose of cells.

[7 Points]

<ol>

 <li>What is the running time of your program?</li>

</ol>

[3 Points]







<ol start="4">

 <li>What is the running time of the following code? [5 Points] public static List&lt;Integer&gt; makeList( int N)</li>

</ol>

{

ArrayList&lt;Integer&gt; lst = new ArrayList&lt;&gt;();      for( inti  =0; i &lt; N; i++)

{

lst.add(i);          lst.trimToSize();

}

}













<ol start="5">

 <li>The following routine removes the first half of the list passed as a parameter: [10 Points]</li>

</ol>

public static void removeFirstHalf(List&lt;?&gt; lst)

{     int theSize = lst.size() /2      for( inti =0; i &lt; theSize; i++ )

lst.remove(0);

}

<ol>

 <li>Why is theSize saved prior to entering the for loop?</li>

 <li>What is the running time of removeFirstHalf if lst is an ArrayList?</li>

 <li>What is the running time of removeFirstHalf if lst is a LinkedLIst?</li>

 <li>Does using an iterator make removeFirstHalf faster for either type of List</li>

 <li>Write a function in pseudocode named removeDuplicates(), which takes a singly linked list sorted in increasing order and deletes any duplicate nodes from the list. The list should only be traversed once and the routine should not call any other routine.</li>

</ol>

For example if the linked list is 11-&gt;11-&gt;11-&gt;21-&gt;43-&gt;43-&gt;60 then removeDuplicates() should convert the list to 11-&gt;21-&gt;43-&gt;60.

<strong>Input:</strong> the <strong>head</strong>  node of the  linked list  .

<strong>Output:</strong>

Your function should return a pointer to the head of linked list with no duplicate element. [10 Points]