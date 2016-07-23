
* [C.4: Make a function a member only if it needs direct access to the representation of a class](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md#Rc-member)
  I first saw this one in a Scott Meyers book.
  It makes sense: fight class bloat, keep each class as small and thus as understandable as possible.
  
* [T.84: Use a non-template core implementation to provide an ABI-stable interface](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md#Rt-abi)
  E.g., Give an intrusive reference counting smart pointer a concrete base class which does the incing and decing
  and have the derived template smart pointer be a type-safe wrapper which mostly generates no additional code.
  E.g., for a generic container of pointers, have a concrete base class of void pointers which does most of the work.

| [Edit](https://github.com/ahcox/ahcox.com/edit/master/cpp/cpp-core-guidelines.md) | [View](http://ahcox.com/cpp/cpp-core-guidelines/) |
| --------------------------------------------------------------------------------- | ------------------------------------------------- |
