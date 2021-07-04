# Python-MD5
program in python to generate MD5 of string data as assigned by shapeAI for project.
in this program MD5 sum of a given string in Python. We will use a built-in function to find the sum. Let's first have a quick look over what is MD5 in Python.

#MD5 Hash in Python..

MD5 Hash is one of the hash functions available in Python's hashlib library. It is mainly used in cryptographic functions to perform hash calculations. Hash is also used to check the checksum of a file, password verification, fingerprint verification, build caches of large data sets, etc. It accepts a byte string and outputs the equivalent hexadecimal string of the encoded value. Encoding a string to an MD5 hash produces a 128-bit hash value.

Hashing algorithms typically act on binary data rather than text data, so you should be careful about which character encoding is used to convert from text to binary data before hashing. The result of a hash is also binary data. In this article, we will import hashlib library to use hashlib.md5() function to find the MD5 sum of the given string in Python.

#Example: Use hashlib.md5() to get MD5 Sum of a String
This method imports hashlib library of Python. The below example calls hashlib.md5() function with an argument as a byte string to return an MD5 hash object. It calls str.encode() with str as an argument to return an encoded string. hexdigest() function is then called to display the encoded data in hexadecimal format, else you can call digest() a function to display data in byte format. The md5 hash function encodes the string and the byte equivalent encoded string is printed.
EXAMPLE-
import hashlib
"""
#using hexdigest()
print hashlib.md5("This is a string").hexdigest()
print hashlib.md5("000005fab4534d05key9a055eb014e4e5d52write").hexdigest()
"""
