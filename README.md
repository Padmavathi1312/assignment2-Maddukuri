# assignment2-Maddukuri
edited
# Padmavathi
###### Bawarchi
__Bawarchi__ is one of the best restaurant in Hyderabad. It is famous for the __spicy chicken dum biryani__.

---

## Directions to airport from restaurant

The closest airport from food court is **Rajiv Gandhi International Airport**.<br>
Below are the directions for travelling to foodcourt from airport
1. Come out from international terminal and get into airport shuttle to Uppal cross roads which is available every one hour.
2. From Uppal cross roads, take metro to Jubilee hills No.5 cross roads which is available every 10 minutes.
2. From Jubilee hills No.5, take right and go straight till Wipro junction.
3. From Wipro junction, take left and you can see Bawarchi restaurant on the right next to Forum mall.

## Best food items in Bawarchi
List of good food items that are recommended to others in Bawarchi
- Virgin watermelon margarita mocktail
- Chicken manchow soup
- Main course
    - Spicy chicken dum biryani
    - Mixed biryani
- Deserts
    - Sizzling brownie icecream
    - Gulab Jamun

---

[link to AboutMe](https://github.com/Padmavathi1312/assignment2-Maddukuri/blob/main/AboutMe.md)

---

# TABLE CREATION

Below is the table for 4 best activities that one should try in a lifetime. It has details regarding the location of the activity and the amount of money needed for the personal equipment.
| Activity | Location | Amount in $|
| --- | --- | ---: |
| Kayaking | Dandeli | 20 |
| River Rafting | Dudhsagar | 30 |
| Mountain Climbing | Pune | 10 |
| Skuba Diving | Goa | 40 |

---

# Inspirational quotes

> “Be the change that you wish to see in the world.”
>> *-Mahatma Gandhi*

> “It is never too late to be what you might have been.”
>> *-George Eliot*

***

# CODE FENCING

> Sparse Table is a data structure that answers static Range Minimum Query (RMQ). It is recognized for its relatively fast query and short implementation compared to other data structures

[Link of source](https://brilliant.org/wiki/sparse-table/#:~:text=Sparse%20Table%20is%20a%20data,compared%20to%20other%20data%20structures.)

```
void make_set(int v) {
    parent[v] = v;
}

int find_set(int v) {
    if (v == parent[v])
        return v;
    return find_set(parent[v]);
}

void union_sets(int a, int b) {
    a = find_set(a);
    b = find_set(b);
    if (a != b)
        parent[b] = a;
}
```
[quick link to the source code - Range sum queries](https://cp-algorithms.com/data_structures/sparse-table.html)






