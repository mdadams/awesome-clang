# Awesome Clang

> Useful resources and samples for using [Clang](http://clang.llvm.org/)-related tools, or for [building stuff on top of Clang](http://clang.llvm.org/docs/Tooling.html).

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Tools

### clang-format

- [clang-format docs](http://clang.llvm.org/docs/ClangFormat.html) - A tool to format C/C++/Java/JavaScript/Objective-C/Protobuf code.
- [style options](http://clang.llvm.org/docs/ClangFormatStyleOptions.html) - clang-format style options.
- [configurator](http://zed0.co.uk/clang-format-configurator/) -  clang-format configurator.

### clang-tidy

- [clang-tidy](http://clang.llvm.org/extra/clang-tidy/) - clang-based C++ linter tool.
- [List of clang-tidy checks](http://clang.llvm.org/extra/clang-tidy/checks/list.html)
- [Writing a basic clang static analysis check](https://bbannier.github.io/blog/2015/05/02/Writing-a-basic-clang-static-analysis-check.html)

## pp-trace

- [pp-trace](http://clang.llvm.org/extra/pp-trace.html) - tool that traces preprocessor activity.



### Clang static analyzer

- [Clang Static Analyzer](http://clang-analyzer.llvm.org/index.html) - a source code analysis tool that finds bugs in C, C++, and Objective-C programs.
- [scan-build](http://clang-analyzer.llvm.org/scan-build.html) -Running the analyzer from the command line.
- [Static Analysis with clang](http://btorpey.github.io/blog/2015/04/27/static-analysis-with-clang/)
- [CodeChecker](https://github.com/Ericsson/codechecker) - defect database and viewer extension for Clang Static Analyzer.

### AddressSanitizer

- [AddressSanitizer](http://clang.llvm.org/docs/AddressSanitizer.html) - a fast memory error detector.
- [Address Sanitizer](https://www.mikeash.com/pyblog/friday-qa-2015-07-03-address-sanitizer.html) - overview by Mike Ash.

## Libraries

### LibClang

- [libclang:](http://clang.llvm.org/doxygen/group__CINDEX.html) -  C Interface to Clang.
- [Introduction to libclang](https://www.mikeash.com/pyblog/friday-qa-2014-01-24-introduction-to-libclang.html)
- [LLVM & Clang library usage samples](https://github.com/eliben/llvm-clang-samples)
- [lloccount](https://github.com/neolynx/lloccount) - C/C++ Logical Lines Of Code Counter.
- [libclangmm](https://github.com/cppit/libclangmm) - C++-wrapper for libclang (developed for [juCi++](https://github.com/cppit/jucipp))
- [Customizable Naming Convention Checker](https://github.com/mapbox/cncc/) - similar to clang-format, but for naming conventions only.
- [irony-mode](https://github.com/Sarcasm/irony-mode) - A C/C++ minor mode for Emacs powered by libclang.
- [c99-to-c89](https://github.com/libav/c99-to-c89/) - Tool to convert C99 code to MSVC-compatible C89.
- [ClangKit](https://github.com/macmade/ClangKit) - Objective-C frontend to LibClang.

### LibTooling

- [LibTooling](http://clang.llvm.org/docs/LibTooling.html) - library to support writing standalone tools based on Clang
- [Tutorial for building tools using LibTooling and LibASTMatchers](http://clang.llvm.org/docs/LibASTMatchersTutorial.html)
- [Modern source-to-source transformation with Clang and libTooling](http://eli.thegreenplace.net/2014/05/01/modern-source-to-source-transformation-with-clang-and-libtooling)
- [AST matchers and Clang refactoring tools](http://eli.thegreenplace.net/2014/07/29/ast-matchers-and-clang-refactoring-tools)
- [Compilation databases for Clang-based tools](http://eli.thegreenplace.net/2014/05/21/compilation-databases-for-clang-based-tools)
- [LibTooling Example](https://kevinaboos.wordpress.com/2013/07/23/clang-tutorial-part-ii-libtooling-example/)

## Tips

Contributions welcome :)
