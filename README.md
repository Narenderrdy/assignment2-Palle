# assignment2-Palle
# Narender Reddy Palle
# Hyderabad

 > My hometown is in Hyderabad and The city of Hyderabad is famous for its **rich architecture culture**.And **Hyderabad biriyani** is most famous dish of Hyderabad.And most of my  friends lives in Hyderabad.
---

## Directions from New York to Chicago
1. Take a cab and go the new york airport.
2. And the estimated flight time  is 2hr by flight.
     1. Its appromiately 1200kms.
     1.   The Distance may be very much different from the actual travel distance.
4. After reaching the chicago Airport take the cab and go the ur favorite places in Chicago.

5. Items that should be brought to your favorite place for maximum enjoyment. 
    
    - camera
    - self-stick
    - Basketball
    - Skateboard
       
       [About Myself](AboutMe.md)
---

## FOOD ITEMS
McDonald's is an American corportion that operates one of the largest chains of fast food restaurants in the world.
 | FOOD ITEMS | LOCATION | AMOUNT |
 | ---| ---| ---: |
 | Tacos | McDonald's | 4$ |
 | Pizza | McDonald's | 15$ |
 | Burger | McDonald's | 10$ |
 | Chicken Nuggets | McDonald's | 6$ |

---
## PITHY QUOTES

 > The unexamined life is not worth living". - *Socrates*
 
>  One cannot step twice in the same river. -*Heraclitus*
---
## CODE FENCING
### Circle-Line Intersection

> An (infinite) line determined by two points (x_1,y_1) and (x_2,y_2) may intersect a circle of radius r and center (0, 0) in two imaginary points, a degenerate single point (corresponding to the line being tangent to the circle; middle figure), or two real points [FOLLOWLINK] (https://mathworld.wolfram.com/Circle-LineIntersection.html)

```java
double r, a, b, c; // given as input
double x0 = -a*c/(a*a+b*b), y0 = -b*c/(a*a+b*b);

if (c*c > r*r*(a*a+b*b)+EPS)
    puts ("no points");
else if (abs (c*c - r*r*(a*a+b*b)) < EPS) {
    puts ("1 point");
    cout << x0 << ' ' << y0 << '\n';
}
else {
    double d = r*r - c*c/(a*a+b*b);
    double mult = sqrt (d / (a*a+b*b));
    double ax, ay, bx, by;
    ax = x0 + b * mult;
    bx = x0 - b * mult;
    ay = y0 - a * mult;
    by = y0 + a * mult;
    puts ("2 points");
    cout << ax << ' ' << ay << '\n' << bx << ' ' << by << '\n';
}
```
(https://cp-algorithms.com/geometry/circle-line-intersection.html)

 
       