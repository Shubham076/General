
1.  **Mutex (Lock)**
    
    -   **Purpose**: A mutex is used to provide mutual exclusion, ensuring that only one thread can access a particular piece of code or data at any given time.
    -   **Behavior**: When a thread acquires a mutex, no other thread can enter the critical section (the part of the program that the mutex protects) until the mutex is released by the owning thread.
    -   **Use Case**: Best suited for situations where you need to protect shared resources or critical sections to ensure that only one thread can access them at a time.
2.  **Semaphore**
    
    -   **Purpose**: Semaphores are more general than mutexes and can be used to control access to a pool of resources, not just a single resource like a mutex.
    -   **Behavior**: A semaphore has a counter which is decremented when a thread acquires the semaphore and incremented when a thread releases the semaphore. If a thread tries to acquire the semaphore and the counter is zero (meaning no resources are available), the thread will block until a resource becomes available.
    -   **Use Case**: Semaphores are useful when you need to control access to a set of resources (like a pool of connections) where the resources are limited but more than one.
