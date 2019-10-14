# Conflicting rules

a.k.a. Why is my CSS not working?!

## Reason #2: Specificity

### ⚠️ `!important`

**Nuclear** option!!

Overrides everything.

Symptom of a problem with either the cascade or specificity in our stylesheet. 

```
     Element 0-0-0-0-1
       Class 0-0-0-1-0
          ID 0-0-1-0-0

Inline style 0-1-0-0-0
!important   1-0-0-0-0
```
