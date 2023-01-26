# Personal profile of software engineering skills

⬜ Optional, 🟦 Required for all, 🟨 Required for js, 🟩 Learned, 🟥 Declined

## Fundamental concepts

<div align="center">

| Syntax               | Statements            | Functions             | Data structures     | Process & style      |
|----------------------|-----------------------|-----------------------|---------------------|----------------------|
| 🟩 value             | 🟩 if                 | 🟩 recursion          | 🟩 array            | 🟩 refactoring       |
| 🟩 identifier        | 🟩 loops              | 🟩 function           | 🟩 instance         | 🟩 code review       |
| 🟩 variable          | 🟩 assignment         | 🟩 return             | 🟩 object           | 🟩 antipatterns      |
| 🟩 constant          | 🟩 prototype          | 🟦 signature          | 🟩 collection       | 🟩 paradigm          |
| 🟩 scalar            | 🟩 class              | 🟩 argument           | 🟩 hash table       | 🟩 algorithm         |
| 🟩 literal           | 🟩 while              | 🟩 parameter          | 🟩 linked list      | 🟩 magic numbers     |
| 🟩 expression        | 🟩 do..while          | 🟩 pure function      | 🟩 queue            | 🟩 hardcode          |
| 🟩 heap              | 🟩 for                | 🟩 lambda             | 🟩 stack            | 🟩 complexity        |
| 🟩 type              | 🟩 for..in            | 🟩 side effects       | 🟩 deque            | 🟩 decomposition     |
| 🟩 primitive types   | 🟩 for..of            | 🟩 closure            | 🟩 serialization    | 🟩 spaghetti         |
| 🟩 reference         | 🟨 for await          | 🟩 partial            | 🟩 mixin, extend    | 🟩 silver bullet     |
| 🟩 flag              | 🟩 throw              | 🟩 curry              | 🟩 iterator         | ⬜️ not invented here |
| 🟩 lexical scope     | 🟩 try..catch         | 🟩 chaining           | 🟩 typed arrays     | 🟩 dead code         |
| 🟩 code block        | 🟩 equality operators | 🟩 higher order       | 🟩 Map              | 🟩 unreachable code  |
| 🟩 Object            | 🟩 logical operators  | 🟩 callback           | 🟩 Set              | 🟩 duplicate code    |
| 🟩 this              | 🟩 bitwise operators  | 🟩 listener           | 🟩 weak collections | 🟩 exception         |
| 🟩 arrow function    | 🟩 break, continue    | 🟩 pipe               | 🟩 Proxy            | 🟩 return early      |
| 🟨 generator         | 🟩 switch             | 🟩 compose            | 🟩 Symbol           | 🟩 linter            |
| 🟩 async function    | 🟩 new Error          | 🟩 memoize            | 🟩 string parsing   | ⬜️ prettier          |
| 🟩 call, bind, apply |                       | 🟩 factory            | 🟩 timers           | 🟩 unittest          |
| 🟩 Array             |                       | 🟦 pool               | 🟩 EventEmitter     | 🟩 git               |
| 🟩 instanceof        |                       | 🟩 wrapper            | 🟨 RegExp           | 🟩 github            |
| 🟩 ...spread         |                       | 🟩 default parameters | 🟩 global           | 🟩 node.js           |
| 🟩 ...rest           |                       |                       | 🟩 undefined        | 🟩 npm               |
| 🟩 typeof            |                       |                       | 🟩 null(nil)        | 🟩 yarn               |
|                      |                       |                       | 🟩 optional             | 🟩 postman             |

</div>

## Multi-paradigm programming

<div align="center">

| Theory                         | OOP basics            | Abstractions         | 
|--------------------------------|-----------------------|----------------------|
| 🟩 Procedural programming      | 🟩 constructor        | 🟩 struct, record    | 
| 🟩 Imperative programming      | 🟩 new                | 🟩 Mutable state     | 
| 🟦 Structured programming      | 🟩 Static method      | 🟩 Immutable state   | 
| 🟦 Non-structured programming  | 🟩 Method             | 🟩 Enum              |  
| 🟩 Functional programming      | 🟦 Async method       | 🟩 Linked list       |                         
| 🟦 Prototype-based programming | 🟩 Getters, Setters   | 🟩 Doubly list       |                  
| 🟩 Object-oriented programming | 🟩 Public fields      | 🟦 Unrolled list     |                        
| ⬜ Object-based programming    | 🟩 Private fields     | 🟦 Circular list     |             
| 🟩 Generic programming         | 🟩 Field declarations | 🟩 Trees             |                          
| 🟩 Concurrent computing        | 🟩 Inheritance        | 🟩 Graphs            |                          
| 🟩 Asyncronous programming     | 🟩 Parent class       | 🟩 Functor           |                          
| 🟩 Parallel programming        | 🟩 Polymorphism       | 🟩 Functional object |                          
| 🟩 Reactive programming        | 🟩 Abstract class     | 🟩 Monad             |                          
| ⬜ FRP (Functional-reactive)   | 🟩 Interface          | 🟦 Generator         |                          
| 🟦 Automata-based programming  | 🟩 Encapsulation      | 🟩 Iterator          |                          
| 🟦 Domain-specific languages   | ⬜ Hidden class       | 🟩 Async Iterator    |                          
| 🟩 Multi-paradigm programming  | ⬜ Object form        |                      |                          
| ⬜ Metaprogramming             | 🟩 instance           |                      |                          
| ⬜ Actor model                 | ⬜ Introspection      |                      |                          
|                                | ⬜ Reflection         |                      |          
|                                | 🟩 SOLID         |                      |
|                                | 🟩 GRASP         |                      |

  

</div>

## Asynchronous programming

<div align="center">

| Async contracts        | JavaScript & Node.js specific  | Theory              | Techniques               |
|------------------------|--------------------------------|---------------------|--------------------------|
| 🟦 Callback-last       | 🟩 Timers                      | 🟩 Event Loop       | ⬜ async.js library      |
| 🟦 Error-first         | 🟩 setImmediate                | 🟩 Async error      | ⬜ Async composition     |
| 🟩 Promise             | 🟦 nextTick                    | 🟩 try..catch       | ⬜ Rx.js                 |
| 🟩 Async function      | ⬜ AbortController             | 🟩 Non-blocking     | 🟩 Sequential async      |
| 🟩 await               | 🟦 Promise unhandled rejection | 🟩 Async I/O        | 🟦 Parallel async        |
| 🟩 Generator           | 🟦 Promise double resolve      | 🟦 Pattern Reactor  | 🟩 Promise.all           |
| 🟩 Async Generator     | 🟩 child_process               | ⬜ CAS operations   | 🟦 Promise.allSettled    |
| 🟩 Async Iterator      | 🟩 worker_threads              | ⬜ epoll            | 🟦 Promise.race          |
| 🟩 Thenable            | 🟦 Atomics                     | ⬜ kqueue           | 🟦 Promise.any           |
| 🟩 EventEmitter        | 🟦 Blockeing operations        | ⬜ Completion ports | ⬜ Web Locks API         |
| ⬜ Cancelable callback | 🟦 Non-blocking loop for Array | ⬜ Event ports      | ⬜ Async Pool            |
| ⬜ Cancelable Promise  | ⬜ High resolution clock       | 🟩 libuv            | ⬜ Thread Pool           |
| 🟩 Asynchronous Queue  | 🟩 Callback hell               | 🟩 Race conditions  | 🟩 callbackify           |
| 🟩 Future              | 🟩 Promise hell                | 🟩 Dead locks       | 🟦 promisify             |
| ⬜ Deferred            |                                | 🟩 Live locks       | ⬜ IPC                   |
| 🟩 Observer            |                                | 🟩 Actor Model      | ⬜ Channel API           |
| ⬜ Async Collector     |                                |                     | ⬜ Revealing Constructor |
| ⬜ Coroutine           |                                |                     |                          |

</div>
  
## Swift/iOS


<div align="center">
  
| Memory management    | Design patterns         | Multithreading and concurrency | Data storage     | Requests and APIs | Main frameworks           |
|----------------------|-------------------------|--------------------------------|------------------|-------------------|---------------------------|
| 🟩 Stack and Heap     | 🟩 MVC, MVP, MVVM, VIPER | 🟩 POSIX                        | 🟩 NSUserDefaults | 🟩 REST API        | 🟩 UIkit                   |
| 🟩 Value              | 🟩 Abstract Factory      | 🟩 NSThreads                    | 🟩 Core Data      | 🟩 GraphQL         | 🟩 SwiftUI                 |
| 🟩 Reference type     | 🟩 Builder               | 🟩 Perform selector family      | 🟩 KeyChain       | 🟩 JSON            | 🟦 Vapor                   |
| 🟩 MRC                | 🟩 Factory Method        | 🟩 GCD                          | 🟩 Plist          | 🟩 WebSocket       | 🟩 Alamofire               |
| 🟩 ARC                | 🟩 Singleton             | 🟩 NSOperation(Queue)           | 🟩 Disk storage   | 🟩 WebRTC          | 🟩 Starscream              |
| 🟩 Weak references    | 🟦 DDD        | 🟩 Runloop                      | 🟩 CloudKit       | 🟩 XML             | 🟩 Socket.io(Client Swift) |
| 🟩 Retain cycles      | 🟩 Redux                 | 🟩 Race condition               | 🟩 SQLite         | 🟩 Codable         | 🟦 Quick                   |
| 🟩 Garbage collection | 🟩 Decorator             | 🟩 Readers–writers problem      | 🟩 Realm          | 🟦 Protobuf        | 🟩 Foundation              |
| 🟩 Memory leaks       | 🟩 Facade                |                                | 🟩 Firebase       |                   |                           |
| 🟩 Shallow copying    | 🟩 Adapter               |                                |                  |                   |                           |
| 🟩 Deep copying       | 🟩 Iterator              |                                |                  |                   |                           |
| 🟩 Autorelease pool   | 🟩 Strategy              |                                |                  |                   |                           |
|                      | 🟩 Command               |                                |                  |                   |                           |
|                      | 🟩 Prototype             |                                |                  |                   |                           |
|                      | 
</div>


