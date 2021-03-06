[![Build][build-badge]][build-link]
[![Docs][docs-badge]][docs-build-link]
[![codecov][codecov-badge]][codecov-link]
[![coveralls][coveralls-badge]][coveralls-link]
[![MIT License][license-badge]](LICENSE.md)

# Cmake - Googletest - CI

Minimal [template][template-link] CMake project with Googletest, and Continuous Integration with GitHub actions.

On each commit push or pull request, the CI does the following:
 - **Build and test**
   - builds the code on a combination of OSes (Linux, Windows, Mac), compilers (gcc, clang, cl.exe), and modes (release, debug)
   - runs tests on each build combination
 - **Code coverage**
   - computes code coverage based on tests
   - uploads code coverage results to [codecov.io][codecov-link] and [coveralls.io][coveralls-link]
 - **Documentation**
   - builds documentation with Doxygen 
   - uploads documentation to [GitHub pages][docs-link]

[build-badge]:     https://img.shields.io/github/workflow/status/gmargari/cmake-gtest-ci/Build?label=build&style=plastic&logo=github
[build-link]:      https://github.com/gmargari/cmake-gtest-ci/actions?query=workflow%3ABuild
[docs-badge]:      https://img.shields.io/github/workflow/status/gmargari/cmake-gtest-ci/Documentation?label=docs&style=plastic&logo=github
[docs-build-link]: https://github.com/gmargari/cmake-gtest-ci/actions?query=workflow%3ADocumentation
[codecov-badge]:   https://img.shields.io/codecov/c/github/gmargari/cmake-gtest-ci?label=coverage&style=plastic&logo=codecov
[codecov-link]:    https://codecov.io/github/gmargari/cmake-gtest-ci
[coveralls-badge]: https://img.shields.io/coveralls/github/gmargari/cmake-gtest-ci?label=coverage&style=plastic&logo=coveralls
[coveralls-link]:  https://coveralls.io/github/gmargari/cmake-gtest-ci
[license-badge]:   https://img.shields.io/github/license/gmargari/cmake-gtest-ci?label=license&style=plastic&color=blue
[template-link]:   https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template
[docs-link]:       https://gmargari.github.io/cmake-gtest-ci/
