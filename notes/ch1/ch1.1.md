### Chapter 1.1

- When you have to add a feature to a program but the code is not structured in a convenient way, first refactor the program to make it easy to add the feature, then add the feature.
- Before you start refactoring, make sure you have a solid suite of tests. These tests must be self-checking.
- The essence of the refactoring process: small changes and testing after each change. Refactoring changes the programs in small steps, so if you make a mistake, it is easy to find where the bug is.
- Commit after each successful refactoring, so you can easily get back to a working state should you mess up later
- Default name for a parameter includes the type name. He uses an indefinite article with it unless there is some specific role information to capture in the name. He learned this convention from Kent Beck [Beck SBPP] and continue to find it helpful.
- Any fool can write code that a computer can understand. Good programmers write code that humans can understand.
- Good code should clearly communicate what it is doing, and variable names are a key to clear code. Never be afraid to change names to improve clarity.
- Temporary variables create a lot of locally scoped names that complicate extractions. The great benefit of removing local variables is that it makes it much easier to do extractions, since there is less local scope to deal with

