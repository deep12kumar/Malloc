# Malloc

As you know, an array is a collection of a fixed number of values. Once the size of an array is declared, you cannot change it.

Sometimes the size of the array you declared may be insufficient. To solve this issue, you can allocate memory manually during run-time. This is known as dynamic memory allocation in C programming.

To allocate memory dynamically, library functions are malloc() is used. These functions are defined in the <stdlib.h> header file.

malloc() The name "malloc" stands for memory allocation.

The malloc() function reserves a block of memory of the specified number of bytes. And, it returns a pointer of void which can be casted into pointers of any form.
![image](https://user-images.githubusercontent.com/125429608/234447867-c54264ae-b782-49dd-9331-4cd24171553a.png)
