Bit manipulation Quiz
Question #0
What is 0x89 in base10?
137
Question #1
What is 0x89 in base2?
0b10001001
Question #2
What is 0b001010010 in base10?
82
Question #3
What is 0b01101101 in base16?
0x6D
Question #4
What is 98 in base2?
0b01100010
Question #5
What is 98 in base16?
0x62
Question #6
0x01 & 0x01 = ?
0x01
Question #7
0x01 | 0x01 = ?
0x01
Question #8
0x01 & 0x00 = ?
0x00
Question #9
0x01 | 0x00 = ?
0x01
Question #10
0x66 & 0x22 = ?
0x22
Question #11
0x44 | 0x22 = ?
0x66
Question #12
0x89 & 0x01 = ?
0x01
Question #13
0x88 & 0x01 = ?
0x00
Question #14
0x02 >> 1 = ?
0x01
Question #15
0x89 >> 3 = ?
0x11
Question #16
0x01 << 1 = ?
0x02
Question #17
0x13 << 1 = ?
0x26
Question #18
~ 0x12 = ?
0xED
Question #19
~ 0x98 = ?
0x67

TASKS
0. Write a function that converts a binary number to an unsigned int.

Prototype: unsigned int binary_to_uint(const char *b);
where b is pointing to a string of 0 and 1 chars
Return: the converted number, or 0 if
there is one or more chars in the string b that is not 0 or 1
b is NULL

1.Write a function that prints the binary representation of a number.

Prototype: void print_binary(unsigned long int n);
Format: see example
You are not allowed to use arrays
You are not allowed to use malloc
You are not allowed to use the % or / operators

2.Write a function that returns the value of a bit at a given index.

Prototype: int get_bit(unsigned long int n, unsigned int index);
where index is the index, starting from 0 of the bit you want to get
Returns: the value of the bit at index index or -1 if an error occured
3.Write a function that sets the value of a bit to 1 at a given index.

Prototype: int set_bit(unsigned long int *n, unsigned int index);
where index is the index, starting from 0 of the bit you want to set
Returns: 1 if it worked, or -1 if an error occurred

4.Write a function that sets the value of a bit to 0 at a given index.

Prototype: int clear_bit(unsigned long int *n, unsigned int index);
where index is the index, starting from 0 of the bit you want to set
Returns: 1 if it worked, or -1 if an error occurred

5.Write a function that returns the number of bits you would need to flip to get from one number to another.

Prototype: unsigned int flip_bits(unsigned long int n, unsigned long int m);
You are not allowed to use the % or / operators

6.Write a function that checks the endianness.

Prototype: int get_endianness(void);
Returns: 0 if big endian, 1 if little endian

7.Find the password for this program.

Save the password in the file 101-password
Your file should contain the exact password, no new line, no extra space


