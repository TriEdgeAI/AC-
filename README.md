# Anarcho-C++

## Classes
Classes are supported in Anarcho-C++, unlike in CCC++, however members of classes can only be either `private` or `protected`. The `public` keyword has been removed.

## Unions
Unions in Anarcho-C++ are deprecated, but the keyword is kept for compatibility reasons. That means that you will be able to declare a union, but it will not really do anything.

## Method Invocation
Invoking methods in Anarcho-C++ costs bitcoins, because if method invocation was free, programs would invoke them as much as they want without caring and that leads to programs getting stuck, lagspikes and so on. A special keyword "cost" is introduced, which is to be used in method declarations in order to specify how much bitcoins it costs to invoke the method. Example:

```cpp
void cost(0.001) bogosort(int arr[], int length)
{
	while(!is_sorted(arr, length))
	{
		shuffle(arr, length);
	}
}
```

Thus, when a program runs, it no longer measures in % of CPU usage, instead it measures in GDP.

![gdp](https://user-images.githubusercontent.com/12459664/30664964-2685e926-9e58-11e7-9270-c1d896392b8c.png)

## Type System
The type system consists of the following primitive types:
```cpp
int 	32-bit integer
short	16-bit integer
long	64-bit integer
float	32-bit floating point number
double	64-bit floating point number
money	128-bit fixed point number
```

## Memory Allocation & Cleanup
There is no imposed garbage-collector, instead you have to pay for one yourself if you want to have one, so programs that don't need garbage collection don't have to pay for it as well. Now you do not need to call `free()` on chunks of memory ever again, because in Anarcho-C++ memory is always free (as in "freedom", not as "free of charge").
You are not allowed to regulate how memory is allocated, because central planning is always bad. Instead, each object instance decides how much memory to use on it's own. You may argue that memory is a finite resource and without centralized memory allocation objects would hog up all of your memory for themselves and have a memory monopoly like Google Chrome. However, memory monopolies only exist because they of central memory allocation, which allows it. In a free market for memory, monopolies will be very rare.

## Pricing

|            | Self-Employed | Business | Corporate |
| ---------- |-------------- | -------- | --------- |
| Features   |               |          |           |
|            |               |          |           |
| Price&ast; | $99.99        | $299.99  | $899.99   |

&ast; All prices are per application and do not include VAT (Value Added Theft) enforced by your local violent gang/government.
