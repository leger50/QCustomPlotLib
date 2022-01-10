# Changelog

All notable changes to this project will be documented in this file.  
The format is based on [Keep a Changelog] and this project adheres to [Semantic Versioning].

## [next] - 2.1.x

## [2.1.0] - 2022-01-10

Creation of the repository which provides :
- **QCustomPlot** library compliant with _Cmake_ projects (`.pro` file has been replaced by `CMakeLists.txt`)
- Hide _Qt dependencies_, callers no longer needed to add mandatory modules of the library in their own _CMakeLists_ project (like `printsupport` module for example)
- Add a `config.h.in` file in order to know which version of the library we are using from the caller project (multiple macros are defined, like `QCP_LIB_VERSION` for example).

<!-- Links -->
[keep a changelog]: https://keepachangelog.com/en/1.0.0/
[semantic versioning]: https://semver.org/spec/v2.0.0.html

<!-- Versions -->
[next]: https://github.com/leger50/QCustomPlot-library/compare/2.1.0...dev
[0.0.2]: https://github.com/Author/Repository/compare/v0.0.1...v0.0.2
[2.1.0]: https://github.com/leger50/QCustomPlot-library/releases/tag/2.1.0