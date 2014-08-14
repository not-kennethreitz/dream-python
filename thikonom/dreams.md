# Dreams

## Technical

### Pattern Matching

Pattern matching is a powerful programming feature adopted by various programming languages that I would love to see in newer versions of Python.
Here is an example from `Rust` which shows how to match against an integer value:

        fn print_number(n: int) {
          match n {
            x if x < 0    => println!("less than zero"),
            0             => println!("zero"),
            1 | 2         => println!("one or two"),
            y @ 3..10     => println!("3 <= {} <= 10", y),
            _             => println!("greater than 10")
          }
        }
