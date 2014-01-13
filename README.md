Right click on build.xml and click Ant Build. Should produce a jar file. 

Best instructions I found so far were from https://docs.google.com/document/d/1yuZ4IjlquPkmC1zXtCeL4GUNKT1uY1xnS_SCBJHps6A/edit?pli=1

Make sure that you setup $HADOOP_HOME to where you have put Hadoop. I did it in my bashrc file (and then remember to source it.)

I also changed <property name="eclipse.home" value="/usr/local/HadoopEclipsePlugin/eclipse"/> to the location of eclipse on my machine in build-contrib.xml. (The file will start to mean something once you start playing around with it.)
