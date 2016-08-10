### C++ 14 Binary Literals
C++ 14 has added support for binary literals.
I.e., you can now write out the individual ones and zeros of an integer.
A binary literal integer is a sequence of ones and zeroes prefixed by `0b`.
While this may sound verbose it can be useful.
For instance, while testing a function which does some bitwise operations,
having the bits in the test code improves readability.
[For example](http://web.archive.org/web/20160610120206/https://codility.com/programmers/task/binary_gap/)
when counting the longest run of zeroes bounded by ones in an integer:

    REQUIRE(solution(0b10000001) == 6);
    REQUIRE(solution(0b100000001) == 7);
    REQUIRE(solution(0b0001110110011110001111000011111000) == 4);

[_Read more_](http://web.archive.org/web/20160710191639/http://www.informit.com/articles/article.aspx?p=2209021)


### C++ 11 Attribute Specifiers
C++ 11 added a construct called an _attribute_ which can be used to attach
implementation-specific metadata to most language entities.
The syntax is:

    [[...]]

Where the ellipses could be anything.

There are two standard attributes in C++ 11, `[[noreturn]]` and `[[carries_dependency]]`.
The first marks a function as never returning.
The second is used to propagate memory order dependencies into and out of functions.

C++ 14 adds `[[deprecated]]` and C++ 17 grows the list with `[[fallthrough]]` to be used in a switch
statement, `[[nodiscard]]`, and `[[maybe_unused]]` to suppress unused entity compiler warnings,
while the transactional memory TS utilises `[[optimize_for_synchronized]]`.
All other attributes are implementation-specific, although some may be widely
supported or at least compatible between **gcc** and **clang**.
