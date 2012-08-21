git-szszk-bp-2k9.pdf: git-szszk-bp-2k9.txt objdb.eps gitk.eps rebase.eps
	a2beamer git-szszk-bp-2k9.txt

objdb.eps: objdb.dot
	dot -Teps -o objdb.eps objdb.dot

%.eps: %.png
	png2eps $< > $@

clean:
	rm -f *.eps *.xml *.pdf *.odp
