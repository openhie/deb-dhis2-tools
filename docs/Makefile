man: manual.xml
	mkdir -p ../pkg/usr/share/man/man1
	docbook2x-man manual.xml
	gzip -f -9  *.1
	cp -f *.1.gz ../pkg/usr/share/man/man1
	chmod 0644 ../pkg/usr/share/man/man1/*

clean:
	rm -f  *.gz
