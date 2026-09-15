# Worksheet — Phase 3: The weekly loop

**Name:** ___________________________

---

### 1. Run the tests

```bash
./gradlew test
```

Tests passed: ________   Tests failed: ________

Is that the correct starting state for a fresh assignment? **Yes / No** — why?

<br><br>

---

### 2. Read one failure

Pick one failing test. Copy its name:

`_____________________ALL Passed in First attempt___________________`

**In your own words — not copied from the output — what did that test want the code to do?**

<br><br><br>

**Which file and method would you have to change to satisfy it?**

<br><br>

---

### 3. Make it pass, then re-run

Tests passed now: 2   Tests failed now: 0

---

### 4. Failing vs broken

Write the difference in one sentence each.

**A test failure means:**

<br>The Expected Output is not matching with the actual output.<br>

**A build error means:**

<br>While we run the code their might be any error while building like syntax error.<br>

**Which of the two should make you ask for help immediately?**

<br>

---

### 5. Find the reports

```bash
./gradlew jacocoTestReport checkstyleMain
```

Full path to the coverage report on your machine:

`Users/gagan/Projects/5004-5010-assignment00/build/reports/tests/test/index.html`

Full path to the checkstyle report:

`Users/gagan/Projects/5004-5010-assignment00/build/reports/chechsytle/test/index.html`

**Coverage says a number. Why is that number a poor target to aim at in this course?**
*(The provided tests already cover almost every line.)*

<br><br>

---

### 6. The wrapper

**Why must you run `./gradlew test` rather than `gradle test`?**

<br>we didnt install gradlew and we are gradlew wrapper class so we did to run this way<br>

**What would go wrong if you installed Gradle yourself and used that?**

<br>Installing a gradle may differ in version so this might break the exisiting plugins.so its better to use the wrapper class<br>
