# Fix My Code Challenge

This directory contains the original challenge programs with focused fixes.
The solutions preserve the existing implementations and correct only the
faulty behavior.

## Tasks

- `0-fizzbuzz.py` - print `FizzBuzz` for multiples of 15
- `1-print_square.js` - parse square sizes as decimal numbers
- `2-sort.rb` - insert integers at the correct sorted position
- `3-user.py` - store and compare the hashed password correctly
- `4-delete_dnodeint` - maintain `prev` and `next` links after deletion

## Validation

```bash
./0-fizzbuzz.py 50
./1-print_square.js 10
ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
./3-user.py
gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c \
    free_dlistint.c print_dlistint.c add_dnodeint_end.c \
    delete_dnodeint_at_index.c -o delete_dnodeint
./delete_dnodeint
```

## Author

Aliyyiakbar Shirinli
