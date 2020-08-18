# Password Checker

This is a simple Python script that makes a call to the https://haveibeenpwned.com/ API which is basically like one big databased of leaked passwords and checks via sha encryption if the password paramter has ever been leaked.

## How does it work:

It's quite easy, you just run the script in your terminal window and pass the password you want to check as an argument:
```
python .\check_my_pass.py password_you_want_to_check

```

* Example:
```
python .\check_my_pass.py password123
The password: password123 was found 123063 times... You should probably change your password!
```
