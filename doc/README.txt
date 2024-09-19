TestIterator.java questions
	Using a linked list would create faster insertion and removal times, but slower retrevial times

	When you use list.remove(Integer.valueOf(77)) it would only remove one of the values of 77 not all of them versus using i.remove()
TestList.java questions
	using a linked list the code compiles in 6 ms using ArrayList the code runs in 7 ms minor difference
	list.remove(5) removes the 5th index of the arraylist where as list.remove(Integer.valueOf(5)) removes the index that holds the value of five
TestPerformance
	Base speed for LinkedList AddRemove: 22 ms Access: 10 ms
	Base speed for ArrayList AddRemove: 184 ms Access :12 ms

	Size increased to 100 LinkedList AddRemove: 22 ms Access: 21 ms
	Size increased to 100 ArrayList AddRemove: 190 ms Access: 13 ms
	
	Size increased to 1000 LinkedList AddRemove: 23 ms Access: 241 ms
	Size increased to 1000 ArrayList AddRemove: 289 ms Access: 14 ms
	
	Arraylists have a better access preformance as they remain relatively constant when increasing size unlike LinkedLists 
	LinkedLists have a better AddRemove preformance as they remain relatively constant when increasing size unlike ArrayLists
	
