# Concert Tour Routing Plan Optimization
````diff 
+ (concert-tour-routing)
````
### Quick Summary
***
- **Purpose:** Study the routing plan optimization based on various scenarios and constraints using Gurobi and Lazy Constraints.
- **Dataset Source:**
  - [Canada Cities Database](https://simplemaps.com/data/canada-cities)
  - Synthetic Data
<br><br>

### Detailed Description
***
1. Implementation - Canadian Cities: Optimize the routing plan to visit ALL top 150 Canadian cities based on their population.
2. Implementation - Synthetic Data: Optimize the routing plan from synthetic data as venue candidates. In this implementation, there's no need to visit all venues yet there are constraints about the minimum and maximum numbers of venues to visit.
3. Implementation - Synthetic Data with Venue Availability: Similar to the previous model, but include the availability time of each venue.

<br><br>

### Preview
***
- Optimized Routing Plan for Top 150 Canadian Cities<br>
![CA Tour](https://user-images.githubusercontent.com/111717563/236935438-2cf607ea-9216-4e79-8720-979f233332cb.png)



- Optimized Routing Plan for Synthetic Data<br>
![Synthetic Data Tour](https://user-images.githubusercontent.com/111717563/236934667-631a333c-ca4b-48e3-8418-4f06bbb17584.png)
