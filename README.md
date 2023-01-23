<h1> 0x1B. C - Sorting algorithms & Big O </h1>

<h2 dir="auto"><a id="user-content-tasks-page_with_curl" class="anchor" aria-hidden="true" href="#tasks-page_with_curl"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Tasks <g-emoji class="g-emoji" alias="page_with_curl" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4c3.png">📃</g-emoji></h2>
<ul dir="auto">
<li>
<p dir="auto"><strong>0. Bubble sort</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/0-bubble_sort.c">0-bubble_sort.c</a>: C function that sorts an array of integers
in ascending order using the Bubble Sort algorithm.</li>
<li>Prints the array after each swap.</li>
<li><a href="/mumbuamutuku/sorting_algorithms/0-O">0-O</a>: Text file containing the best, average, and worst case time
complexities of the Bubble Sort algorithm, one per line.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>1. Insertion sort</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/1-insertion_sort_list.c">1-insertion_sort_list.c</a>: C function that sorts a
<code>listint_t</code> doubly-linked list of integers in ascending order using the
Insertion Sort algorithm.</li>
<li>Prints the list after each swap.</li>
<li><a href="/mumbuamutuku/sorting_algorithms/1-O">1-O</a>: Text file containing the best, average, and worst case time
complexities of the Insertion Sort algorithm, one per line.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>2. Selection sort</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/2-selection_sort.c">2-selection_sort.c</a>: C function that sorts an array of
integers in ascending order using the Selection Sort algorithm.</li>
<li>Prints the array after each swap.</li>
<li><a href="/mumbuamutuku/sorting_algorithms/2-O">2-O</a>: Text file containing the best, average, and worst case time
complexities of the Selection Sort algorithm, one per line.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>3. Quick sort</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/3-quick_sort.c">3-quick_sort.c</a>: C function that sorts an array of
integers in ascending order using the Quick Sort algorithm.</li>
<li>Implements the Lomuto partition scheme.</li>
<li>Always uses the last element of the partition being sorted as the pivot.</li>
<li>Prints the array after each swap.</li>
<li><a href="/mumbuamutuku/sorting_algorithms/3-O">3-O</a>: Text file containing the best, average, and worst case time
complexities of the Quick Sort Lomuto Partition scheme algorithm, one per line.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>4. Shell sort - Knuth Sequence</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/100-shell_sort.c">100-shell_sort.c</a>: C function that sorts an array of
integers in ascending order using the Shell sort algorithm.</li>
<li>Implements the Knuth interval sequence.</li>
<li>Prints the array each time the interval is decreased.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>5. Cocktail shaker sort</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/101-cocktail_sort_list.c">101-cocktail_sort_list.c</a>: C function that sorts
a <code>listint_t</code> doubly-linked list of integers in ascending order using the Cocktail Shaker
Sort algorithm.</li>
<li>Prints the list after each swap.</li>
<li><a href="/mumbuamutuku/sorting_algorithms/101-O">101-O</a>: Text file containing the best, average, and worst case time
complexities of the Cocktail Shaker Sort algorithm, one per line.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>6. Counting sort</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/102-counting_sort.c">102-counting_sort.c</a>: C function that sorts an array
of integers in ascending order using the Counting Sort algorithm.</li>
<li>Assumes that the array will only contain numbers <code>&gt;= 0</code>.</li>
<li>Prints the counting array after it has been initialized.</li>
<li><a href="/mumbuamutuku/sorting_algorithms/102-O">102-O</a>: Text file containing the best, average, and worst case time
complexities of the Counting Sort algorithm, one per line.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>7. Merge sort</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/103-merge_sort.c">103-merge_sort.c</a>: C function that sorts an array of integers in
ascending order using the Merge Sort algorithm.</li>
<li>Implements the <code>top-down</code> Merge Sort algorithm.
<ul dir="auto">
<li>When an array is divided, the size of the left subarray is always less than
or equal to the size of the right subarray.</li>
<li>Always sorts the left subarray before the right one.</li>
</ul>
</li>
<li>Prints subarrays each time they are merged.</li>
<li><a href="/mumbuamutuku/sorting_algorithms/103-O">103-O</a>: Text file containing the best, average, and worst case time
complexities of the Merge Sort algorithm, one per line.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>8. Heap sort</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/104-heap_sort.c">104-heap_sort.c</a>: C function that sorts an array of integers
in ascending order using the Heap Sort algorithm.</li>
<li>Implements the <code>sift-down</code> Heap Sort algorithm.</li>
<li>Prints the array after each swap.</li>
<li><a href="/mumbuamutuku/sorting_algorithms/104-O">104-O</a>: Text file containing the best, average, and worst case time
complexiites of the Heap Sort algorithm, one per line.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>9. Radix sort</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/105-radix_sort.c">105-radix_sort.c</a>: C function that sorts an array of
integers in ascending order using the Radix Sort algorithm.</li>
<li>Implements the Least-Significant-Digit (LSD) Radix Sort algorithm.</li>
<li>Assumes that the array will only contain numbers <code>&gt;= 0</code>.</li>
<li>Prints the array for each significant digit increase.</li>
<li><a href="/mumbuamutuku/sorting_algorithms/105-O">105-O</a>: Text file containing the best, average, and worst case time
complexities of the Radix Sort algorithm, one per line.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>10. Bitonic sort</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/106-bitonic_sort.c">106-bitonic_sort.c</a>: C function that sorts an array of integers
in ascending order using the Bitonic Sort algorithm.</li>
<li>Assumes that <code>size</code> is a power of 2 (ie. <code>size</code> can be expressed as <code>2^k</code>
where <code>k &gt;= 0</code>).</li>
<li>Prints subarrays each time they are merged.</li>
<li><a href="/mumbuamutuku/sorting_algorithms/106-O">106-O</a>: Text file containing the best, average, and worst case time
complexities of the Bitonic Sort algorithm, one per line.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>11. Quick Sort - Hoare Partition scheme</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/107-quick_sort_hoare.c">107-quick_sort_hoare.c</a>: C function that sorts an array
of integers in ascending order using the Quick Sort algorithm.</li>
<li>Implements the Hoare partition scheme.</li>
<li>Always uses the last elemement of the partition being sorted as the pivot.</li>
<li>Prints the array after each swap.</li>
<li><a href="/mumbuamutuku/sorting_algorithms/107-O">107-O</a>: Text file containing the best, average, and worst case time
complexities of the Quick Sort Hoare Partition cheme algorithm, one per line.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>12. Dealer</strong></p>
<ul dir="auto">
<li><a href="/mumbuamutuku/sorting_algorithms/1000-sort_deck.c">1000-sort_deck.c</a>: C function that sorts a <code>deck_node_t</code>
doubly-linked list deck of cards.</li>
<li>Assumes that there are exactly <code>52</code> elements in the doubly-linked list.</li>
<li>Orders the deck from spades to diamonds and from aces to kings.</li>
</ul>
</li>
</ul>
</article>
          </div>