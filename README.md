# Builder Pattern Problem

__Problem Scenario__

Imagine you're developing an e-commerce application where customers create accounts with varying levels of detail.
Initially, you use a standard constructor for the User class:

![image](https://github.com/JamesManalili/BuilderPattern/assets/142465145/9ecd25e1-c4b6-4a2c-8b17-033e7b4ad431)

However, you encounter challenges:

- Registration forms: It's cumbersome to ensure users enter all fields in the correct order, leading to errors and frustration.
- Optional fields: Not all customers provide complete information, but the constructor forces them to.
- Data consistency: Changes to user profiles after registration can cause unexpected issues due to mutable fields.
- Implement solution using the Builder Pattern to address the issue.

# UML CLASS DIAGRAM

![BuilderPattern](https://github.com/JamesManalili/BuilderPattern/assets/142465145/e9b38d2d-09d6-4459-8375-5239da275b74)
