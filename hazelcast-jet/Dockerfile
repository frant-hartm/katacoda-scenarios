FROM hazelcast-jet:SNAPSHOT

WORKDIR /opt/hazelcast-jet

ADD setup.jsh ./

CMD jshell --class-path "lib/*"  setup.jsh

