# Conflicting rules

a.k.a. Why is my CSS not working?!

## Reason #2: Specificity

### Calculating specificity

Adding more selectors increases the priority of the selector rule.

```
 .banner .sale .clearance p { }   0-0-0-3-1
            header .title p { }   0-0-0-1-2
.footer .note .meta .social { }   0-0-0-4-0
          .social { !important}   1-0-0-1-0  
```
