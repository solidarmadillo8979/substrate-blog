```markdown
# echo – Print text to the terminal

**Command type:** Built-in shell command  
**Difficulty:** Beginner (1/10)

---

<!-- VIDEO PLACEHOLDER: Direct terminal screen recording – typing echo commands -->

## What It Does

`echo` prints whatever text you give it back to the terminal screen.

It's one of the simplest commands and is used to:

- Display messages
- Check if the terminal is working
- Output text to files (when combined with `>`)
- Debug shell scripts

---

## Syntax

```bash
echo [text]
```

Or with quotes (recommended for spaces):

```bash
echo "your text here"
```

---

## Examples

### Basic

```bash
echo hello
```

Output:
```text
hello
```

### With spaces

```bash
echo "hello substrate"
```

Output:
```text
hello substrate
```

### Without quotes (still works, but limited)

```bash
echo hello substrate
```

Output:
```text
hello substrate
```

*Note: Without quotes, multiple spaces get collapsed into one.*

---

## Common Use Cases

| Use | Command |
|-----|---------|
| Print a message | `echo "Done"` |
| Add text to a file | `echo "new line" >> file.txt` |
| Overwrite a file | `echo "new content" > file.txt` |
| Show a variable | `echo $HOME` |

---

## Try It Now (Termux)

Open Termux and type:

```bash
echo "The Substrate is listening"
```

You should see the same sentence printed below.

---

## Video Lesson

<!-- VIDEO PLACEHOLDER: Short (60 seconds) – Fast walkthrough of echo with examples -->

---

## Next Command

Coming soon: `ls` – List files in the current directory

---

👉 **Gamified Version:** [Void's Echo – A Story](../atlas/voids-echo.md)
```
