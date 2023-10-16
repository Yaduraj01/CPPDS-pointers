# CPPDS-pointers
##Abstract
Pointers in C++ are variables that store memory addresses. They allow you to work directly with memory and data, including dynamic memory allocation. You can access and modify data at specific memory locations, but they require careful handling to avoid errors like memory leaks and segmentation faults.
In the given codes we have demonstrated these things.

##Algorithm - Code 1
Here's an algorithm for your C++ code that demonstrates the use of pointers:
1. Declare integer variable `i`, floating-point variable `fl`, and pointers `int_ptr` (integer pointer), `flt_ptr` (float pointer), and `chr_ptr` (character pointer).
2. Assign the value `5` to `i`.
3. Assign the value `3.4` to `fl`.
4. Set the integer pointer `int_ptr` to point to the memory address of `i` using the address-of operator (`&`).
5. Print the value pointed to by `int_ptr` using `*int_ptr`.
6. Print the memory address of `i` using `&i`.
7. Print the value stored in `int_ptr`, which represents the memory address of `i`.

##Algorithm - Code 2
Certainly, here's a more detailed algorithm for your C++ code that uses a "call by value" approach to swap two variables:
1. Declare two integer variables `i` and `j`.
2. Assign the value `2` to `i` and `3` to `j`.
3. Display the values of `i` and `j before swapping to the user.
4. Call the `swap` function, passing the memory addresses (pointers) of `i` and `j`.
5. Inside the `swap` function:
    a. Declare an integer variable `tmp` to temporarily hold a value.
    b. Store the value pointed to by `m` (which is the memory address of `i`) in `tmp`. This effectively copies the value of `i` to `tmp`.
    c. Update the value pointed to by `m` (the memory address of `i`) with the value pointed to by `n` (the memory address of `j`). This assigns the value of `j` to `i`.
    d. Update the value pointed to by `n` (the memory address of `j`) with the value stored in `tmp`. This assigns the original value of `i` (stored in `tmp`) to `j`.
6. Return from the `swap` function.
7. Display the values of `i` and `j after swapping to the user.


