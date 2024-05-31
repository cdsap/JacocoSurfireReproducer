# Goal marked as not cacheable reproducer
In this project there are different test goals. The second goal is marked as not cacheable:
```
Goal execution marked as not cacheable: Build caching was not enabled for this goal execution because pre-existing files were modified.
Cacheable goals may only create new files.
```
Checking the logs:
```
[DEBUG] The following output files existed before execution of this goal and were also modified during the execution of the goal:
- /example-jacoco/target/jacoco.exec

```
