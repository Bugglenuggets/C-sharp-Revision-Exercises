---
Order: "0"
---

# Class Test Practice Sheet 3: Code Output and Logic

These questions are in the style of the code output section of the class test. Read each program and choose what it prints to the console. Work through the code line by line on paper. Do not run it. Each question has one correct answer. Use the Weeks 1-4 slides and tutorials to check your answers.

---

## Part A: Easy

### 1. What is the output of the following code?

```csharp
int a = 5;
int b = 3;
Console.WriteLine(a + b);
```

- A) 53
- B) 2
- C) 15
- D) 8

---

### 2. What is the output of this code?

```csharp
int x = 10;
x -= 4;
Console.WriteLine(x);
```

- A) 4
- B) 6
- C) 14
- D) -4

---

### 3. What will be printed to the console?

```csharp
int a = 2;
int b = 4;
Console.WriteLine(a * b + 1);
```

- A) 9
- B) 8
- C) 6
- D) 5

---

### 4. What is printed here?

```csharp
int x = 10;
int y = 2;
Console.WriteLine(x / y);
```

- A) 4
- B) 12
- C) 8
- D) 5

---

### 5. What is the output of this conditional statement?

```csharp
int health = 0;
if (health > 0)
{
    Console.WriteLine("Alive");
}
else
{
    Console.WriteLine("Game Over");
}
```

- A) Alive
- B) 0
- C) Game Over
- D) Error

---

### 6. What will the console display?

```csharp
int score = 50;
if (score >= 100)
{
    Console.WriteLine("Winner");
}
else
{
    Console.WriteLine("Try Again");
}
```

- A) Try Again
- B) 50
- C) Winner
- D) 100

---

### 7. What will this program output?

```csharp
bool isReady = true;
if (isReady)
{
    Console.WriteLine("Start!");
}
else
{
    Console.WriteLine("Wait...");
}
```

- A) Wait...
- B) Start!
- C) isReady
- D) true

---

### 8. What will this loop print? (Each value is printed on its own line.)

```csharp
for (int i = 0; i < 3; i++)
{
    Console.WriteLine(i);
}
```

- A) 1 2 3
- B) 3 2 1
- C) 0 1 2 3
- D) 0 1 2

---

## Part B: Medium

### 9. What is the output?

```csharp
int lives = 3;

if (lives > 0)
{
    Console.WriteLine("Keep playing");
    lives = lives - 1;
}
else
{
    Console.WriteLine("Game over");
}
```

- A) Game over
- B) Keep playing
- C) 2
- D) lives

---

### 10. What is the output?

```csharp
bool isOnline = false;
bool hasToken = true;

if (isOnline || hasToken)
{
    Console.WriteLine("access allowed");
}
else
{
    Console.WriteLine("access denied");
}
```

- A) access denied
- B) true
- C) access allowed
- D) false

---

### 11. What is the output?

```csharp
int x = 3;
int y = 7;

if (x < y && y < 10)
{
    Console.WriteLine("in range");
}
else
{
    Console.WriteLine("out of range");
}
```

- A) true
- B) in range
- C) 3 7
- D) out of range

---

### 12. What is the output?

```csharp
int a = 2;
int b = 3;
int c = a + b;

if (c > 5)
{
    Console.WriteLine("large");
}
else if (c == 5)
{
    Console.WriteLine("exact");
}
else
{
    Console.WriteLine("small");
}
```

- A) small
- B) exact
- C) large
- D) 5

---

### 13. What is the output?

```csharp
int energy = 8;

if (energy >= 10)
{
    Console.WriteLine("high");
}
else
{
    if (energy >= 5)
    {
        Console.WriteLine("medium");
    }
    else
    {
        Console.WriteLine("low");
    }
}
```

- A) high
- B) low
- C) medium
- D) energy

---

### 14. What is the output?

```csharp
string first = "Player";
string middle = "scored ";
int points = 100;

string message = first + " " + middle + points + " points!";
Console.WriteLine(message);
```

- A) Player scored points!
- B) Player scored100 points!
- C) Player scored 100 points!
- D) Player 100 scored points!

---

## Part C: Advanced

### 15. Player Health Update - What is the output?

```csharp
int health = 100;
int hit = 20;

Console.WriteLine("Starting Health: " + health);
health -= hit;
Console.WriteLine("Took Damage: " + hit);
Console.WriteLine("Current Health: " + health);
```

- A) Starting Health: 100  
  Took Damage: 20  
  Current Health: 80
- B) Starting Health: 80  
  Took Damage: 20  
  Current Health: 100
- C) Starting Health: 100  
  Current Health: 80
- D) Took Damage: 80  
  Current Health: 20

---

### 16. Score and Bonus Loop - What is the output?

```csharp
int score = 0;
int bonus = 5;

for (int i = 1; i <= 3; i++)
{
    score += bonus;
    if (score > 10)
    {
        Console.WriteLine("High Score");
    }
    else
    {
        Console.WriteLine("Keep Going");
    }
}
```

- A) Keep Going  
  High Score
- B) Keep Going  
  Keep Going  
  High Score
- C) High Score  
  Keep Going
- D) Keep Going  
  High Score  
  High Score

---

### 17. Inventory Count Loop - What is the output?

```csharp
int items = 0;

for (int i = 0; i < 4; i++)
{
    items++;
    if (items == 3)
    {
        Console.WriteLine("Inventory Almost Full");
    }
}

Console.WriteLine("Total Items: " + items);
```

- A) Inventory Almost Full  
  Total Items: 3
- B) Inventory Almost Full  
  Total Items: 4
- C) Total Items: 4
- D) Inventory Almost Full

---

### 18. Player Energy Loop - What is the output?

```csharp
int energy = 5;

while (energy > 0)
{
    energy--;
    Console.WriteLine("Energy Left: " + energy);
}

Console.WriteLine("Out of Energy!");
```

- A) Energy Left: 4  
  Energy Left: 3  
  Energy Left: 2  
  Energy Left: 1  
  Energy Left: 0  
  Out of Energy!
- B) Out of Energy!
- C) Energy Left: 0
- D) Energy Left: 5  
  Energy Left: 4  
  Energy Left: 3  
  Energy Left: 2  
  Energy Left: 1  
  Out of Energy!

---

### 19. Score Bonus - What is the output?

```csharp
int baseScore = 20;

int total = AddBonus(baseScore);
Console.WriteLine("Final Score: " + total);

int AddBonus(int score)
{
    int bonus = 10;
    return score + bonus;
}
```

- A) Final Score: 20
- B) Final Score: 10
- C) Final Score: 2010
- D) Final Score: 30

---

### 20. Function Return and Condition - What is the output?

```csharp
int result = Calculate(4);
Console.WriteLine("Result: " + result);

int Calculate(int n)
{
    int total = n * 2;
    if (total > 5)
    {
        return total + 1;
    }
    else
    {
        return total - 1;
    }
}
```

- A) Result: 8
- B) Result: 7
- C) Result: 5
- D) Result: 9
