# Luhn Algorithm

This project implements the [Luhn algorithm](https://en.wikipedia.org/wiki/Luhn_algorithm), a simple checksum formula used to validate identification numbers such as credit card numbers.

## 🚀 Features

- Validates numeric strings using the Luhn formula
- Ignores spaces or dashes for cleaner input handling
- Returns boolean values or messages based on validity

## 📦 Usage

### Example

```python
from luhn import validate_card

print(validate_card("4539 1488 0343 6467"))  # True
print(validate_card("8273 1232 7352 0569"))  # False
