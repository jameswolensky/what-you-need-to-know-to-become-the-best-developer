### SOLID
- (S)ingle Responsibility Principle
A function or class should only be responsible for one thing

- (O)pen Closed Principle
A function or class should be open for extension but closed for modification

- (L)iskov Substitution Principle
A child class should be able to replace its parent class

- (I)nterface Segregation Principle
Classes should only be forced to implement the methods they need

- (D)ependency Inversion Principle
High-level modules (a module that requires other modules to function) should not implement low-level modules (a specific, single-purpose module) directly, but instead the high-level modules should use an abstraction (A high-level module shouldn't implement Stripe directly - it should implement a generic, abstract PaymentProcessor class instead)

### ACID
- (A)tomicity
All data changes are made as if they were a single operation

- (C)onsistency
Data remains consistent throughout the transaction

- (I)solation
Transactions are "invisible" to other transactions

- (D)urability
When the transaction completes, in the event of an error or system failure, the changes to the data remain intact
