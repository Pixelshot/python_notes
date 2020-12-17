---
description: >-
  When we want to document our function and make it appear on tooltip for our
  future self or others. This helps everyone understand the purpose of the
  function
---

# Docstrings

```python
def format_name(f_name, l_name):
        """Take a first and last name and format it to return the title case version of the name."""
        if f_name == "" or l_name == "":
                return "You didn't provide valid inputs."
        formated_f_name = f_name.title()
        formated_l_name = l_name.title()
        return f"Result: {formated_f_name} {formated_l_name}"
```

