# UTF-8 Validation
## Resources
* [UTF-8](https://en.wikipedia.org/wiki/UTF-8)
* [Characters, Symbols, and the Unicode Miracle](https://www.youtube.com/watch?v=MijmeoH9LT4)

## Task
Write a method that determines if a given data set represents a valid UTF-8 encoding.

* Prototype: `def validUTF8(data)```
* Return: `True` if data is a valid UTF-8 encoding, else return `False`
* A character in UTF-8 can be 1 to 4 bytes long
* The data set can contain multiple characters
* The data will be represented by a list of integers
* Each integer represents 1 byte of data, therefore you only need to handle the 8 least significant bits of each integer

```
carrie@ubuntu:~/0x04-utf8_validation$ ./0-main.py
True
True
False
carrie@ubuntu:~/0x04-utf8_validation$
```

File: [0-validate_utf8.py](./0-validate_utf8.py)
