all:
	cd thirdparty && make
	make -j8 -f Makefile_ptam

eclipse-project:
	make -f Makefile_ptam $@

.DEFAULT:
	cd thirdparty && make $@
	make -j8 -f Makefile_ptam $@


