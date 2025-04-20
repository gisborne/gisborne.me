Let me discuss something around security, then generalise the observation.

I will first argue that authorisation should be a First Order Theory.

Meaning it can be implemented using a relational query. I should be able to represent all the information I need about my security requirements in a set of tables with regular values, and I should be able to answer any authorisation question I have using a simple database query.

You might have a table of named privileges. A table of users. A table of user groups. Tables that represent relationships such as “inherits”.

Note here that I’m imagining using something like Datalog, not vanilla SQL. So I can trivially query a recursive relationship without requiring something Turing complete and awful, like recursive Common Table Expressions. Shudder.

Because this is a FOT, I have computability guarantees, and I have known efficient algorithms and data structures for implement this, at any scale.

# So what?

I’ve not dealt with any security requirements that I can’t implement this way.

I *might* have some aspect of security I need to implement in a programming language. Encryption or signing calculations. But those can be presented as functions callable from the query language and will be very self-contained.