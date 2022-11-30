# Go Shell Utilities

*Native Go implementations of as many [standard] [utilities] as possible.*

The goal of this project is to implement [standard] POSIX shell utilities in pure Go.
Ideally without relying too heavily on external libraries.
POSIX is in no way perfect, but neither is a world where typing `make install` does something completely different on a user's machine as what you expected when you wrote the makefile.
My hope is that by implementing the tools that I rely on, I can gain a better understanding of how to use them.
And I hope that these alternative implementations will be of use to somebody, if not for practical use, then at least as an academic exercise.

## Contribution

If you'd like to contribute, please open a PR. Be sure to explain what your proposed changes do.
If you're unsure about something, or don't know how to make a change that you'd like to see, open an issue and I'll see what I can do 🙂

Please be sure to also read the [CODE_OF_CONDUCT.md] and [CONTRIBUTING.md] guidelines.

## Resources

A good place to start is looking at the actual [standard] itself.
It is full of technical documentation, which can be rather dense, so another good place to look is at a simple example such as the [true utility].

[standard]: https://pubs.opengroup.org/onlinepubs/9699919799
[utilities]: https://pubs.opengroup.org/onlinepubs/9699919799/utilities/contents.html
[true utility]: https://pubs.opengroup.org/onlinepubs/9699919799/utilities/true.html
[CONTRIBUTING.md]: https://github.com/goshutils/.github/blob/main/CONTRIBUTING.md
[CODE_OF_CONDUCT.md]: https://github.com/goshutils/.github/blob/main/CODE_OF_CONDUCT.md
[security policy]: https://github.com/goshutils/.github/security/policy
[security advisory]: https://github.com/goshutils/.github/security/advisories/new
