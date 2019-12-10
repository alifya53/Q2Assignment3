# Q2Assignment3

Q1: You are required to understand and implement the
example given in the book:

(https://doc.rust-lang.org/book/ch10-02-traits.html#using-tra
it-bounds-to-conditionally-implement-methods)

Optional:
Implement fn main() for the above example to illustrate the difference between
types that implement PartialOrd and Display traits and types that does not
implement PartialOrd and Display Trait, Add comments at the end of your code
to support your code.

Q2:Why Generic Type Parameter 'T' is bound with Display and PartialOrd Trait? (answer briefly) *

**ANSWER**
Because:
Pair<T> only implements the cmp_display if its inner type T implements the PartialOrd trait that enables comparison and the Display trait that enables printing
