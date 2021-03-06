# Datastructure

## What is Data structure?
- Organising data in organised way. for example if you need cooper wire from store..if they are in messed up with other wires it will be very hard to find that.. but in our daily store they orgainsed in way..so that's data structure

## What is Alogithm?
- Set of rules to solve a problem
ex: for making a tea.. you have to put water, tea leaves, milk , sugar..and then put it on stove.. so these are set of rules to solve a problem.and here problem is to make a tea.

## Types of Data structure
[![](https://mermaid.ink/img/eyJjb2RlIjoiZ3JhcGggVERcbiAgICBBKERhdGFTdHJ1Y3R1cmUpIC0tPiBCKFByaW1pdGl2ZSBEYXRhIFN0cnVjdHVyZSlcbiAgICBBKERhdGFTdHJ1Y3R1cmUpIC0tPiBHKE5vbiBQcmltaXRpdmUgRGF0YSBTdHJ1Y3R1cmUpXG4gICAgQihQcmltaXRpdmUgRGF0YSBTdHJ1Y3R1cmUpIC0tPiBDKEludGVnZXIpXG4gICAgQihQcmltaXRpdmUgRGF0YSBTdHJ1Y3R1cmUpIC0tPiBEKEZsb2F0KVxuICAgIEIoUHJpbWl0aXZlIERhdGEgU3RydWN0dXJlKSAtLT4gRShDaGFyYWN0ZXIpXG4gICAgQihQcmltaXRpdmUgRGF0YSBTdHJ1Y3R1cmUpIC0tPiBGKEJvb2xlYW4pXG4gICAgRyhOb24gUHJpbWl0aXZlIERhdGEgU3RydWN0dXJlKSAtLT4gSChMaW5lYXIgRGF0YSBTdHJ1Y3R1cmUpXG4gICAgRyhOb24gUHJpbWl0aXZlIERhdGEgU3RydWN0dXJlKSAtLT4gSShOb24tTGluZWFyIERhdGEgU3RydWN0dXJlKVxuICAgIEgoTGluZWFyIERhdGEgU3RydWN0dXJlKSAtLT4gSihBcnJheSlcbiAgICBIKExpbmVhciBEYXRhIFN0cnVjdHVyZSkgLS0-IEsoTGlua2xpc3QpXG4gICAgSChMaW5lYXIgRGF0YSBTdHJ1Y3R1cmUpIC0tPiBMKFN0YWNrKVxuICAgIEgoTGluZWFyIERhdGEgU3RydWN0dXJlKSAtLT4gTShRdWV1ZSlcbiAgICBJKE5vbi1MaW5lYXIgRGF0YSBTdHJ1Y3R1cmUpIC0tPiBPKFRyZWUpXG4gICAgSShOb24tTGluZWFyIERhdGEgU3RydWN0dXJlKSAtLT4gUChHcmFwaCkiLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOmZhbHNlfQ)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbiAgICBBKERhdGFTdHJ1Y3R1cmUpIC0tPiBCKFByaW1pdGl2ZSBEYXRhIFN0cnVjdHVyZSlcbiAgICBBKERhdGFTdHJ1Y3R1cmUpIC0tPiBHKE5vbiBQcmltaXRpdmUgRGF0YSBTdHJ1Y3R1cmUpXG4gICAgQihQcmltaXRpdmUgRGF0YSBTdHJ1Y3R1cmUpIC0tPiBDKEludGVnZXIpXG4gICAgQihQcmltaXRpdmUgRGF0YSBTdHJ1Y3R1cmUpIC0tPiBEKEZsb2F0KVxuICAgIEIoUHJpbWl0aXZlIERhdGEgU3RydWN0dXJlKSAtLT4gRShDaGFyYWN0ZXIpXG4gICAgQihQcmltaXRpdmUgRGF0YSBTdHJ1Y3R1cmUpIC0tPiBGKEJvb2xlYW4pXG4gICAgRyhOb24gUHJpbWl0aXZlIERhdGEgU3RydWN0dXJlKSAtLT4gSChMaW5lYXIgRGF0YSBTdHJ1Y3R1cmUpXG4gICAgRyhOb24gUHJpbWl0aXZlIERhdGEgU3RydWN0dXJlKSAtLT4gSShOb24tTGluZWFyIERhdGEgU3RydWN0dXJlKVxuICAgIEgoTGluZWFyIERhdGEgU3RydWN0dXJlKSAtLT4gSihBcnJheSlcbiAgICBIKExpbmVhciBEYXRhIFN0cnVjdHVyZSkgLS0-IEsoTGlua2xpc3QpXG4gICAgSChMaW5lYXIgRGF0YSBTdHJ1Y3R1cmUpIC0tPiBMKFN0YWNrKVxuICAgIEgoTGluZWFyIERhdGEgU3RydWN0dXJlKSAtLT4gTShRdWV1ZSlcbiAgICBJKE5vbi1MaW5lYXIgRGF0YSBTdHJ1Y3R1cmUpIC0tPiBPKFRyZWUpXG4gICAgSShOb24tTGluZWFyIERhdGEgU3RydWN0dXJlKSAtLT4gUChHcmFwaCkiLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOmZhbHNlfQ)

## Recursion
calling same method again and again

ex. 
- finding factorial
- finding fibonacci

## comparision recursion and iteration
| Ways  | Recursion better  | Iteration better| Description |
| :------------: |:---------------:| :-----:| :-----:|
| Space Complexity     | No | Yes | Interally system is using stack as memory but for iteration we are using variables |
| Time Complexity     | No        | Yes | System is using stack in recursion so it will take time to push and pop |
| Ease of code (to solve subproblem) | Yes       |   No | When there is case when we can divide the problem in simlar problems then Recursion will help to divide in subproblems which is better approch |


## When to avoid and use Recursion
- When we can divide problem into simlar problems then we have to use recursion
- when there is no bound for time and space then we can use recursion. for example we have to program for air bag..in which case time is crucial point and another example embedded system where storage is important point.. so at these places we have to avoid using recursion

## Practical uses
- stack
- Tree - Traversal/Insertion/Deletion/Searching
- Sorting - Quick and Merge sort
- Divide and conqur
- Dynamic Programming and many more.
- 
