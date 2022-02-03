# assignment2-pavuluri-

# pavuluri pranay kumar 

###### kritunga biryani 

> kritunga biryani is located in **kukatpally** , hyderabad , Telangana , India. The ingredients in the biryani are very spicy and **good to taste**. The price of the biryani is very affordable.  


---
## Directions to Kritunga biryani 

1. Ragiv gandhi airport is the naerest airport to the kritunga biryanin house.
2. Catch the cab and reach the shamshabad metro station.
3. Travel from shamshabad airport to kukatpally.
4. catch a cab to reach the destination.


## Menu
* Chinese 
  - chicken noodles
  - chilli chicken
  - gobi fry

* Main course
  - Bamboo chicken 
  - Special chicken 
  - prawns biryani 
  
* Drinks
  - Faluda
  - Strawberry
  - Merinda 
**[AboutMe](Aboutme.md)**


---


### Sports
Below Table shows the sports activities which contain name of the sport, location, money to be pay for the equipment.<br>these are the 4 types of sports that i would recommend someone to try.

Name       | Location        | Amount 
---        | ---             | ---
Badminton  | kolkata stadium |$ 200
Football   | chennai stadium |$ 180
cricket    | uppal stadium   |$ 150
Baseball   | shivaji stadium |$ 100
---

# Pithy Quotes
> “What's really important here," I whispered loudly to myself,"is not the big things other people have thought up, but the small things you, yourself have”
> ― Haruki Murakami, Sputnik Sweetheart

> “Mathematicians deal with large numbers sometimes, but never in their income.”
> ― Isaac Asimov, Prelude to Foundation

---
# Code Fencing

You are given two numbers  and . Find the largest power of   such that  is divisible by Prime Let's first consider the case of prime . The explicit expression for factorial Note that every -th element of the product is divisible by , i.e. adds  to the answer; the number of such elements is Next, every is divisible by , i.e. adds another  to the answer (the first power of  has already been counted in the previous paragraph). The number of such elements is 
And so on, for every  each element adds another  to the answer, and there are such elements. The final answer. The sum is of course finite, since only approximately the first elements are not zeros. Thus, the runtime of this algorithm is Implementation.

(https://cp-algorithms.com/algebra/factorial-divisors.html)

```
int fact_pow (int n, int k) {
    int res = 0;
    while (n) {
        n /= k;
        res += n;
    }
    return res;
}
```

[wiki](https://cp-algorithms.com/combinatorics/catalan-numbers.html)