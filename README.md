# Pincrack

### What this is

Crack your pre-registration advising pin. Useful if your academic advisor is unavailable.

### Usage

- Change the values of `app_username` and `app_password` to your username and password.
- Change the value of `term_in=201610` or whatever is the latest to reflect the current semester.

```sh
$ ./begin.sh
```

### Example

```sh
000000
000001
000002
...
000354
000356
000357
000358
Pin found 000358
```

### Note 
Be careful with this, The school hasn't said anything about this yet, however if a bunch of people start using this and bogging down the servers they will probably get mad. You can slow down the requests by uncommenting the 

```sh
#sleep .5
```
line 

### Another Note
You should still probably go see your academic advisor too.. Use this just to get your pin and register if your advisor can't meet prior to the registration deadline.
