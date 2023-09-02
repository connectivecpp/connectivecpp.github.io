# Connective C++ References

## Networking and Asynchronous Design

- Chris Kohlhoff is a networking expert (among other expertises, including C++), creator of the Asio library and initial author of the C++ Networking Technical Standard (TS). Asio is [available here](https://think-async.com/) as well as at Chris' [GitHub site](https://github.com/chriskohlhoff/). Asio forms the basis for the C++ Networking Technical Standard (TS), which will be standardized in C++ 23 or C++ 26 (or thereabouts). Currently the Chops Net IP library uses the stand-alone Asio repository from Chris' GitHub account.

- Vinnie Falco is the author of the Boost Beast library, available at [Boost.org](https://www.boost.org/). Beast is an excellent building block library for asynchronous (and synchronous) HTTP and WebSocket applications. The Beast library uses Asio. Vinnie is proficient in C++ including presenting at [CppCon](https://cppcon.org/) and is also active in blockchain development and other technology areas. Vinnie has a [GitHub site](https://github.com/vinniefalco). While Chops Net IP does not depend on Beast, the choices and design rationale made by Vinnie in implementing Beast are highly helpful.

- Kirk Shoop is a C++ expert, particularly in the area of asynchronous design, and has presented multiple times at [CppCon](https://cppcon.org/). He is a co-author of the [Unified Executors Proposal for C++](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2020/p0443r12.html) and has a [GitHub site](https://github.com/kirkshoop). 

## Concurrency

- Anthony Williams is the author of Concurrency in Action, Practical Multithreading. He is a recognized expert in concurrency including Boost Thread and C++ standards efforts. It is highly recommended to buy his book, whether in paper or electronic form, and there is now a second edition of Concurrency in Action. Anthony has a [web site](http://www.justsoftwaresolutions.co.uk) and a [GitHub site](https://github.com/anthonywilliams). 

## Useful Libraries

- Martin Moene is a C++ expert and member and former web editor of [accu-org](https://github.com/accu-org). He provides an excellent set of header-only libraries that implement many useful C++ library features, both C++ 17 as well as future C++ standards. These include `std::optional`, `std::variant`, `std::any`, and `std::byte` (from C++ 17) as well as `expected` and `ring_span` (possibly in a future C++ standard). He also has multiple other useful repositories including an implementation of the C++ Guideline Support Library (GSL). Martin has a [GitHub site](https://github.com/martinmoene). 

- Justas Masiulis provides a nice [circular buffer implementation](https://github.com/JustasMasiulis/circular_buffer) used in the Utility Rack `wait_queue` unit test.

## Blogs, Articles, and Examples

- Andrzej Krzemieński is a C++ expert and proficient [blog author](https://akrzemi1.wordpress.com/). This blog is influential, well written, and a significant portion of the Chops code is directly influenced by it.

- Bjørn Reese [blogs about](http://breese.github.io/blog/) many topics in C++ at the expert level and is active with the Boost organization. 

- Richard Hodges is a prolific C++ expert with over 1,900 answers on StackOverflow as well as numerous discussions relating to C++ standardization and has a [GitHub site](https://github.com/madmongo1).

- Vittorio Romeo is a blog author and C++ expert with a [web site](https://vittorioromeo.info/) and a [GitHub site](https://github.com/SuperV1234). Vittorio's blog is excellent and well worth reading.

- Blitz Rakete is a student software developer who has the user id of Rakete1111 on many forums and sites (including Stackoverflow) and has a [GitHub site](https://github.com/Rakete1111).

- Anders Schau Knatten has a [C++ blog](https://blog.knatten.org/) and is the creator and main editor of the [C++ quiz site](http://cppquiz.org/). One of the best overviews of lvalues, rvalues, glvalues, prvalues, and xvalues is [available here](https://blog.knatten.org/2018/03/09/lvalues-rvalues-glvalues-prvalues-xvalues-help/).

- Jonathan Müller is very active in the C++ universe and is well known as "foonathan". His has a [blog](https://foonathan.net/) and his article [Rvalue References in APIs](http://foonathan.net/blog/2018/03/26/rvalue-references-api-guidelines.html) is a must read for library designers.

## Build Tools

- Modern CMake design is important, although not a lot of reference material is available. See Daniel Pfeifer's C++Now 2017 talk on [Effective CMake](https://www.youtube.com/watch?v=bsXLMQ6WgIk) and Manuel Binna's [GitHub page](https://gist.github.com/mbinna/c61dbb39bca0e4fb7d1f73b0d66a4fd1).

- An excellent book is [Professional CMake, A Practical Guide](https://crascit.com/professional-cmake/) by Craig Scott.

- [Effective CMake](https://leanpub.com/effective-cmake), by Kai Wolf, is under development. Another book is under [development on GitHub](https://cliutils.gitlab.io/modern-cmake/).


## Unit Testing

- Phil Nash is the author of the Catch C++ unit testing library. The Catch library is [available here](https://github.com/catchorg/Catch2).

## Documentation

- Sy Brand's [article on writing clear documentation](https://devblogs.microsoft.com/cppblog/clear-functional-c-documentation-with-sphinx-breathe-doxygen-cmake/) has been invaluable. In addition, Sy is a well known C++ expert and presenter, known as TartanLLama, and his blog is [available here](https://blog.tartanllama.xyz).

- Diagrams in the Connective C++ documentation are created using [draw.io](https://www.draw.io/).

## Boost

- The Boost libraries collection is a high quality set of C++ libraries, [available here](https://www.boost.org/).
