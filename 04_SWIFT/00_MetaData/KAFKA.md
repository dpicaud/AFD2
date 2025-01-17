<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.kafka.server" id="_AOK6wNTbEe-ayYrzKU_LEQ" name="EntreeSWIFT" md:ref="resource.tech#UUID_DEF_TECH_KAFKA?fileId=UUID_DEF_TECH_KAFKA$type=tech$name=kafka?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.kafka.server.driver" id="_AOMv8NTbEe-ayYrzKU_LEQ" value="com.semarchy.xdi.jdbc.kafka.KafkaDriver"/>
  <attribute defType="com.stambia.kafka.server.module" id="_AONXANTbEe-ayYrzKU_LEQ" value="Kafka"/>
  <attribute defType="com.stambia.kafka.server.bootstrapServers" id="_IFA7MNTbEe-ayYrzKU_LEQ" value="frpardevkfk01:9092,frpardevkfk02:9092,frpardevkfk03:9092"/>
  <attribute defType="com.stambia.kafka.server.ssl" id="_LFUqgNTbEe-ayYrzKU_LEQ" value="true"/>
  <attribute defType="com.stambia.kafka.server.sslProtocol" id="_LghYwNTbEe-ayYrzKU_LEQ" value=""/>
  <attribute defType="com.stambia.kafka.server.sslKeyPassword" id="_LlGWwNTbEe-ayYrzKU_LEQ" value="C7E3BE6DF993E1C1F44F1771C12F7CC863486BA2A46ECF530F1852AA9AF25274"/>
  <attribute defType="com.stambia.kafka.server.sslKeyStoreType" id="_Lt0N4NTbEe-ayYrzKU_LEQ" value="JKS"/>
  <attribute defType="com.stambia.kafka.server.sslKeyStoreLocation" id="_LxU04NTbEe-ayYrzKU_LEQ" value="/semarchy_xdi/semarchy-xdi-runtime/certificat_ssl/keystore_kafka.devreftiers.afd.fr.jks"/>
  <attribute defType="com.stambia.kafka.server.sslKeyStorePassword" id="_L0ZXANTbEe-ayYrzKU_LEQ" value="C7E3BE6DF993E1C1F44F1771C12F7CC863486BA2A46ECF530F1852AA9AF25274"/>
  <attribute defType="com.stambia.kafka.server.sslTrustStoreType" id="_L3dSENTbEe-ayYrzKU_LEQ" value="JKS"/>
  <attribute defType="com.stambia.kafka.server.sslTrustStoreLocation" id="_L6zhANTbEe-ayYrzKU_LEQ" value="/semarchy_xdi/semarchy-xdi-runtime/certificat_ssl/truststore.jks"/>
  <attribute defType="com.stambia.kafka.server.sslTrustStorePassword" id="_L9tEANTbEe-ayYrzKU_LEQ" value="6929964D4514864E3D49919A12C2587F"/>
  <node defType="com.stambia.kafka.topic" id="_VxNlcNTbEe-ayYrzKU_LEQ" name="dev-back.ref-banques.pivot-diffusionbancaire.prv.c2.1">
    <attribute defType="com.stambia.kafka.topic.physicalName" id="_urSdYNTbEe-ayYrzKU_LEQ" value="dev-back.ref-banques.pivot-diffusionbancaire.prv.c2.1"/>
    <node defType="com.stambia.kafka.valueField" id="_Bl34EdTcEe-ayYrzKU_LEQ">
      <attribute defType="com.stambia.kafka.valueField.type" id="_Ea5kcNTcEe-ayYrzKU_LEQ" value="string"/>
    </node>
  </node>
  <node defType="com.stambia.kafka.consumer" id="_wyVpcdTbEe-ayYrzKU_LEQ" name="ConsommationSWIFT">
    <attribute defType="com.stambia.kafka.consumer.topicsSubscribed" id="_2tZSoNTbEe-ayYrzKU_LEQ">
      <refs>resource.md#_VxNlcNTbEe-ayYrzKU_LEQ?fileId=_AOK6wNTbEe-ayYrzKU_LEQ$type=md$name=dev-back.ref-banques.pivot-diffusionbancaire.prv.c2.1?</refs>
    </attribute>
    <node defType="com.stambia.kafka.valueField" id="_Gw1hEdTcEe-ayYrzKU_LEQ">
      <attribute defType="com.stambia.kafka.valueField.type" id="_IU8_MNTcEe-ayYrzKU_LEQ" value="string"/>
    </node>
  </node>
</md:node>