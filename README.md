# Algorithm_octal_close_friends

We define two non-negative integers to be close friends if their octal representations (without
leading zeros) are permutations of each other. For example, 519 (octal 1007) and 3592 (octal 7010) are
close friends while 347 (octal 533) and 1579 (3053) are not. As a special case, an integer is considered
to be a close friend of itself.

Design an algorithm CLOSEFRIEND (num1, num2) in pseudocode that takes two non-negative integers
as input, the algorithm should return TRUE if the two integers are close friends, FALSE otherwise.
