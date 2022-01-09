# Placeholder to keep adding my technical knowledge and notes I gather

**Design Patterns:**

**Creational Design Patterns:**

  **1. Singleton:**

      Singleton is a creational design pattern, which ensures that only one object of its kind exists and provides a single point of access to it for any other code.

      Singleton has almost the same pros and cons as global variables. Although they’re super-handy, they break the modularity of your code.

      You can’t just use a class that depends on Singleton in some other context. You’ll have to carry the Singleton class as well. Most of the time, this limitation comes up during the creation of unit tests.

      There are many ways to create singleton in Java. The following article shows on different ways to create it.

      https://www.journaldev.com/1377/java-singleton-design-pattern-best-practices-examples

  **2. Factory:**

