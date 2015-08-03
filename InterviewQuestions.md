# Good Interview Questions for future reference

## 1. String VS StringBuilder?

System.String is an immutable object, it means whenever you modify its content it will allocate a new string and this takes time and memory. Using StringBuilder we can modify the actual content of the object without allocating a new one.

So use StringBuilder when you need to do many modifications on the string.

