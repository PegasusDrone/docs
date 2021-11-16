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
- future usecase
- Priority given to efficiency (for longer flight time) as opposed to power (good for racing drones)
- 50% throttle taken as nominal (used to determine AUW) and 100% as extreme

<TableWrap>

| Motor                         | Throttle | Thrust (g)  | Amps & Power (w) | Efficiency (g/w) | Price ($)        | AUW (g) (thrust*4) |
|-------------------------------|----------|-------------|------------------|------------------|------------------|--------------------|
| MN4006 KV380 (15*5'' props)   | 50%      | 805         | 74               | 10.82            | 149.9*2 = 299.8  | 1610               |
| 100%                          | 2228     | 360         | 6.19             |                  |                  |                    |
| MN5006 KV450 (15*5'' props)   | 50%      | 1084        | 5.41 | 127       | 8.51             | 84.99*4 = 339.96 | 4336               |
| 100%                          | 3218     | 26 | 601    | 5.35             |                  |                  |                    |
| MN5008 KV400 (16*5.4'' props) | 50%      | 1033        | 4.95| 116        | 8.92             | 89.99*4 = 359.96 | 4132               |
| 100%                          | 3027     | 23.44 | 535 | 5.66             |                  |                  |                    |



</TableWrap>

### ESC Selection
### Considerations: 
- Only difference is efficiency / finetuning options 
- Air 40A should work equally good

<TableWrap>

| Esc          | Price ($)        |
|--------------|------------------|
| AIR 40A 6S   | 39.99*4 = 159.96 |
| ALPHA 40A 6S | 69.99*4 = 279.96 |

</TableWrap>

### Propeller Selection
### Considerations: 
- 5.4mm pitch would be ideal trade off between speed and precision 
- Larger Props increased efficiency and thrust
- Due to size constraints, 16'' is max we can go
- Only difference betn Foldable and normal prop I found was better efficiency/Time of flight

<TableWrap>

| Propellers      | Price ($)        |
|-----------------|------------------|
| NS16x5.4 Prop   | 62.99*2 = 125.98 |
| NS15x5 Prop     | 56.99*2 = 113.98 |
| FA16.2×5.3 Prop | 109.9*2 = 219.8  |

</TableWrap>

### Battery Selection
### Considerations: 
- All motors worked best with 6S
- 4S step up doesnt work well with pm07 power module, better to isolate both systems
- 5000*60/1000 = 300 amp/min
- 300/8 (amps) = 37.5 mins time of flight (approx without safety factor)

<TableWrap>

| Battery                         | Price ($) |
|---------------------------------|-----------|
| Turnigy Graphene 5000mAh 6S 45C | $99.99    |


</TableWrap>


> Author: [Mihir Patel](https://github.com/mihyr)