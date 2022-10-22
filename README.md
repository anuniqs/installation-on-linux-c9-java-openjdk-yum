### OpenJDK Installation — YUM

**Site address :** https://adoptium.net/temurin/releases/

`[anup@c9-250-server ~]$ sudo yum install java-11-openjdk`

`[anup@c9-250-server ~]$ sudo yum install java-11-openjdk-devel`

`[anup@c9-250-server ~]$ sudo yum install java-11-openjdk-headless`

`[anup@c9-250-server ~]$ java -version`

`[anup@c9-250-server ~]$ javac -version`

<br>

`[anup@c9-250-server ~]$ sudo yum install java-17-openjdk-headless`

`[anup@c9-250-server ~]$ java -version`

`[anup@c9-250-server ~]$ javac -version`

<br>

`[anup@c9-250-server ~]$ update-alternatives --config java`

`[anup@c9-250-server ~]$ java -version`

`[anup@c9-250-server ~]$ javac -version`


`[anup@c9-250-server ~]$ java -version`

`[anup@c9-250-server ~]$ sudo yum install java-17-openjdk-devel`

`[anup@c9-250-server ~]$ javac -version`

<br>

`[anup@c9-250-server ~]$ echo $JAVA_HOME`

`[anup@c9-250-server ~]$ whereis java`

`[anup@c9-250-server ~]$ update-alternatives --config java`

`[anup@c9-250-server ~]$ update-alternatives --display java`

`[anup@c9-250-server ~]$ ls -ltr /usr/lib/jvm/`

`[anup@c9-250-server ~]$ sudo nano /etc/environment`

    JAVA_HOME=/usr/lib/jvm/java-11-openjdk-11.0.17.0.7-0.2.ea.el9.x86_64/ 
    export JAVA_HOME

`[anup@c9-250-server ~]$ . /etc/environment`

`[anup@c9-250-server ~]$ echo $JAVA_HOME`

`[anup@c9-250-server ~]$ export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-11.0.17.0.7-0.2.ea.el9.x86_64/`

`[anup@c9-250-server ~]$ export PATH=$PATH:/usr/lib/jvm/java-11-openjdk-11.0.17.0.7-0.2.ea.el9.x86_64/bin/`

`[anup@c9-250-server ~]$ echo $JAVA_HOME`

`[anup@c9-250-server ~]$ echo $PATH`

`[anup@c9-250-server ~]$ echo $JAVA_HOME`

`[anup@c9-250-server ~]$ nano .bash_profile`

    JAVA_HOME=/usr/lib/jvm/java-11-openjdk-11.0.17.0.7-0.2.ea.el9.x86_64/ 
    export JAVA_HOME

`[anup@c9-250-server ~]$ echo $JAVA_HOME`

`[anup@c9-250-server ~]$ source ~/.bash_profile`

`[anup@c9-250-server ~]$ echo $JAVA_HOME`

<br>

`[anup@c9-250-server ~]$ sudo yum remove java-11-openjdk-headless.x86_64`

`[anup@c9-250-server ~]$ java -version`

`[anup@c9-250-server ~]$ update-alternatives --config java`
