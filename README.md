# IKumo

POC of getting all Apple devices asociated with an account.
It will return data such as: Device Name, Device Model, Battery % and Location (Google Map URL)

P.S: Even if 2FA is activated on the account, it will still be displaying the data.

P.S 2: Be aware: after several intents against an account (trying incorrect passwords) will result on a blocked Apple account, where the user will need to change the password in order to re-activate.

## Single Password:
```bash
python3 i-kumo.py --appleid example@mail.com --password Password123
```

## Dictionary:
```bash
python3 i-kumo.py --appleid example@mail.com --password-list dictionary.txt
```
