[**English**](README.md) | [Українська](README.uk.md)

# Address Book - Birthdays

CLI address book extended with birthday tracking and a "who's having a birthday in the next 7 days" query, including weekend roll-over (a Saturday/Sunday birthday is reported on the next Monday).

## Stack

- Python 3.12 (standard library only)

## Commands

| Command | Action |
|---------|--------|
| `add <name> <phone>` | Create a contact (10-digit phone validation) |
| `change <name> <old_phone> <new_phone>` | Update a phone |
| `phone <name>` | Show all phones for a contact |
| `add-birthday <name> <DD.MM.YYYY>` | Set the birthday |
| `show-birthday <name>` | Show one contact's birthday |
| `birthdays` | List birthdays in the next 7 days |
| `all` | List all contacts |
| `close` / `exit` | Exit |

## Run

```bash
python hw7.py
```
