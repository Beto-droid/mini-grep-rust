# Environment Variable: `IGNORE_CASE`

This variable controls whether the search function operates in **case-sensitive** or **case-insensitive** mode.

- **Case Sensitive**:  
  ```bash
  IGNORE_CASE=0
  ```

- **Case Insensitive**:  
  ```bash
  IGNORE_CASE=1
  ```

## Setting the Environment Variable

To set the environment variable for the current session:

```bash
export IGNORE_CASE=0  # Set to 0 for case-sensitive
export IGNORE_CASE=1  # Set to 1 for case-insensitive
```

## Checking the Environment Variable

1. **To check if the variable is set:**

   ```bash
   echo IGNORE_CASE
   ```

2. **To check the value of the variable:**

   ```bash
   echo $IGNORE_CASE
   ```

## Removing the Environment Variable from the Current Session

To unset (remove) the `IGNORE_CASE` environment variable:

```bash
unset IGNORE_CASE
```

---

## Summary

- Use `export` to set the environment variable.
- Use `unset` to remove it from the current session.
- Use `echo` to check whether it’s set and what its value is.

This configuration allows you to control case sensitivity dynamically during runtime.
