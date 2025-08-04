# 0x03. Shell, init files, variables and expansions

### Author
Franklin Zyambo

---

## Task 0: <o>

**Objective:**  
Create a script that defines an alias.

**Details:**  
- **Alias name:** `ls`
- **Alias value:** `rm *`
- This means every time you type `ls`, it will actually run `rm *`, removing all files in the current directory.

**Script:**
```bash
#!/bin/bash
alias ls='rm *'
