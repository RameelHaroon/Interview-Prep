
==Synchronous programming executes tasks sequentially, while asynchronous programming allows tasks to run independently and potentially concurrently==. Synchronous code blocks execution until a task completes, whereas asynchronous code can continue executing other tasks while waiting for the result of an asynchronous operation. Asynchronous programming is generally preferred for I/O-bound tasks like network requests or database queries, as it improves responsiveness and performance
Youtube: https://www.youtube.com/watch?v=Kpn2ajSa92c

### Async vs multithreading
==No, asynchronous programming and multithreading are distinct concepts==, although they are related and can be used together to achieve concurrency. Asynchronous programming focuses on non-blocking execution, allowing a program to continue working on other tasks while waiting for an operation to complete, while multithreading involves running multiple threads concurrently to utilize multiple CPU cores for parallel execution
https://www.baeldung.com/cs/async-vs-multi-threading