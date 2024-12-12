<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.kafka.server" id="_mQZRAJt9Ee-DKYFre3OFCQ" name="RetourSIOP" md:ref="resource.tech#UUID_DEF_TECH_KAFKA_STRUCT?fileId=UUID_DEF_TECH_KAFKA_STRUCT$type=tech$name=kafka%20structured?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.kafka.server.module" id="_mQbGMJt9Ee-DKYFre3OFCQ" value="Kafka"/>
  <attribute defType="com.stambia.kafka.server.serverProperties" id="_vU6lgJt9Ee-DKYFre3OFCQ" value=""/>
  <configuration id="_p3FD0Jt9Ee-DKYFre3OFCQ" name="Dev">
    <attribute defType="com.stambia.kafka.server.serverProperties" id="_sKxkwJt9Ee-DKYFre3OFCQ" value="newValue"/>
  </configuration>
  <node defType="com.stambia.kafka.monoconsumer" id="_nJSn4Zt9Ee-DKYFre3OFCQ" name="SIOP">
    <attribute defType="com.stambia.kafka.monoconsumer.consumerGroupName" id="_2wMqAJzrEe-DKYFre3OFCQ" value="SIOP"/>
    <attribute defType="com.stambia.kafka.monoconsumer.pollTimeout" id="_21YsAJzrEe-DKYFre3OFCQ" value="10000"/>
    <attribute defType="com.stambia.kafka.monoconsumer.readMaxPollCalls" id="_264QAJzrEe-DKYFre3OFCQ" value="-1"/>
    <attribute defType="com.stambia.kafka.monoconsumer.readTimeout" id="_2-j2IJzrEe-DKYFre3OFCQ" value="-1"/>
    <attribute defType="com.stambia.kafka.monoconsumer.consumerProperties" id="_3CO1MJzrEe-DKYFre3OFCQ" value=""/>
  </node>
</md:node>