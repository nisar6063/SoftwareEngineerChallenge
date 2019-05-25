# SoftwareEngineerChallenge

For developing an Immutable queue, I have used two stacks - forward & backward. This is like implementing a queue using two stacks.

## Enqueue
It creates a new instance using forward & backward(pushes new entry to backward)
## Dequeue
Removes the element from the forward stack & then creates a new instance and returns it.
          If both forward & backward stacks are empty then returns empty queue.
          If forward is empty & backward not empty, then it creates a new instance by reversing backward
## Head
It returns the top from forward stack.
## isEmpty
Both forward and backward has to be empty for queue to be empty.