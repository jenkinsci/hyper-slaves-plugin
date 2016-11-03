go get github.com/pwaller/goupx

modify Makefile, change
	#upx -o $(DISTDIR)/$* $(DISTDIR)/$*.fat
to
	goupx $(DISTDIR)/$*.fat

make

