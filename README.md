# assignment2-sukasi

# Sukasi Gopi Kishore

###### Hyderabad Biriyani

It is very famous in **India**. It is also known as **Hyderabadi dum**. It is originated from **Nizam of Hyderabad**.

---
### Directions To Hyderabad Biriyani
1. Take cab and go to kansas city
2. Get on I-29 N in Rock Port from MO-46 W, State Hwy J and US Hwy 136 W
3. Continue on I-29 N to Omaha. Take exit 445 from I-80 W
4. Follow NE-92 W/US-275 W to S 174th Plaza


### Menu
* India
    - North Thali
    - South Thali
    - Pappu
* Chinesse
    - Manchuria
    - Noodles
    - Snake Fry
* America
    - Pizza
    - Burger
    - Sandwich

**[Document](ABOUTME.md)

---
## FOOD RECOMMENDATIONS
Sport/Activity  | Location  |  Price 
---             | ---       | ---
Cricket         | India     | $ 100
Football        | US        | $ 50
Basketball      | Newyork   | $ 25

---

## Pithy Quotes
> "A dream is not that which you see while sleeping, it is something that does not let you sleep."
> - APJ ABDUL KALAM

> "Excellence happens not by accident. It is a process."
> - Sir C.V. RAMAN

---
## CODE FENCING
Given two non-negative integers  and , we have to find their GCD (greatest common divisor), i.e. the largest number which is a divisor of both  and . It's commonly denoted by . Mathematically it is defined as:

(here the symbol "" denotes divisibility, i.e. "" means " divides ")

When one of the numbers is zero, while the other is non-zero, their greatest common divisor, by definition, is the second number. When both numbers are zero, their greatest common divisor is undefined (it can be any arbitrarily large number), but we can define it to be zero. Which gives us a simple rule: if one of the numbers is zero, the greatest common divisor is the other number.

The Euclidean algorithm, discussed below, allows to find the greatest common divisor of two numbers  and  in .

The algorithm was first described in Euclid's "Elements" (circa 300 BC), but it is possible that the algorithm has even earlier origins.

(https://cp-algorithms.com/index.html)

```
int gcd (int a, int b) {
    while (b) {
        a %= b;
        swap(a, b);
    }
    return a;
}
```
[Link](https://cp-algorithms.com/algebra/euclid-algorithm.html)