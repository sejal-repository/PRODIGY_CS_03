# PRODIGY_CS_03
 # Task-03 Password Complexity Checker.

# ✅ Step 1: Import re module
   re stands for regular expressions, used to search for patterns in text (like letters, numbers, symbols). 
   We'll use it to check what types of characters are in the password.

# ✅ Step 2: Define a function to check password strength
 This function takes in one thing: the password you typed.
 It will analyze the password and return the strength + feedback.

# ✅ Step 3: Check each password rule (flags)
  This part checks if your password:
  Is too short (less than 8 characters)
  Is missing lowercase letters
  Is missing uppercase letters
  Is missing digits
  Is missing special characters (like @, #, !, etc.)
  If any of these are missing, the error will be True.
  
# ✅ Step 4: Count how many rules are followed 
  We count how many rules were broken by adding up the True errors.
  Then subtract from 5 to get how many good things your password has.
  For example, if only 1 rule is broken, then criteria_met = 4.
  
# ✅ Step 5: Decide password strength
  This part assigns a strength level based on how many rules your password follows.

# ✅ Step 6: Prepare feedback messages
  If your password breaks any rule, it adds a suggestion to the feedback list.

# ✅ Step 7: Return the result
  This gives back the strength level and the list of suggestions.

# ✅ Step 8: Ask the user for input
  You type in a password here when running the code.

# ✅ Step 9: Call the function and show results
  It runs the function using your input.
  Then it prints:
  The strength (like Strong)
  Any feedback to improve the password

# ✅ Summary
> What the code checks for:
✔️ Minimum 8 characters

✔️ Lowercase letters

✔️ Uppercase letters

✔️ Numbers

✔️ Special characters

It helps you understand what your password is missing and how to make it stronger.
