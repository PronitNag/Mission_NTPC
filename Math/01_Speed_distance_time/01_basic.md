# 🚗 Speed and Distance Problems Solutions

## Q1) Journey with Three Different Speeds 🛣️

**Problem:** One-third of a journey is covered at 67 km/hr, next one-third at 66 km/hr, and remaining at 17 km/hr. Find average speed.

```
Journey Visualization:
🏁 ────────────────────────────────────────────────────────────────── 🏁
     1/3 @ 67 km/hr    1/3 @ 66 km/hr    1/3 @ 17 km/hr
     ═══════════════   ═══════════════   ═══════════════
```

**Solution:**
Let total distance = 3d (so each part = d)

Time for each segment:
- First 1/3: t₁ = d/67 hours
- Second 1/3: t₂ = d/66 hours  
- Final 1/3: t₃ = d/17 hours

Total time = d/67 + d/66 + d/17 = d(1/67 + 1/66 + 1/17)

Finding common denominator:
- 1/67 = 66×17/(67×66×17) = 1122/75042
- 1/66 = 67×17/(66×67×17) = 1139/75042
- 1/17 = 67×66/(17×67×66) = 4422/75042

Total = d(1122 + 1139 + 4422)/75042 = d(6683)/75042

Average speed = Total distance/Total time = 3d ÷ (d × 6683/75042) = 3 × 75042/6683 = **33.7 km/hr**

**Answer: C) 33.7** ✅

---

## Q2) Rishika's Journey Problem 🚶‍♀️

**Problem:** Travels distance d at 52 km/hr, then 2d at 39 km/hr, returns via same route. Average speed for entire journey = 56 km/hr. Find return speed.

```
Journey Visualization:
🏠 ────d────► 🏪 ────2d────► 🏁 ────3d────► 🏠
   52 km/hr      39 km/hr      v km/hr
                                (return)
```

**Solution:**
Forward journey:
- Time₁ = d/52 hours
- Time₂ = 2d/39 hours
- Total forward time = d/52 + 2d/39

Return journey:
- Distance = 3d, Speed = v km/hr
- Time₃ = 3d/v hours

Total distance = 6d
Total time = d/52 + 2d/39 + 3d/v

Average speed equation:
56 = 6d ÷ (d/52 + 2d/39 + 3d/v)

Simplifying:
56 = 6 ÷ (1/52 + 2/39 + 3/v)

1/52 + 2/39 = 39 + 104/2028 = 143/2028

6/56 = 3/28 = 143/2028 + 3/v

3/v = 3/28 - 143/2028 = (3×2028 - 143×28)/(28×2028) = 2084/56784

v = 56784/2084 × 3 = **81.9 km/hr**

**Answer: B) 81.9** ✅

---

## Q3) Two Cabs and Walking Man Problem 🚖👤

**Problem:** Two cabs start at 74 km/hr with 28-minute intervals. Man walking opposite direction meets them at 10-minute intervals. Find man's speed.

```
Relative Motion Visualization:
Cab 1 ──────────────────────────► 74 km/hr
                    ◄────────────── Man @ v km/hr
         Cab 2 ──────────────────► 74 km/hr
         
Time gap: 28 min → Meeting gap: 10 min
```

**Solution:**
Let man's speed = v km/hr

Distance between consecutive cabs = 74 × (28/60) = 74 × 7/15 km

When man meets cabs, relative speed = 74 + v km/hr
Time between meetings = 10 minutes = 1/6 hour

Distance = Speed × Time
74 × 7/15 = (74 + v) × 1/6

Solving:
74 × 7/15 = (74 + v)/6
74 × 7 × 6 = 15(74 + v)
3108 = 1110 + 15v
15v = 1998
v = **133.2 km/hr**

**Answer: B) 133.2** ✅

---

## Q4) Amita's Journey Problem 🚶‍♀️

**Problem:** Travels distance d at 84 km/hr, then 2d at 28 km/hr, returns via same route. Average speed = 24 km/hr. Find return speed.

```
Journey Visualization:
🏠 ────d────► 🏪 ────2d────► 🏁 ────3d────► 🏠
   84 km/hr      28 km/hr      v km/hr
                                (return)
```

**Solution:**
Forward journey times:
- Time₁ = d/84 hours
- Time₂ = 2d/28 = d/14 hours
- Total forward time = d/84 + d/14

Return journey:
- Time₃ = 3d/v hours

Total distance = 6d
Average speed = 24 km/hr

24 = 6d ÷ (d/84 + d/14 + 3d/v)

Simplifying:
24 = 6 ÷ (1/84 + 1/14 + 3/v)

1/84 + 1/14 = 1/84 + 6/84 = 7/84 = 1/12

6/24 = 1/4 = 1/12 + 3/v

3/v = 1/4 - 1/12 = (3-1)/12 = 2/12 = 1/6

v = 3 × 6 = **18 km/hr**

**Answer: C) 18** ✅

---

## Q5) Another Two Cabs and Walking Man Problem 🚖👤

**Problem:** Two cabs start at 54 km/hr with 29-minute intervals. Man walking opposite direction meets them at 12-minute intervals. Find man's speed.

```
Relative Motion Visualization:
Cab 1 ──────────────────────────► 54 km/hr
                    ◄────────────── Man @ v km/hr
         Cab 2 ──────────────────► 54 km/hr
         
Time gap: 29 min → Meeting gap: 12 min
```

**Solution:**
Distance between consecutive cabs = 54 × (29/60) km

Relative speed when meeting = 54 + v km/hr
Time between meetings = 12/60 = 1/5 hour

Distance equation:
54 × 29/60 = (54 + v) × 1/5

Solving:
54 × 29/60 = (54 + v)/5
54 × 29 × 5 = 60(54 + v)
7830 = 3240 + 60v
60v = 4590
v = **76.5 km/hr**

**Answer: C) 76.5** ✅

---

## 📊 Summary of Answers

| Question | Answer | Value |
|----------|---------|--------|
| Q1 | C | 33.7 km/hr |
| Q2 | B | 81.9 km/hr |
| Q3 | B | 133.2 km/hr |
| Q4 | C | 18 km/hr |
| Q5 | C | 76.5 km/hr |

## 🔑 Key Formulas Used

1. **Average Speed = Total Distance ÷ Total Time**
2. **For relative motion: Combined speed = Speed₁ + Speed₂**
3. **Distance = Speed × Time**
4. **Harmonic mean for equal distances at different speeds**

## 💡 Tips for Speed Problems

- Always identify whether distances or times are equal
- Use relative speed concept for opposite direction problems
- Set up equations systematically
- Convert time units consistently (minutes to hours)
- Double-check calculations with dimensional analysis

---
*Solutions completed with step-by-step mathematical reasoning* 🎯
