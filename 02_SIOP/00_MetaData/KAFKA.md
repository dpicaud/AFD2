<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.kafka.server" id="_4ccnkNPtEe-ayYrzKU_LEQ" name="EntreeSIOP" md:ref="resource.tech#UUID_DEF_TECH_KAFKA?fileId=UUID_DEF_TECH_KAFKA$type=tech$name=kafka?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.kafka.server.driver" id="_4cfq4NPtEe-ayYrzKU_LEQ" value="com.semarchy.xdi.jdbc.kafka.KafkaDriver"/>
  <attribute defType="com.stambia.kafka.server.module" id="_4cfq4dPtEe-ayYrzKU_LEQ" value="Kafka"/>
  <attribute defType="com.stambia.kafka.server.bootstrapServers" id="_7lomENPtEe-ayYrzKU_LEQ" value="frpardevkfk01:9092,frpardevkfk02:9092,frpardevkfk03:9092"/>
  <attribute defType="com.stambia.kafka.server.ssl" id="_ASJ_kNPuEe-ayYrzKU_LEQ" value="true"/>
  <attribute defType="com.stambia.kafka.server.sslKeyPassword" id="_RAV0INPuEe-ayYrzKU_LEQ" value="C7E3BE6DF993E1C1F44F1771C12F7CC863486BA2A46ECF530F1852AA9AF25274"/>
  <attribute defType="com.stambia.kafka.server.sslKeyStoreType" id="_UYNH0NPuEe-ayYrzKU_LEQ" value="JKS"/>
  <attribute defType="com.stambia.kafka.server.sslKeyStoreLocation" id="_VMPM0NPuEe-ayYrzKU_LEQ" value="/semarchy_xdi/semarchy-xdi-runtime/certificat_ssl/keystore_kafka.devreftiers.afd.fr.jks"/>
  <attribute defType="com.stambia.kafka.server.sslKeyStorePassword" id="_a0f10NPuEe-ayYrzKU_LEQ" value="C7E3BE6DF993E1C1F44F1771C12F7CC863486BA2A46ECF530F1852AA9AF25274"/>
  <attribute defType="com.stambia.kafka.server.sslTrustStoreType" id="_crtPENPuEe-ayYrzKU_LEQ" value="JKS"/>
  <attribute defType="com.stambia.kafka.server.sslTrustStoreLocation" id="_dWiUwNPuEe-ayYrzKU_LEQ" value="/semarchy_xdi/semarchy-xdi-runtime/certificat_ssl/truststore.jks"/>
  <attribute defType="com.stambia.kafka.server.sslTrustStorePassword" id="_gKIdwNPuEe-ayYrzKU_LEQ" value="6929964D4514864E3D49919A12C2587F"/>
  <attribute defType="com.stambia.kafka.server.sslProtocol" id="_OhXEoNS8Ee-ayYrzKU_LEQ" value=""/>
  <attribute defType="com.stambia.kafka.server.otherConnectionProperties" id="_qdQc4NS-Ee-ayYrzKU_LEQ" value=""/>
  <externalize defType="com.stambia.kafka.server.sslProtocol" enable="false"/>
  <externalize defType="com.stambia.kafka.server.sslKeyPassword" enable="false"/>
  <node defType="com.stambia.kafka.consumer" id="_lWU10dPuEe-ayYrzKU_LEQ" name="ConsommationSIOP">
    <attribute defType="com.stambia.kafka.consumer.topicsSubscribed" id="_7LP6sNPuEe-ayYrzKU_LEQ">
      <refs>resource.md#_vJlfoNPuEe-ayYrzKU_LEQ?fileId=_4ccnkNPtEe-ayYrzKU_LEQ$type=md$name=dev-back.ref-tiers.retour-majtiers.prv.c2.1?</refs>
    </attribute>
    <attribute defType="com.stambia.kafka.consumer.consumerGroupName" id="_QSgAMNS-Ee-ayYrzKU_LEQ" value="kafka.devreftiers.afd.fr"/>
    <node defType="com.stambia.kafka.valueField" id="_NixrodPvEe-ayYrzKU_LEQ">
      <attribute defType="com.stambia.kafka.valueField.type" id="_PMyWYNPvEe-ayYrzKU_LEQ" value="string"/>
    </node>
  </node>
  <node defType="com.stambia.kafka.topic" id="_vJlfoNPuEe-ayYrzKU_LEQ" name="dev-back.ref-tiers.retour-majtiers.prv.c2.1">
    <attribute defType="com.stambia.kafka.topic.physicalName" id="_q9HigNTbEe-ayYrzKU_LEQ" value="dev-back.ref-tiers.retour-majtiers.prv.c2.1"/>
    <node defType="com.stambia.kafka.valueField" id="_v60vUdPuEe-ayYrzKU_LEQ">
      <attribute defType="com.stambia.kafka.valueField.type" id="_00qMENPuEe-ayYrzKU_LEQ" value="string"/>
    </node>
  </node>
</md:node>