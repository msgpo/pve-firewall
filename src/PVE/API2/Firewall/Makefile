LIB_SOURCES=			\
	Aliases.pm		\
	IPSet.pm		\
	Rules.pm		\
	Cluster.pm		\
	Host.pm			\
	VM.pm			\
	Groups.pm

all:

.PHONY: install
install:
	install -d -m 0755 ${DESTDIR}${PERLDIR}/PVE/API2/Firewall
	for i in ${LIB_SOURCES}; do install -D -m 0644 $$i ${DESTDIR}${PERLDIR}/PVE/API2/Firewall/$$i; done	


.PHONY: clean
clean:
	rm -rf *~
