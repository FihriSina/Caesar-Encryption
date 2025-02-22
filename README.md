```markdown
# Caesar Cipher Python Implementation

This is a simple implementation of the Caesar Cipher encryption algorithm in Python. It shifts each letter in the input message by a given number of positions in the alphabet.

## About the Project

The project demonstrates how to implement a classic encryption technique called the Caesar Cipher. The algorithm works by shifting each letter of the message by a specific number (offset) within the alphabet, while leaving spaces unchanged.

This project was developed as part of my learning journey with **FreeCodeCamp**. The goal is to better understand encryption algorithms and how to implement them in Python.

## How it Works

The program takes two inputs:

1. `message` - The plain text you want to encrypt.
2. `offset` - The number by which to shift the letters in the message.

### Example

```python
text = 'Hello Zaira'
shift = 3
caesar(text, shift)
```

- The plain text "Hello Zaira" would be shifted by 3 positions to give the encrypted text "khoor cbldu".

## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/FihriSina/caesar-cipher.git
   ```

2. Run the script with Python:

   ```bash
   python caesar_cipher.py
   ```

3. Modify the `text` and `shift` variables to test different inputs and shifts.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements

- This project was created as part of my learning journey with **FreeCodeCamp**. The tutorial helped me understand how basic encryption algorithms work in Python.

```

