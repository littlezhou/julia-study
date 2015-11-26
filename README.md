Setup:
	1. export LD_LIBRARY_PATH=path_to_libhdfs.so
	2. export CLASSPATH=$CLASSPATH:path_to_hadoop_jars

Run:
	Command: julia hdfs_rw.jl [NameNodeIP [Port]]
