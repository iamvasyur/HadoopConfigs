# HadoopConfigs

    ~/.bashrc
    /usr/local/hadoop/etc/hadoop/hadoop-env.sh
    /usr/local/hadoop/etc/hadoop/core-site.xml
    /usr/local/hadoop/etc/hadoop/mapred-site.xml.template
    /usr/local/hadoop/etc/hadoop/hdfs-site.xml


////

To format hdfs

hadoop namenode -format

If this command is executed again after Hadoop has been used, it'll destroy all the data on the Hadoop file system.

To start We can use start-all.sh or (start-dfs.sh and start-yarn.sh)


jps - to check that it is up and running

Example of output 

9026 NodeManager
7348 NameNode
9766 Jps
8887 ResourceManager
7507 DataNode



http://localhost:50070/ - web UI of the NameNode daemon

