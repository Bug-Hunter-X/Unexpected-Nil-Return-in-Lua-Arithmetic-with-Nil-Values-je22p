# Lua Nil Arithmetic Bug

This repository demonstrates an unexpected behavior in Lua when performing arithmetic operations with `nil` values.  The `foo` function attempts to add two numbers but returns `nil` if either input is `nil`. This behavior can lead to unexpected results and debugging challenges.  The solution demonstrates how to handle `nil` values appropriately to avoid this issue.