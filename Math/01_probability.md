# Probability Concepts Guide 🎲🪙🃏

## 1. Equally Likely Events (समान संभावित घटनाएं)

**Definition**: Events jo same probability rakhte hain occur hone ki

### Example 1: Single Die Roll
- **Experiment**: Ek 6-sided die roll karna
- **Sample Space**: {1, 2, 3, 4, 5, 6}
- **Sample Size**: 6
- **Events**: Getting 1, Getting 2, Getting 3, Getting 4, Getting 5, Getting 6
- **Probability**: Har event ka P = 1/6 = 0.167

### Example 2: Coin Toss
- **Experiment**: Ek fair coin toss karna
- **Sample Space**: {Heads, Tails}
- **Sample Size**: 2
- **Events**: Getting Heads, Getting Tails
- **Probability**: Dono events ka P = 1/2 = 0.5

### Example 3: Card Draw (Suits)
- **Experiment**: 52-card deck se ek card draw karna
- **Sample Space**: All 52 cards
- **Sample Size**: 52
- **Events**: Drawing Spades, Hearts, Diamonds, Clubs
- **Probability**: Har suit ka P = 13/52 = 1/4 = 0.25

---

## 2. Complement of an Event (घटना का पूरक)

**Definition**: Event A ka complement A' hai - jo sab kuch include karta hai except A

### Example 1: Die Roll
- **Experiment**: Die roll karna
- **Event A**: Getting even number {2, 4, 6}
- **Complement A'**: Getting odd number {1, 3, 5}
- **P(A) = 3/6 = 0.5**
- **P(A') = 3/6 = 0.5**
- **Verification**: P(A) + P(A') = 1

### Example 2: Card Draw
- **Experiment**: Card draw karna
- **Event A**: Drawing a red card
- **Complement A'**: Drawing a black card
- **P(A) = 26/52 = 0.5**
- **P(A') = 26/52 = 0.5**

### Example 3: Coin Toss
- **Experiment**: Coin toss karna
- **Event A**: Getting Heads
- **Complement A'**: Getting Tails
- **P(A) = 1/2 = 0.5**
- **P(A') = 1/2 = 0.5**

---

## 3. Mutually Exclusive Events (परस्पर अपवर्जी घटनाएं)

**Definition**: Events jo same time pe occur nahi ho sakte

### Example 1: Single Die Roll
- **Experiment**: Die roll karna
- **Event A**: Getting 2
- **Event B**: Getting 5
- **Sample Size**: 6
- **Mutually Exclusive**: Haan, because ek roll mein dono nahi aa sakte
- **P(A ∩ B) = 0**

### Example 2: Card Draw
- **Experiment**: Ek card draw karna
- **Event A**: Drawing a King
- **Event B**: Drawing a Queen
- **Sample Size**: 52
- **Mutually Exclusive**: Haan, ek card King aur Queen dono nahi ho sakta
- **P(A ∩ B) = 0**

### Example 3: Coin Toss
- **Experiment**: Coin toss karna
- **Event A**: Getting Heads
- **Event B**: Getting Tails
- **Sample Size**: 2
- **Mutually Exclusive**: Haan, ek toss mein dono nahi aa sakte
- **P(A ∩ B) = 0**

---

## 4. Mutually Exhaustive Events (परस्पर संपूर्ण घटनाएं)

**Definition**: Events jo collectively pure sample space ko cover karte hain

### Example 1: Die Roll
- **Experiment**: Die roll karna
- **Event A**: Getting {1, 2, 3}
- **Event B**: Getting {4, 5, 6}
- **Sample Size**: 6
- **Mutually Exhaustive**: Haan, dono events milke pure sample space ko cover karte hain
- **P(A ∪ B) = 1**

### Example 2: Card Draw (Color)
- **Experiment**: Card draw karna
- **Event A**: Drawing Red card
- **Event B**: Drawing Black card
- **Sample Size**: 52
- **Mutually Exhaustive**: Haan, har card red ya black hai
- **P(A ∪ B) = 1**

### Example 3: Coin Toss
- **Experiment**: Coin toss karna
- **Event A**: Getting Heads
- **Event B**: Getting Tails
- **Sample Size**: 2
- **Mutually Exhaustive**: Haan, result Heads ya Tails hi hoga
- **P(A ∪ B) = 1**

---

## 5. Independent Events (स्वतंत्र घटनाएं)

**Definition**: Events jinka occurrence ek dusre ko affect nahi karta

### Example 1: Two Dice Rolls
- **Experiment**: Do dice ek saath roll karna
- **Event A**: First die shows 4
- **Event B**: Second die shows 6
- **Sample Size**: 36 (6×6)
- **Independent**: Haan, first die ka result second die ko affect nahi karta
- **P(A) = 6/36 = 1/6, P(B) = 6/36 = 1/6**
- **P(A ∩ B) = 1/36 = P(A) × P(B)**

### Example 2: Coin and Die
- **Experiment**: Coin toss aur die roll together
- **Event A**: Coin shows Heads
- **Event B**: Die shows 3
- **Sample Size**: 12 (2×6)
- **Independent**: Haan, coin ka result die ko affect nahi karta
- **P(A) = 1/2, P(B) = 1/6**
- **P(A ∩ B) = 1/12 = P(A) × P(B)**

### Example 3: Two Card Draws (With Replacement)
- **Experiment**: Do cards draw karna with replacement
- **Event A**: First card is Ace
- **Event B**: Second card is King
- **Sample Size**: 52×52 = 2704
- **Independent**: Haan, replacement ke saath first card second ko affect nahi karta
- **P(A) = 4/52, P(B) = 4/52**
- **P(A ∩ B) = 16/2704 = P(A) × P(B)**

---

## 6. Dependent Events (आश्रित घटनाएं)

**Definition**: Events jinka occurrence ek dusre ko affect karta hai

### Example 1: Two Card Draws (Without Replacement)
- **Experiment**: Do cards draw karna without replacement
- **Event A**: First card is Ace
- **Event B**: Second card is also Ace
- **Sample Size**: 52×51 = 2652
- **Dependent**: Haan, first Ace nikalne pe second Ace ki probability change ho jati hai
- **P(A) = 4/52, P(B|A) = 3/51**
- **P(A ∩ B) = (4/52) × (3/51) = 12/2652**

### Example 2: Drawing Cards (Color)
- **Experiment**: Do cards draw karna without replacement
- **Event A**: First card is Red
- **Event B**: Second card is Red
- **Sample Size**: 52×51 = 2652
- **Dependent**: Haan, first red nikalne pe second red ki probability change ho jati hai
- **P(A) = 26/52, P(B|A) = 25/51**
- **P(A ∩ B) = (26/52) × (25/51) = 650/2652**

### Example 3: Bag with Balls
- **Experiment**: Bag mein 3 red, 2 blue balls hain, 2 balls draw karna without replacement
- **Event A**: First ball is Red
- **Event B**: Second ball is Blue
- **Sample Size**: 5×4 = 20
- **Dependent**: Haan, first ball ka color second ball ki probability affect karta hai
- **P(A) = 3/5, P(B|A) = 2/4 = 1/2**
- **P(A ∩ B) = (3/5) × (1/2) = 3/10**

---

## 7. Addition Rule of Probability (योग नियम)

**Formula**: P(A ∪ B) = P(A) + P(B) - P(A ∩ B)

### Example 1: Die Roll
- **Experiment**: Die roll karna
- **Event A**: Getting even number {2, 4, 6}
- **Event B**: Getting number > 4 {5, 6}
- **Sample Size**: 6
- **P(A) = 3/6 = 0.5**
- **P(B) = 2/6 = 1/3**
- **P(A ∩ B) = 1/6** (only 6 is common)
- **P(A ∪ B) = 3/6 + 2/6 - 1/6 = 4/6 = 2/3**

### Example 2: Card Draw
- **Experiment**: Card draw karna
- **Event A**: Drawing a King
- **Event B**: Drawing a Heart
- **Sample Size**: 52
- **P(A) = 4/52**
- **P(B) = 13/52**
- **P(A ∩ B) = 1/52** (King of Hearts)
- **P(A ∪ B) = 4/52 + 13/52 - 1/52 = 16/52 = 4/13**

### Example 3: Two Dice
- **Experiment**: Do dice roll karna
- **Event A**: Sum = 7
- **Event B**: At least one die shows 4
- **Sample Size**: 36
- **P(A) = 6/36** (combinations: (1,6), (2,5), (3,4), (4,3), (5,2), (6,1))
- **P(B) = 11/36** (first die 4: 6 outcomes, second die 4: 6 outcomes, minus (4,4) counted twice)
- **P(A ∩ B) = 2/36** ((3,4) and (4,3))
- **P(A ∪ B) = 6/36 + 11/36 - 2/36 = 15/36 = 5/12**

---

## 8. Multiplication Rule of Probability (गुणा नियम)

**Formula**: 
- Independent events: P(A ∩ B) = P(A) × P(B)
- Dependent events: P(A ∩ B) = P(A) × P(B|A)

### Example 1: Independent - Coin and Die
- **Experiment**: Coin toss aur die roll
- **Event A**: Coin shows Heads
- **Event B**: Die shows 6
- **Sample Size**: 12
- **P(A) = 1/2**
- **P(B) = 1/6**
- **P(A ∩ B) = 1/2 × 1/6 = 1/12**

### Example 2: Dependent - Cards without Replacement
- **Experiment**: Do cards draw karna without replacement
- **Event A**: First card is Ace
- **Event B**: Second card is King
- **Sample Size**: 52×51
- **P(A) = 4/52**
- **P(B|A) = 4/51** (4 Kings remain in 51 cards)
- **P(A ∩ B) = 4/52 × 4/51 = 16/2652**

### Example 3: Three Coins
- **Experiment**: Teen coins toss karna
- **Event A**: First coin Heads
- **Event B**: Second coin Heads  
- **Event C**: Third coin Heads
- **Sample Size**: 8
- **P(A) = P(B) = P(C) = 1/2**
- **P(A ∩ B ∩ C) = 1/2 × 1/2 × 1/2 = 1/8**

---

## 9. Conditional Probability (सप्रतिबंध प्रायिकता)

**Formula**: P(B|A) = P(A ∩ B) / P(A)

### Example 1: Cards
- **Experiment**: Card draw karna
- **Event A**: Card is Red
- **Event B**: Card is King
- **Sample Size**: 52
- **P(A) = 26/52 = 1/2**
- **P(A ∩ B) = 2/52** (2 red Kings)
- **P(B|A) = (2/52) / (26/52) = 2/26 = 1/13**

### Example 2: Two Dice
- **Experiment**: Do dice roll karna
- **Event A**: Sum is even
- **Event B**: First die shows 3
- **Sample Size**: 36
- **P(A) = 18/36 = 1/2** (18 even sums)
- **P(A ∩ B) = 3/36** (when first die is 3, second die must be 1,3,5 for even sum)
- **P(B|A) = (3/36) / (18/36) = 3/18 = 1/6**

### Example 3: Bag with Balls
- **Experiment**: Bag mein 5 red, 3 blue balls, ek ball draw karna
- **Event A**: Ball is drawn from first 6 balls
- **Event B**: Ball is Red
- **Sample Size**: 8
- **Assume first 6 balls mein 4 red, 2 blue hain**
- **P(A) = 6/8 = 3/4**
- **P(A ∩ B) = 4/8 = 1/2**
- **P(B|A) = (4/8) / (6/8) = 4/6 = 2/3**

---

## Quick Reference Table 📊

| Concept | Formula | Key Point |
|---------|---------|-----------|
| Equally Likely | P(each event) = 1/n | Sab events same probability |
| Complement | P(A') = 1 - P(A) | Total probability = 1 |
| Mutually Exclusive | P(A ∩ B) = 0 | Ek saath nahi ho sakte |
| Mutually Exhaustive | P(A ∪ B ∪ ...) = 1 | Sab possibilities cover |
| Independent | P(A ∩ B) = P(A) × P(B) | Ek dusre ko affect nahi karte |
| Dependent | P(A ∩ B) = P(A) × P(B\|A) | Ek dusre ko affect karte hain |
| Addition Rule | P(A ∪ B) = P(A) + P(B) - P(A ∩ B) | Union ki probability |
| Multiplication Rule | P(A ∩ B) = P(A) × P(B) or P(A) × P(B\|A) | Intersection ki probability |
| Conditional | P(B\|A) = P(A ∩ B) / P(A) | Given condition mein probability |

**Sample Space Size Quick Reference:**
- Single die: 6
- Single coin: 2  
- Two dice: 36
- Two coins: 4
- Single card from deck: 52
- Two cards without replacement: 52 × 51 = 2652
- Two cards with replacement: 52 × 52 = 2704
