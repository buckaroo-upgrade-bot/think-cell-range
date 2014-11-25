range
=====

Ranges proposal as described in ISO WG21 [N3782](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2013/n3782.pdf)

Compile instructions:

	cmake ./Library/Utilities/Range/
	make

You might need to adapt the CMakeLists.txt in ./Library/Utilities/Range to find your boost include path.
We used boost 1.57 for all testing
(note: boost 1.57.0 has an issue [#10754](https://svn.boost.org/trac/boost/ticket/10754) which will break our build. Use the patch to fix this )

The Range specific code is under https://github.com/think-cell/range/tree/master/Library/Utilities/Range 

The tests and examples are in Library/Utilities/Range/*.t.cpp

Tested with:
* clang 3.5
* VC12 (== Visual Studio 2013)

