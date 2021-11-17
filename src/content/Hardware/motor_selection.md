---
title: Motor Selection
order: 4
pcx-content-type: best-practices
---
<Aside type="warning" header="To-Do">

Page To be removed

</Aside>

### Motor Selection
### Considerations: 
- Future usecase (i.e. additional weight 250-300 g)
- Priority given to efficiency (for longer flight time) as opposed to power (good for racing drones)
- 50% throttle taken as nominal (used to determine AUW) and 100% as extreme  
- Note: - In my view MN 5006 KV450 suits best, hence I added two configurations, i.e. with 14 and 15 inch props
<TableWrap>
|Motor                        |Throttle|Thrust (g)|Current (a)|Power (w)|Efficiency (g/w)|Price ($)       |AUW (g) (thrust*4)|
|-----------------------------|--------|----------|-----------|---------|----------------|----------------|------------------|
|[MN4006 KV380 (15*5'' props)](https://store.tmotor.com/goods.php?id=440)  |50%     |805       |3.1        |74       |10.82           |149.9*2 = 299.8 |1610              |
|                             |100%    |2228      |15         |360      |6.19            |                |                  |
|[MN5006 KV450 (14*4.8'' props)](https://store.tmotor.com/goods.php?id=997)|50%     |840       |4.04       |95       |8.82            |84.99*4 = 339.96|3360              |
|                             |100%    |2672      |20.16      |465      |5.75            |                |                  |
|[MN5006 KV450 (15*5'' props)](https://store.tmotor.com/goods.php?id=997)  |50%     |895       |4.2        |99       |9.03            |84.99*4 = 339.96|3580              |
|                             |100%    |3218      |26.28      |601      |5.35            |                |                  |
|[MN5008 KV400 (15*5.4'' props)](https://store.tmotor.com/goods.php?id=1000)|50%     |1033      |4.95       |116      |8.92            |89.99*4 = 359.96|4132              |
|                             |100%    |3027      |23.44      |535      |5.66            |                |                  |



</TableWrap>

### ESC Selection
### Considerations: 
- Only difference is efficiency / finetuning options 
- Air 40A should work fine for our application

<TableWrap>

| Esc          | Price ($)        |
|--------------|------------------|
| [AIR 40A 6S ](https://store.tmotor.com/goods.php?id=368)  | 39.99*4 = 159.96 |
| [ALPHA 40A 6S ](https://store.tmotor.com/goods.php?id=580)| 69.99*4 = 279.96 |

</TableWrap>

### Propeller Selection
### Considerations: 
- 5.4mm pitch would be ideal trade off between speed and precision 
- Larger Props increased efficiency and thrust
- Due to size constraints, 15'' is max we can go
- Only difference betn Foldable and normal prop I found was better efficiency/Time of flight, but they tend to have more vibrations because of bolts they are attached to.

<TableWrap>

| Propellers      | Price ($)        |
|-----------------|------------------|
|[NS14x4.8 Prop](https://store.tmotor.com/goods.php?id=962)|$49.99*2 = 99.98|
|[NS15x5 Prop](https://store.tmotor.com/goods.php?id=1072)  |56.99*2 = 113.98|
|[FA15.2×5 Prop](https://store.tmotor.com/goods.php?id=391)|109.9*2 = 219.8 |

</TableWrap>

### Battery Selection
### Considerations: 
- All motors worked best with 6S  
- Rough Calculation:  
For 5000 mah  
5000*60/1000 = 300 amp/min  
If drone consumes 4 amps per motor on an average (from first table 50% throttle); i.e. 16 amps in total (we are not considering xavier's consumption)  
300/16 (amps) = 18.75 mins time of flight (approx without safety factor)   

<TableWrap>

| Battery                         | Price ($) |
|---------------------------------|-----------|
| [Turnigy Graphene 5000mAh 6S 45C](https://hobbyking.com/en_us/graphene-5000mah-6s-45c-w-xt90.html) | $99.99    |


</TableWrap>


> Author: [Mihir Patel](https://github.com/mihyr)