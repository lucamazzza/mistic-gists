# mistic-gists

A nice collection of dirty code snippets in various languages 

### 1. `if false:` but more efficient

```py
if data['project_id'] != data['project_id']:
```

### 2. Best way to comment your code

```py
if False:
  print(f"Cluster {ind_l}")
  print(f"Selected feature: {feat_list[0]}")
```

### 3. Hate for multiple `catch` clauses

```java
try {
  // ...
} catch (Exception e) {
  if (e instanceof InvalidLanguageException) {
    this.language = DEFAULT_LANGUAGE;
  }
  
  if (e instanceof InvalidBombsException) {
    this.bombs = DEFAULT_BOMBS;
  }
}
```

### 4. Eepy executor

```java
while (!executor.isTerminated()) {
    // zzz
}
```

### 5. PMS

```java
/* pages */
public String page1;
public String page2;
public String page3;
public String page4;
public String page5;
public String page6;
public String page7;
public String page8;
public String page9;
public String page10;
/* five more pages */
public String page11;
public String page12;
public String page13;
public String page14;
public String page15;
```

### 6. _Password is stored securely_

```cs
public IActionResult OnPost()
{

    const string AdminPassword = "abc1234!";

    if (Password == AdminPassword)
    {
        return RedirectToPage("/Admin/Index"); // success
    }

    ErrorMessage = "Incorrect password.";
    return Page();
}
```

