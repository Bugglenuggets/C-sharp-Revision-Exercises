---
Order: "0"
---

# Class Test Practice Sheet 1: Multiple Choice

These questions are in the style of the multiple-choice sections of the class test. Each question has one correct answer. Use the Weeks 1-4 slides and tutorials to check your answers.

---

## Part A: General C# and Unity

### 1. What is a variable in programming?

- A) A tool used to compile the code.
- B) A named value that can change while the program runs.
- C) A function that defines the program's entry point.
- D) An error message displayed by the compiler.

---

### 2. Which of the following is a valid data type in C#?

- A) `integer`
- B) `float`
- C) `number`
- D) `letter`

---

### 3. What is the purpose of the `void` keyword in a method declaration?

- A) It indicates the method will return a string value.
- B) It specifies that the method returns no value.
- C) It makes the method private.
- D) It initialises a new instance of the class.

---

### 4. What is the purpose of a conditional statement like `if` in C#?

- A) To declare a variable.
- B) To create a class.
- C) To execute code based on a condition being true or false.
- D) To define a method's parameters.

---

### 5. Which of these operators is used for equality comparison in C#?

- A) `=`
- B) `==`
- C) `!=`
- D) `>=`

---

### 6. What does the `+=` operator do when used with a variable in C#?

- A) Assigns the value to the variable.
- B) Adds a value and assigns the result to the variable.
- C) Multiplies the value of the variable.
- D) Subtracts a value from the variable.

---

### 7. Which of the following is a valid way to declare a string variable in C#?

- A) `string name = 'John';`
- B) `String name = (John);`
- C) `string name = "John";`
- D) `char name = "John";`

---

### 8. What is the default value of a boolean variable in C#?

- A) `true`
- B) `1`
- C) `false`
- D) `null`

---

### 9. Which symbol is used to denote a single-line comment in C#?

- A) `/* ... */`
- B) `//`
- C) `<!-- ... -->`
- D) `**`

---

### 10. Which of the following is NOT a type of loop in C#?

- A) `while`
- B) `for`
- C) `foreach`
- D) `until`

---

### 11. Which C# loop structure is best suited for iterating a fixed number of times?

- A) `foreach`
- B) `while`
- C) `do-while`
- D) `for`

---

### 12. Which keyword is used to exit a loop early in C#?

- A) `stop`
- B) `end`
- C) `continue`
- D) `break`

---

### 13. What is an array in C#?

- A) A collection of elements of different data types.
- B) A single variable that can store multiple values of the same data type.
- C) A function that processes input and outputs data.
- D) A method that returns a string.

---

### 14. Which of these correctly declares an integer array in C#?

- A) `int[] numbers = {1, 2, 3};`
- B) `array<int> numbers = [1, 2, 3];`
- C) `int numbers[3] = {1, 2, 3};`
- D) `int[] numbers = new {1, 2, 3};`

---

### 15. Which of the following correctly creates a new list of integers in C#?

- A) `List<int> numbers = new List<int>();`
- B) `List numbers = new List();`
- C) `int[] numbers = new List<int>();`
- D) `List<int> numbers = int List();`

---

### 16. What is the purpose of the `null` keyword in C#?

- A) It signifies a variable that is equal to 0.
- B) It indicates that a variable has no value.
- C) It is used to declare variables.
- D) It converts data types.

---

### 17. What is a method in C#?

- A) A named block of code that performs a task when it is called.
- B) A keyword that defines a variable.
- C) A loop used for iteration.
- D) A conditional statement used for branching.

---

### 18. Which of these is a correct way to declare a public method in C#?

- A) `void public MyMethod()`
- B) `public void MyMethod()`
- C) `public MyMethod void()`
- D) `void MyMethod() public`

---

### 19. What is the purpose of the `return` statement in a method?

- A) To stop the program completely.
- B) To end the method and optionally send a value back to the caller.
- C) To pause the method until resumed.
- D) To call another function.

---

### 20. What keyword is used to define a class in C#?

- A) `define`
- B) `declare`
- C) `object`
- D) `class`

---

### 21. Which of the following is the correct way to create an object from a class in C#?

- A) `ClassName newObj = ClassName();`
- B) `ClassName newObj = new ClassName();`
- C) `ClassName = newObj()`
- D) `ClassName newObj = create ClassName();`

---

### 22. Which of these access modifiers allows a variable to be accessible from any class?

- A) `private`
- B) `internal`
- C) `protected`
- D) `public`

---

### 23. Which access modifier restricts a variable so it can only be used within the same class?

- A) `public`
- B) `protected`
- C) `private`
- D) `internal`

---

### 24. What is the main purpose of `get` and `set` accessors in a C# property?

- A) To control how the property's value is read and changed.
- B) To create a new instance of a class.
- C) To handle events when a variable changes.
- D) To initialise a variable once at startup.

---

### 25. What does the `Debug.Log()` function do in Unity?

- A) Outputs a message to the Console window.
- B) Halts the program execution.
- C) Displays an error message to the user.
- D) Saves the game state.

---

### 26. What is the purpose of the `Start()` method in Unity?

- A) To handle physics updates.
- B) To initialise variables or state once, before the first frame update.
- C) To destroy objects in the scene.
- D) To render the UI.

---

### 27. What is the `Awake()` method used for in Unity?

- A) To update physics-based operations.
- B) To initialise variables or state before `Start()` is called.
- C) To create new GameObjects.
- D) To handle user input.

---

### 28. Which method is called once per frame in a Unity script?

- A) `OnEnable()`
- B) `Awake()`
- C) `Update()`
- D) `FixedUpdate()`

---

### 29. In Unity, which method is used to detect collision events between two GameObjects?

- A) `Update()`
- B) `Start()`
- C) `OnCollisionEnter()`
- D) `FixedUpdate()`

---

### 30. In Unity, which built-in method is used to detect when a trigger collider is entered?

- A) `OnCollisionEnter()`
- B) `OnTriggerEnter()`
- C) `OnColliderEnter()`
- D) `StartTrigger()`

---

### 31. In Unity, which component is used to render 3D objects?

- A) `Rigidbody`
- B) `Collider`
- C) `Renderer`
- D) `AudioSource`

---

### 32. In Unity, which class must a script inherit from so it can be attached to a GameObject?

- A) `ScriptableObject`
- B) `MonoBehaviour`
- C) `GameObject`
- D) `Transform`

---

## Part B: Object-Oriented Programming

### 1. What is a class in C#?

- A) A blueprint that defines the data and behaviour of objects.
- B) A built-in Unity component that handles rendering.
- C) A specific instance of an object stored in memory.
- D) A variable used to group primitive types together.

---

### 2. What is the relationship between a class and an object in C#?

- A) A class is a single instance created from an object.
- B) An object is a specific instance created from a class.
- C) A class and an object are the same thing in memory.
- D) An object defines the blueprint that classes follow.

---

### 3. What keyword is used to create an instance of a class in C#?

- A) `new`
- B) `create`
- C) `instance`
- D) `init`

---

### 4. Which of the following is NOT a feature of object-oriented programming?

- A) Encapsulation
- B) Inheritance
- C) Polymorphism
- D) Compilation

---

### 5. What does encapsulation mean in object-oriented programming?

- A) Bundling data and methods together while restricting direct access to internal data.
- B) Allowing multiple classes to share the same base methods.
- C) Reusing code through inheritance.
- D) Creating multiple versions of a method.

---

### 6. What does inheritance allow in OOP?

- A) Multiple objects to exist from the same class.
- B) A class to take on the properties and methods of a parent (base) class.
- C) A class to define many different versions of a method.
- D) A class to encapsulate data into a single method.

---

### 7. Which of the following is used to make a class inherit from another class in C#?

- A) `inherit`
- B) `extends`
- C) `derives`
- D) `:`

---

### 8. What is polymorphism in OOP?

- A) Creating objects from multiple classes.
- B) The ability of the same method call to behave differently depending on the object it is called on.
- C) The process of hiding the internal state of an object.
- D) A way of inheriting multiple classes.

---

### 9. What is the purpose of the `virtual` keyword in C#?

- A) To prevent a method from being overridden.
- B) To declare a method that can be overridden by derived classes.
- C) To mark a class as abstract.
- D) To allow access from any namespace.

---

### 10. When overriding a virtual method from a parent class, which keyword is required in the child class?

- A) `extends`
- B) `implements`
- C) `virtual`
- D) `override`

---

### 11. What is abstraction in OOP?

- A) Reusing code by combining two unrelated classes.
- B) Hiding complex implementation details and exposing only the essential features.
- C) Sharing variables between unrelated objects.
- D) Turning public data into private fields.

---

### 12. Which statement best describes a constructor in C#?

- A) It is used to call the base class automatically.
- B) It must always return a value.
- C) It runs when a new object is created and is used to initialise values.
- D) It defines how data is hidden inside a class.

---

### 13. Which of the following statements about interfaces in C# is TRUE?

- A) Interfaces make a script run faster.
- B) A class can only implement one interface.
- C) Interfaces define method signatures without implementation.
- D) Interfaces must inherit from another class.

---

### 14. Why might a developer use an interface in a C# game project?

- A) To store player data in a file.
- B) To define a common set of methods that different classes must each implement.
- C) To prevent other scripts from accessing a class.
- D) To automatically optimise performance.

---

### 15. How does using an interface differ from inheriting from a base class?

- A) Interfaces are only used for building menus and UI.
- B) Inheritance cannot include shared behaviour.
- C) Interfaces cannot be used with Unity components.
- D) A class can implement multiple interfaces but only inherit from one base class.

---

### 16. What is the main purpose of using events in C#?

- A) To schedule timed actions in the game loop.
- B) To allow a class to notify other classes when something happens.
- C) To store player input values between frames.
- D) To pause and resume coroutines.

---

### 17. Which of the following is used to subscribe a method to an event?

- A) `attach`
- B) `add`
- C) `+=`
- D) `subscribe`

---

### 18. What is the purpose of passing parameters with a C# event?

- A) To delay the event until the parameters are ready.
- B) To allow the event to send data about what happened to any listening methods.
- C) To limit which objects can subscribe to the event.
- D) To make the event run only once.
