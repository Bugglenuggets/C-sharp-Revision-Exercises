---
Order: "0"
---

# Class Test Practice Sheet 2: Code Completion

These questions are in the style of the code completion section of the class test. Each `_________` is one blank. Type only what is missing: a keyword, operator, name or value. C# is case-sensitive, so write each answer exactly as it would appear in code. Use the Weeks 1-4 slides and tutorials to check your answers.

---

## Part A: C# Basics

### 1. Creating and Initialising a Variable

Complete the code below to declare an integer variable named `score` and set its value to `100`:

```csharp
int _________ = _________;
```

---

### 2. If Statement

Complete the following `if` statement to check if a variable `health` is greater than zero:

```csharp
if (_________ > _________)
{
    Console.WriteLine("Player is alive");
}
```

---

### 3. While Loop

Complete the code to make a `while` loop that runs as long as `score` is less than `100`:

```csharp
while (_________ < 100)
{
    score++;
}
```

---

### 4. For Loop Syntax

Complete the code below to write a `for` loop that counts from 1 to 5:

```csharp
for (int i = 1; i _________ 5; i_________)
{
    Console.WriteLine(i);
}
```

---

### 5. For Loop

Complete the code to create a `for` loop that iterates through an array of strings called `names`:

```csharp
for (_________ i = 0; i _________ names.Length; i_________)
{
    Console.WriteLine(names[i]);
}
```

---

### 6. Switch Statement

Fill in the blanks so the switch statement checks the integer variable `level` and prints "Medium mode" when `level` is 2:

```csharp
switch (_________)
{
    case 1:
        Console.WriteLine("Easy mode");
        break;
    case _________:
        Console.WriteLine("Medium mode");
        break;
    default:
        Console.WriteLine("Invalid mode");
        break;
}
```

---

### 7. Function Definition

Complete the code to define a public method in C# named `MovePlayer` that takes no parameters and returns no value:

```csharp
public _________ MovePlayer()
{
    Console.WriteLine("Moving player...");
}
```

---

### 8. Method Declaration

Fill in the blanks to create a public method called `TakeDamage` that accepts an integer parameter `damage`:

```csharp
public void _________(int _________)
{
    health -= damage;
}
```

---

### 9. Calling a Method

Fill in the blank to call the method `StartGame()` from within the `Main` method:

```csharp
public static void Main()
{
    _________();
}

public static void StartGame()
{
    Console.WriteLine("Game has started.");
}
```

---

### 10. Creating a Class

Complete the following code to create a class called `Enemy` with a public method called `Attack()`:

```csharp
public _________ Enemy
{
    public void _________()
    {
        Console.WriteLine("Enemy attacks!");
    }
}
```

---

### 11. Creating an Object

Fill in the blank to create a `Player` object in C#:

```csharp
Player myPlayer = _________ Player();
```

---

## Part B: Arrays and Lists

### 12. Array Length

Complete the code to get the number of elements in the `names` array:

```csharp
int total = names._________;
```

---

### 13. List Declaration

Fill in the blank to declare a list of strings called `names`:

```csharp
List<string> names = _________ List<string>();
```

---

### 14. Adding Elements to a List

Complete the code to add the string "John" to the `names` list:

```csharp
names._________("John");
```

---

### 15. Removing Elements from a List

Complete the code to remove the element "John" from the `names` list:

```csharp
names._________("John");
```

---

### 16. List Count Property

Complete the code to get the number of elements in the `names` list:

```csharp
int count = names._________;
```

---

## Part C: Unity

### 17. Accessing a Component

Fill in the blank to get the `Renderer` component of a GameObject:

```csharp
Renderer r = GetComponent<_________>();
```

---

### 18. Adding a Rigidbody Component

Complete the following code to add a `Rigidbody` component to a `GameObject`:

```csharp
gameObject.AddComponent<_________>();
```

---

### 19. Instantiate a GameObject

Fill in the blanks to instantiate a `bullet` prefab at the player's position and rotation:

```csharp
Instantiate(_________, transform.position, transform._________);
```

---

### 20. Destroy a GameObject

Complete the code to destroy a `GameObject` called `enemy` after 3 seconds:

```csharp
Destroy(_________, 3f);
```

---

### 21. Checking for Collision

Complete the code with the Unity method that runs when a `GameObject` collides with another object:

```csharp
void _________(Collision collision)
{
    Debug.Log("Collision Detected");
}
```

---

### 22. Event Subscription in Unity

Complete the code (fill in the operator) to subscribe a method called `OnGameOver` to a `GameOver` event:

```csharp
GameManager.GameOver _________ OnGameOver;
```
