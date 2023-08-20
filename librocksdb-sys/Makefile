include rocksdb/src.mk
include rocksdb/plugin/speedb/speedb.mk

rocksdb_lib_sources.txt: rocksdb/src.mk rocksdb/plugin/speedb/speedb.mk
	@echo "${LIB_SOURCES}" | tr ' ' '\n' > rocksdb_lib_sources.txt
	@echo "${speedb_SOURCES}" | tr ' ' '\n' >> rocksdb_lib_sources.txt

gen_lib_sources: rocksdb_lib_sources.txt
