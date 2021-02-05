t: p; @echo t ;
	touch t
p: d; @echo execute recipe in p
	touch p -r d
clean: ; rm -vf p t
.PHONY: clean
