<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.http.rest" id="_NSI6ELcQEe-0Xc913hdzrA" name="VersFIFTIMDM" md:ref="resource.tech#UUID_TECH_HTTPREST?fileId=UUID_TECH_HTTPREST$type=tech$name=HttpRest?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.http.rest.module" id="_NSNykLcQEe-0Xc913hdzrA" value="HttpRest"/>
  <attribute defType="com.stambia.http.rest.url" id="_UbDdgLcQEe-0Xc913hdzrA" value="https://devreftiers.afd.fr:8443/semarchy/api/rest/"/>
  <node defType="com.stambia.http.rest.path" id="_aYfFQLcQEe-0Xc913hdzrA">
    <attribute defType="com.stambia.http.rest.path.path" id="_cAu1cLcQEe-0Xc913hdzrA" value="workflows/ref_tiers/workflow-definitions/CreationTiersV2/start"/>
    <node defType="com.stambia.http.rest.operation" id="_gzy70bcQEe-0Xc913hdzrA">
      <attribute defType="com.stambia.http.rest.operation.method" id="_j1qKULcQEe-0Xc913hdzrA" value="POST"/>
      <node defType="com.stambia.http.rest.parameters" id="_F06Bl7cSEe-0Xc913hdzrA">
        <node defType="com.stambia.http.rest.parameter" id="_F06BmLcSEe-0Xc913hdzrA" name="API-Key">
          <attribute defType="com.stambia.http.rest.parameter.allowEmptyValue" id="_F06BmbcSEe-0Xc913hdzrA" value="false"/>
          <attribute defType="com.stambia.http.rest.parameter.location" id="_F06BmrcSEe-0Xc913hdzrA" value="header"/>
          <attribute defType="com.stambia.http.rest.parameter.default" id="_BgSjALcYEe-HWORqlyIdiQ" value="KjnVrBk.5Y5jWPhVoeEibskhsuMCiuzK_i2hzz9MtoG"/>
        </node>
      </node>
      <node defType="com.stambia.http.rest.requestbody" id="_F06Bm7cSEe-0Xc913hdzrA">
        <node defType="com.stambia.http.rest.content" id="_F06BnLcSEe-0Xc913hdzrA">
          <attribute defType="com.stambia.http.rest.content.mediaType" id="_F06BnbcSEe-0Xc913hdzrA" value="JSON"/>
          <attribute defType="com.stambia.http.rest.content.contentType" id="_F06BnrcSEe-0Xc913hdzrA" value="application/json"/>
          <node defType="com.stambia.json.rootObject" id="_F06Bn7cSEe-0Xc913hdzrA" name="root">
            <node defType="com.stambia.json.value" id="_F06BoLcSEe-0Xc913hdzrA" name="startupApplicationName" position="1">
              <attribute defType="com.stambia.json.value.type" id="_F06BobcSEe-0Xc913hdzrA" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_F06BorcSEe-0Xc913hdzrA" name="startEventName" position="2">
              <attribute defType="com.stambia.json.value.type" id="_F06Bo7cSEe-0Xc913hdzrA" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_F06BpLcSEe-0Xc913hdzrA" name="selectionFilter" position="3">
              <attribute defType="com.stambia.json.value.type" id="_F06BpbcSEe-0Xc913hdzrA" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_F06BprcSEe-0Xc913hdzrA" name="priority" position="4">
              <attribute defType="com.stambia.json.value.type" id="_F06Bp7cSEe-0Xc913hdzrA" value="string"/>
            </node>
          </node>
        </node>
      </node>
      <node defType="com.stambia.http.rest.responses" id="_F06BqLcSEe-0Xc913hdzrA">
        <node defType="com.stambia.http.rest.response" id="_QqKsSrcYEe-HWORqlyIdiQ">
          <attribute defType="com.stambia.http.rest.response.code" id="_QqKsS7cYEe-HWORqlyIdiQ" value="200"/>
          <node defType="com.stambia.http.rest.headers" id="_QqKsTLcYEe-HWORqlyIdiQ">
            <node defType="com.stambia.http.rest.header" id="_QqKsTbcYEe-HWORqlyIdiQ" name="Transfer-Encoding"/>
            <node defType="com.stambia.http.rest.header" id="_QqKsTrcYEe-HWORqlyIdiQ" name="Keep-Alive"/>
            <node defType="com.stambia.http.rest.header" id="_QqKsT7cYEe-HWORqlyIdiQ" name="Connection"/>
            <node defType="com.stambia.http.rest.header" id="_QqKsULcYEe-HWORqlyIdiQ" name="Set-Cookie"/>
            <node defType="com.stambia.http.rest.header" id="_QqKsUbcYEe-HWORqlyIdiQ" name="Date"/>
            <node defType="com.stambia.http.rest.header" id="_QqKsUrcYEe-HWORqlyIdiQ" name="Content-Type"/>
            <node defType="com.stambia.http.rest.header.cookie" id="_QqKsU7cYEe-HWORqlyIdiQ" name="_XSRF-TOKEN">
              <attribute defType="com.stambia.http.rest.header.cookie.cookieName" id="_QqKsVLcYEe-HWORqlyIdiQ" value="_XSRF-TOKEN"/>
            </node>
          </node>
          <node defType="com.stambia.http.rest.content" id="_QqKsVbcYEe-HWORqlyIdiQ">
            <attribute defType="com.stambia.http.rest.content.mediaType" id="_QqKsVrcYEe-HWORqlyIdiQ" value="JSON"/>
            <attribute defType="com.stambia.http.rest.content.contentType" id="_QqKsV7cYEe-HWORqlyIdiQ" value="application/json"/>
            <node defType="com.stambia.json.rootObject" id="_QqKsWLcYEe-HWORqlyIdiQ" name="root">
              <node defType="com.stambia.json.array" id="_QqKsWbcYEe-HWORqlyIdiQ" name="workflowInstances" position="1">
                <node defType="com.stambia.json.object" id="_QqKsWrcYEe-HWORqlyIdiQ" name="item" position="1">
                  <node defType="com.stambia.json.value" id="_QqKsW7cYEe-HWORqlyIdiQ" name="workflowInstanceId" position="1">
                    <attribute defType="com.stambia.json.value.type" id="_QqKsXLcYEe-HWORqlyIdiQ" value="number"/>
                  </node>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
  <node defType="com.stambia.http.rest.path" id="_USNx0LiVEe-VV-cv9aIe2w">
    <attribute defType="com.stambia.http.rest.path.path" id="_W8u3ULiVEe-VV-cv9aIe2w" value="workflows/ref_tiers/workflow-definitions/EnvoirMailRetourFIFTIFalse/start"/>
    <node defType="com.stambia.http.rest.operation" id="_i-IzsLiVEe-VV-cv9aIe2w">
      <attribute defType="com.stambia.http.rest.operation.method" id="_i-IzsbiVEe-VV-cv9aIe2w" value="POST"/>
      <node defType="com.stambia.http.rest.parameters" id="_i-IzsriVEe-VV-cv9aIe2w">
        <node defType="com.stambia.http.rest.parameter" id="_i-Izs7iVEe-VV-cv9aIe2w" name="API-Key">
          <attribute defType="com.stambia.http.rest.parameter.allowEmptyValue" id="_i-IztLiVEe-VV-cv9aIe2w" value="false"/>
          <attribute defType="com.stambia.http.rest.parameter.location" id="_i-IztbiVEe-VV-cv9aIe2w" value="header"/>
          <attribute defType="com.stambia.http.rest.parameter.default" id="_i-IztriVEe-VV-cv9aIe2w" value="KjnVrBk.5Y5jWPhVoeEibskhsuMCiuzK_i2hzz9MtoG"/>
        </node>
      </node>
      <node defType="com.stambia.http.rest.requestbody" id="_i-Izt7iVEe-VV-cv9aIe2w">
        <node defType="com.stambia.http.rest.content" id="_i-IzuLiVEe-VV-cv9aIe2w">
          <attribute defType="com.stambia.http.rest.content.mediaType" id="_i-IzubiVEe-VV-cv9aIe2w" value="JSON"/>
          <attribute defType="com.stambia.http.rest.content.contentType" id="_i-IzuriVEe-VV-cv9aIe2w" value="application/json"/>
          <node defType="com.stambia.json.rootObject" id="_i-Izu7iVEe-VV-cv9aIe2w" name="root">
            <node defType="com.stambia.json.value" id="_i-IzvLiVEe-VV-cv9aIe2w" name="startupApplicationName" position="1">
              <attribute defType="com.stambia.json.value.type" id="_i-IzvbiVEe-VV-cv9aIe2w" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_i-IzvriVEe-VV-cv9aIe2w" name="startEventName" position="2">
              <attribute defType="com.stambia.json.value.type" id="_i-Izv7iVEe-VV-cv9aIe2w" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_i-IzwLiVEe-VV-cv9aIe2w" name="selectionFilter" position="3">
              <attribute defType="com.stambia.json.value.type" id="_i-IzwbiVEe-VV-cv9aIe2w" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_i-IzwriVEe-VV-cv9aIe2w" name="priority" position="4">
              <attribute defType="com.stambia.json.value.type" id="_i-Izw7iVEe-VV-cv9aIe2w" value="string"/>
            </node>
          </node>
        </node>
      </node>
      <node defType="com.stambia.http.rest.responses" id="_i-IzxLiVEe-VV-cv9aIe2w">
        <node defType="com.stambia.http.rest.response" id="_i-IzxbiVEe-VV-cv9aIe2w">
          <attribute defType="com.stambia.http.rest.response.code" id="_i-IzxriVEe-VV-cv9aIe2w" value="200"/>
          <node defType="com.stambia.http.rest.headers" id="_i-Izx7iVEe-VV-cv9aIe2w">
            <node defType="com.stambia.http.rest.header" id="_i-IzyLiVEe-VV-cv9aIe2w" name="Transfer-Encoding"/>
            <node defType="com.stambia.http.rest.header" id="_i-IzybiVEe-VV-cv9aIe2w" name="Keep-Alive"/>
            <node defType="com.stambia.http.rest.header" id="_i-IzyriVEe-VV-cv9aIe2w" name="Connection"/>
            <node defType="com.stambia.http.rest.header" id="_i-Izy7iVEe-VV-cv9aIe2w" name="Set-Cookie"/>
            <node defType="com.stambia.http.rest.header" id="_i-IzzLiVEe-VV-cv9aIe2w" name="Date"/>
            <node defType="com.stambia.http.rest.header" id="_i-IzzbiVEe-VV-cv9aIe2w" name="Content-Type"/>
            <node defType="com.stambia.http.rest.header.cookie" id="_i-IzzriVEe-VV-cv9aIe2w" name="_XSRF-TOKEN">
              <attribute defType="com.stambia.http.rest.header.cookie.cookieName" id="_i-Izz7iVEe-VV-cv9aIe2w" value="_XSRF-TOKEN"/>
            </node>
          </node>
          <node defType="com.stambia.http.rest.content" id="_i-Iz0LiVEe-VV-cv9aIe2w">
            <attribute defType="com.stambia.http.rest.content.mediaType" id="_i-Iz0biVEe-VV-cv9aIe2w" value="JSON"/>
            <attribute defType="com.stambia.http.rest.content.contentType" id="_i-Iz0riVEe-VV-cv9aIe2w" value="application/json"/>
            <node defType="com.stambia.json.rootObject" id="_i-Iz07iVEe-VV-cv9aIe2w" name="root">
              <node defType="com.stambia.json.array" id="_i-Iz1LiVEe-VV-cv9aIe2w" name="workflowInstances" position="1">
                <node defType="com.stambia.json.object" id="_i-Iz1biVEe-VV-cv9aIe2w" name="item" position="1">
                  <node defType="com.stambia.json.value" id="_i-Iz1riVEe-VV-cv9aIe2w" name="workflowInstanceId" position="1">
                    <attribute defType="com.stambia.json.value.type" id="_i-Iz17iVEe-VV-cv9aIe2w" value="number"/>
                  </node>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>