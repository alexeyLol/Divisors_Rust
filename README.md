# Multipliers_VERY_FAST
Very FAST code for finding the multipliers of a number (Rust, C++, Python)

MANUAL

I recommend using the code in Rust or C++ (because Python is too slow).

The first step: enter number (for C++ and Rust: 0 <= number < 2^64)
The second step: program will print all multipliers

OUTPUT FORMAT

#  This program returns multipliers of a number.
#  Enter the number: 1234567890                     # YOUR NUMBER
#  ----------
#  2 ^1                                             # Multiplier 1
#  3 ^2                                             # Multiplier 2
#  5 ^1                                             # Multiplier 3
#  3607 ^1                                          # Multiplier 4
#  3803 ^1                                          # Multiplier 5
#  ----------
#  Finished

All multipliers are PRIME NUMBERS (2, 3, 5, 3607, 3803)

3 ^2    # Here '3' is a prime multiplier, '^2' is the DEGREE (3^2 <=> 3 * 3)
Indeed, 2 * 3 * 3 * 5 * 3607 * 3803 = 1234567890
