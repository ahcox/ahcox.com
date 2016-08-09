
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
