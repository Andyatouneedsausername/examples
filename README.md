# CS3560 - Example Project

Example project that uses Doxygen, Makefile, Catch2, Travis CI.
Also used for students to practice pull requests

This is a simple project that contain some of the tools used in the class. For example,

- .gitignore
- Git with commit message in Commitizen convention ([https://commitizen.github.io/cz-cli/](https://commitizen.github.io/cz-cli/)).
- Makefile
- Doxygen with Netlify
- Catch2
- Travis CI (The idea of integrating this into class is heavily influenced by Mr. Robert Foreman).
- maybe Google Test Framework (using Docker image)

## Git with commit message in Commitizen convention

Some of commit message in this repository are following the Commitizen convention
([https://commitizen.github.io/cz-cli/](https://commitizen.github.io/cz-cli/)).

## Doxygen with Netlify

The `fib` example contains configuration of [Doxygen](http://www.doxygen.nl/) (`fib/Doxygfile`) and [Netlify](https://www.netlify.com/) (`netlify.toml`)
that automatically build doxygen (using `cd fib && make doc`), and publish the generated document
to [https://ou-cs3560-examples.netlify.com/](https://ou-cs3560-examples.netlify.com/).
