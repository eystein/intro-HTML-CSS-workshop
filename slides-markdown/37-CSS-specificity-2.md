# Conflicting rules

a.k.a. Why is my CSS not working?!

## Reason #2: Specificity

The types of selectors have different levels of importance assigned to them:

* ID - **Most important**
* Class
* Element - **Least important**


```
     Element 0-0-0-0-1
       Class 0-0-0-1-0
          ID 0-0-1-0-0

Inline style 0-1-0-0-0
!important   1-0-0-0-0
```
