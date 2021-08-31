# Cash-Settlement

## What it does ?
<pre>It is a Web App that resolves the conflict which might occur when a group usually credits or debit some
amount of money with each other, forming a complex cyclic graph. It simplifies the cyclic graph into an
acyclic graph by storing each edge into a min-heap and maintaining net % credit or debit at each vertex.
</pre>

## How it works ?
<pre>The algorithm maintains two heaps ,one min heap and one max heap which contains the total amount 
(which is treated as an edge) of those who gave the cash and the ones who took the cash respectively.

After that we settle the amount by constantly popping the elements from both the heaps.
</pre>
