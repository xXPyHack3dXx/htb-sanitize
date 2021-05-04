# Sanitize
Solution to Hack The Box Challenge - Sanitize

### Problem

Can you escape the query context and log in as admin at my super secure login page?

### Solution

As the problem says the form is vuln to SQL Injection. Also when you complete the form it prints the SQL query as result in the HTML. So you must do an injection that escapes some validation and gain access as admin user to get the flag...

Username field
```
admin
```

Password field
```
' OR 1=1 --
```
