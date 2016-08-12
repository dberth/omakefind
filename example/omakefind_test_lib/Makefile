#Copyright (C) Denis Berthod 2016
# Released under MIT license

install:
	$(shell if ocamlfind query omakefind_test_lib > /dev/null ; then ocamlfind remove omakefind_test_lib; fi)
	ocamlfind install omakefind_test_lib META Test.om

uninstall:
	ocamlfind remove omakefind_test_lib
