Generate image from `.plantuml` files:
```
$ cat diagrams/tasks/use-case.plantuml | java -jar ~/Programs/plantuml.jar -p > diagrams/tasks/use-case.png
$ cat diagrams/tasks/sequence.plantuml | java -jar ~/Programs/plantuml.jar -p > diagrams/tasks/sequence.png
```
