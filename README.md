# assignment2-Thakkallapally
Assignment-2
# Vikram Thakkallapally
###### New York
A little over **8 million people** live in **New York City**. That means 1 in every 38 people in the United States call the city home. More than 800 languages are spoken in New York City, making it the most linguistically diverse city in the world. ... New York City's **Federal Reserve Bank** has the **largest gold storage in the world**.
---
## My trip route map from Maryville to New York.
1. I've started intially from **Maryville** towards **Kansas International Airport**
2. Once I reached airport I've collected my boarding pass.
    1. Intial boarding pass was until Atlanta airport as my flying route to newyork is via **Atlanta**.
    2. I Finally collected my boarding pass for newyork after a 1hr flight time to Atlanta airport 
3. I reached New York from my starting point Maryville within a time span of 3hours.

## List of items that should be brought to New York for maximum enjoyment

* Rain Coat
* DSLR Camera
* Jacket
* Licence

[Direct link to know About Me](./AboutMe.md)
---
## Food,Drinks I would recommend someone to try
Below table lists out the food and drink items that I preferably recommend to anyone.Among all these items I loved Chicken Nuggets the most.
| Items | Available at | Price |
|------|----------|------|
| Pepperoni Pizza | Dominos | $15 |
| Frenchfries | McDonalds | $5 |
| Cold Coffee | StarBucks | $3 |
| Chicken Nuggets | KFC | $4 |
---
## Pithy Quotes that inspired me 
> Never write anything that does not give you great pleasure. Emotion is easily transferred from the     writer to the reader.   - *Joseph Joubert*

> It is perfectly okay to write garbage as long as you edit brilliantly.   - *C. J. Cherryh*

----
## Precise information about Data Structures
> A data structure is a particular way of organizing data in a computer so that it can be used effectively.
> For example, we can store a list of items having the same data-type using the array data structure.
[Quick-link for the source](https://www.geeksforgeeks.org/data-structures/)
## Sample code for deleting an element from the stack
```
stack<pair<int, int>> s1, s2;

if (s2.empty()) {
    while (!s1.empty()) {
        int element = s1.top().first;
        s1.pop();
        int minimum = s2.empty() ? element : min(element, s2.top().second);
        s2.push({element, minimum});
    }
}
int remove_element = s2.top().first;
s2.pop();

```
[Quick-link for the code source](https://cp-algorithms.com/data_structures/stack_queue_modification.html)

