1. the second element to the last element.
2. For each element at index `i`, the algorithm picks the current element (`currentElement`) and starts a loop (`j`) to compare it with the elements to its left (elements at indices `j - 1`).
3. The inner loop (`j`) continues as long as `j` is greater than 0 and the element at `arr[j - 1]` is greater than `currentElement`. This loop helps to find the correct position for `currentElement` within the sorted sequence.
4. Inside the inner loop, the algorithm shifts the larger elements to the right (`arr[j] = arr[j - 1]`) until it finds the correct position for `currentElement`.
5. Once the correct position is found (`j` reaches the correct index), the algorithm places `currentElement` at that position (`arr[j] = currentElement`).

Here's the JavaScript implementation of the insertion sort algorithm using two counters:
