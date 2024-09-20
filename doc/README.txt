TestIterator.java questions
	Using a linked list would create faster insertion and removal times, but slower retrieval times
    When using an ArrayList TestIterator runs at a time of 66 ms whereas running TestIterator with a LinkedList runs at a time of 21 ms

	When you use list.remove(Integer.valueOf(77)) it would only remove one of the values of 77 not all of them versus using i.remove()
TestList.java questions
	using a linked list the code compiles in 6 ms using ArrayList the code runs in 7 ms minor difference
	list.remove(5) removes the 5th index of the arraylist whereas list.remove(Integer.valueOf(5)) removes the index that holds the value of five


TestPerformance
	Base speed for LinkedList AddRemove: 22 ms Access: 10 ms
	Base speed for ArrayList AddRemove: 184 ms Access :12 ms

	Size increased to 100 LinkedList AddRemove: 22 ms Access: 21 ms
	Size increased to 100 ArrayList AddRemove: 190 ms Access: 13 ms
	
	Size increased to 1000 LinkedList AddRemove: 23 ms Access: 241 ms
	Size increased to 1000 ArrayList AddRemove: 289 ms Access: 14 ms

	Size increased to 10000 LinkedList AddRemove: 84 ms Access: 7 sec 784 ms
    Size increased to 10000 ArrayList AddRemove:  73 ms Access: 2 sec 640 ms

	Arraylists preforms better as the size increases past a certain point. therefore I would choses an arraylist if I was not working with a fixed data set
