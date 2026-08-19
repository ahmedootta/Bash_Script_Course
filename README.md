# Bash Script Problems

Small shell-scripting exercises from the ITI Bash course — practicing `case`
statements, pattern matching, and file permission handling.

| Script | What it does |
|---|---|
| `mycase` | Reads a single character and classifies it as uppercase, lowercase, a digit, or "Nothing" using a `case` statement. |
| `mycase2` | Reads a string and classifies it as all-uppercase, all-lowercase, all-digits, or a mix, using extended glob patterns (`+([A-Z])` etc.). |
| `mychmod` | Loops over files in a home directory and makes them executable (`chmod u+x`). |

## Run

```bash
chmod +x mycase && ./mycase
```
