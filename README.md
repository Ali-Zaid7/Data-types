
## 📌 Python Data Types 
Python data types define the kind of value a variable can hold and how it behaves. This ensures data is stored, processed, and utilized efficiently.

[Python Data types](![image](https://github.com/user-attachments/assets/f362b6e7-0b47-47ee-8dad-531b6154f2bc)
)

# 1. Numeric Types
int – Whole numbers (e.g., 42)
float – Decimal numbers (e.g., 3.14)
complex – Real + Imaginary (e.g., 2 + 3j)
Access real/imaginary parts with .real and .imag

# 2. Boolean Type
bool – Represents True or False

# 3. Sequence Types
str – Text/characters enclosed in single ', double ", or triple quotes '''

list – Ordered, mutable collection (e.g., [1, "Python", 3.14])
tuple – Ordered, immutable collection (e.g., (1, "AI", 2.71))
range – Immutable sequence of numbers, commonly used in loops

# 4. Set Types
set – Unordered, mutable collection of unique values (e.g., {1, 2, 3})

frozenset – Immutable version of a set

# 5. Mapping Type
dict – Key-value pairs (e.g., {"name": "Alice", "age": 25})

# 6. Binary Types
Used for handling binary data like files or network data.

bytes – Immutable byte sequences (e.g., b"Hello")
bytearray – Mutable byte sequences; supports modification
memoryview – Views underlying binary data without copying

📍 Example:
```
ba = bytearray(b"hello")
ba[0] = 72  # 'H'
print(ba)   # bytearray(b'Hello')
```

# 7. Special Type: None
Represents no value or null
Singleton object (None is None is always True)
Used for optional/default variables

# 8. Number Systems & Encodings
Binary (base-2): 0, 1 – core language of computers
Octal (base-8): 0-7 – used in file permissions
Decimal (base-10): 0-9 – standard system
Hexadecimal (base-16): 0-9, A-F – compact binary representation
ASCII: Maps characters to values 0-127
UTF-8: Modern, variable-length Unicode encoding

📍 Example:
```
b = bytearray([65, 66, 67])
print(b.decode('utf-8'))  # 'ABC'
```
