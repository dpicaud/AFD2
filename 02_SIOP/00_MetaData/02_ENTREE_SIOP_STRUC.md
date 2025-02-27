<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.kafka.server" id="_fgGuoNc2Ee-ayYrzKU_LEQ" name="EntreeSIOP" md:ref="resource.tech#UUID_DEF_TECH_KAFKA_STRUCT?fileId=UUID_DEF_TECH_KAFKA_STRUCT$type=tech$name=kafka%20structured?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.kafka.server.module" id="_fgH8wNc2Ee-ayYrzKU_LEQ" value="Kafka"/>
  <attribute defType="com.stambia.kafka.server.serverProperties" id="_73HjkOe1Ee-hG9BZ5Z_6Fg" value="bootstrap.servers=frpardevkfk01:9092,frpardevkfk02:9092,frpardevkfk03:9092&#xD;&#xA;security.protocol=SSL&#xD;&#xA;ssl.key.password=kafka.devreftiers.afd.fr&#xD;&#xA;ssl.keystore.location=/semarchy_xdi/semarchy-xdi-runtime/certificat_ssl/keystore_kafka.devreftiers.afd.fr.jks&#xD;&#xA;ssl.keystore.password=kafka.devreftiers.afd.fr&#xD;&#xA;ssl.truststore.location=/semarchy_xdi/semarchy-xdi-runtime/certificat_ssl/truststore.jks&#xD;&#xA;ssl.truststore.password=changeme"/>
  <node defType="com.stambia.kafka.topic" id="_paDPQNc2Ee-ayYrzKU_LEQ" name="dev-back.ref-tiers.retour-majtiers.prv.c2.1">
    <attribute defType="com.stambia.kafka.topic.physicalName" id="_r5g7UNc2Ee-ayYrzKU_LEQ" value="dev-back.ref-tiers.retour-majtiers.prv.c2.1"/>
    <attribute defType="com.stambia.kafka.topic.producerProperties" id="_2roi4OfFEe-hG9BZ5Z_6Fg" value=""/>
    <node defType="com.stambia.kafka.valueField" id="_8Qmegdc2Ee-ayYrzKU_LEQ">
      <attribute defType="com.stambia.kafka.valueField.type" id="_9RZ0MNc2Ee-ayYrzKU_LEQ" value="bytes"/>
      <attribute defType="com.stambia.kafka.valueField.schema" id="_-RAy0PBrEe-60dBp80p0Rg" ref="resource.md#_nvojkNcwEe-ayYrzKU_LEQ?fileId=_np5vANcwEe-ayYrzKU_LEQ$type=md$name=01_SIOP_JSON?"/>
    </node>
    <node defType="com.stambia.kafka.keyField" id="_n1CpMOhhEe-hG9BZ5Z_6Fg">
      <attribute defType="com.stambia.kafka.keyField.type" id="_PSalwOrDEe-4q5GBG05Ffg" value="bytes"/>
    </node>
  </node>
  <node defType="com.stambia.kafka.monoconsumer" id="_xU2iodc2Ee-ayYrzKU_LEQ" name="ConsommationSIOP">
    <attribute defType="com.stambia.kafka.monoconsumer.consumerGroupName" id="_ziHrcNc2Ee-ayYrzKU_LEQ" value="GROUP.dev-back.ref-tiers.retour-majtiers.prv.c2.1"/>
    <attribute defType="com.stambia.kafka.monoconsumer.topic" id="_16db0Nc2Ee-ayYrzKU_LEQ" ref="resource.md#_paDPQNc2Ee-ayYrzKU_LEQ?fileId=_fgGuoNc2Ee-ayYrzKU_LEQ$type=md$name=dev-back.ref-tiers.retour-majtiers.prv.c2.1?"/>
  </node>
</md:node>