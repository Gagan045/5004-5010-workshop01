# Worksheet — Phase 4: Project anatomy

**Name:** Gagan

Read `handouts/project-anatomy.md` first.

---

### 1. Package to path

A class declares:

```java
package edu.northeastern.shelter;
```

Its file is called `Animal.java`. **Write the full path from the project root:**

`src/main/java/edu/northeastern/shelther/Animal.java`

---

### 2. The deep folders

**Why is the folder chain so deep? Give the actual reason, not "it is the convention".**

<br>This is enforced by the complier that the file name should match the class name.<br><br>

---

### 3. Break it on purpose

You move `Greeting.java` up one directory, leaving the `package` line untouched.

**What happens, and at what moment — writing, compiling, or running?**

<br>while Writing, the class cant be recongized<br>
 .While Compliing there will be a error and the code doesnt run
---

### 4. main vs test

| | `src/main/java` | `src/test/java` |
|---|---|---|
| What lives here? | Programs| Jnit tests(test cases)|
| Shipped to a user? | yes| no|
| Can use JUnit? | no| yes|

---

### 5. The same package, twice

`Greeting` is in `edu.northeastern.setup`. So is `GreetingTest`.

**Why is that deliberate? What does the test gain by sharing the package?**

<br>Tests are private class and to access the programs we need to folow the naming nomenclature if not we need to make the public.<br><br>

---

### 6. Access modifiers

For each, say who can see it:

| Declaration | Who can see it |
|---|---|
| `public int x;` | anyone in the package |
| `private int x;` |specific to class |
| `int x;` *(no modifier)* | everyone in the package|

**Which one depends on packages existing to mean anything at all?**

<br>Private.

---

### 7. Where does your work go?

| File | Which folder? |
|---|---|
| A new class you wrote |main/Java |
| A test you wrote | test/java|
| `LLM-Evaluation.md` | submission|
| Your code-walk video | canvas|
