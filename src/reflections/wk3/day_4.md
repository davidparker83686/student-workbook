# Day 4 - WORKING IN MVC WITH COMPLEX DATA, ARRAY METHODS

Read Advancing with JS > The Observer Pattern and answer the following questions


### What problems does the Observer Pattern seek to solve?
```
The need to update a page using the same data for which the code for can get very dense and cluttered. 
```
### What are the three mechanisms of the observer pattern?
```
The Subscribe, The Unsubscribe, and The Broadcast Method
```

### Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
```
The use of proxy allows us to mess with the appstate in the service part of our template. the observer waits for changes to excute on our object then preforms an action, in our case its been draw() resulting in a change to our dom.
```



afternoon challenge link-https://davidparker83686.github.io/sporting_goods/