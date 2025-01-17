<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.server" id="_VCfIMLbUEe-oWcSwM0X2ag" name="Fichier_RDD" md:ref="resource.md#UUID_MD_RDBMS_MICROSOFT_EXCEL?fileId=UUID_MD_RDBMS_MICROSOFT_EXCEL$type=md$name=Microsoft%20Excel?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.rdbms.server.module" id="_VCknwLbUEe-oWcSwM0X2ag" value="Microsoft Excel"/>
  <attribute defType="com.stambia.rdbms.server.driver" id="_uFLwoLbUEe-oWcSwM0X2ag" value="com.semarchy.xdi.jdbc.excel.XLSXDriver"/>
  <attribute defType="com.stambia.rdbms.server.designerAutoCommit" id="_uFLwobbUEe-oWcSwM0X2ag" value="true"/>
  <attribute defType="com.stambia.rdbms.server.url" id="_uFPbALbUEe-oWcSwM0X2ag" value="jdbc:semarchy:excel://C:\Users\PICAUDD\Desktop\2024.12.03 Echantillon test SIOP.xlsx?columnNameStyle=PRESERVE"/>
  <configuration id="_8t6X8Lb9Ee-0Xc913hdzrA" name="Dev">
    <attribute defType="com.stambia.rdbms.server.url" id="__5mQ0bb9Ee-0Xc913hdzrA" value="jdbc:semarchy:excel://C:\Users\PICAUDD\Desktop\2024.12.03 Echantillon test SIOP.xlsx?columnNameStyle=PRESERVE"/>
  </configuration>
  <node defType="com.stambia.rdbms.schema" id="_VKspALbUEe-oWcSwM0X2ag" name="2024.12.03 Echantillon test SIOP">
    <attribute defType="com.stambia.rdbms.schema.catalog.name" id="_VNVtULbUEe-oWcSwM0X2ag" value="2024.12.03 Echantillon test SIOP"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_VNWUYLbUEe-oWcSwM0X2ag" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_VNW7cLbUEe-oWcSwM0X2ag" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_VNXigLbUEe-oWcSwM0X2ag" value="I_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.dataStoreFilter" id="_qPbKkLbVEe-oWcSwM0X2ag" value=""/>
    <node defType="com.stambia.rdbms.datastore" id="_L5qQkLbWEe-oWcSwM0X2ag" name="nature de relation$">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_L5qQkbbWEe-oWcSwM0X2ag" value="nature de relation$"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_L5qQkrbWEe-oWcSwM0X2ag" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_L5q3oLbWEe-oWcSwM0X2ag" name="ID_Tiers" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_L5q3obbWEe-oWcSwM0X2ag" value="ID_Tiers"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_L5q3orbWEe-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_L5q3o7bWEe-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_L5q3pLbWEe-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_L5q3pbbWEe-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_L5q3prbWEe-oWcSwM0X2ag" name="id_naturerelation" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_L5q3p7bWEe-oWcSwM0X2ag" value="id_naturerelation"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_L5q3qLbWEe-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_L5q3qbbWEe-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_L5q3qrbWEe-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_L5q3q7bWEe-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_L5q3rLbWEe-oWcSwM0X2ag" name="f_type_nature_relation" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_L5q3rbbWEe-oWcSwM0X2ag" value="f_type_nature_relation"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_L5q3rrbWEe-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_L5q3r7bWEe-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_L5q3sLbWEe-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_L5q3sbbWEe-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_L5q3srbWEe-oWcSwM0X2ag" name="f_type_role_nature_relation" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_L5q3s7bWEe-oWcSwM0X2ag" value="f_type_role_nature_relation"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_L5q3tLbWEe-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_L5q3tbbWEe-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_L5q3trbWEe-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_L5q3t7bWEe-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_L5q3uLbWEe-oWcSwM0X2ag" name="dat_creation" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_L5q3ubbWEe-oWcSwM0X2ag" value="dat_creation"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_L5q3urbWEe-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_L5q3u7bWEe-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_L5q3vLbWEe-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_L5q3vbbWEe-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_L5q3vrbWEe-oWcSwM0X2ag" name="dat_affectionnature" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_L5q3v7bWEe-oWcSwM0X2ag" value="dat_affectionnature"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_L5q3wLbWEe-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_L5q3wbbWEe-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_L5q3wrbWEe-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_L5q3w7bWEe-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_L5q3xLbWEe-oWcSwM0X2ag" name="dat_finaffectionnature" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_L5q3xbbWEe-oWcSwM0X2ag" value="dat_finaffectionnature"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_L5q3xrbWEe-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_L5q3x7bWEe-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_L5q3yLbWEe-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_L5q3ybbWEe-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_FBg0kLb4Ee-oWcSwM0X2ag" name="tiers$">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_FBg0kbb4Ee-oWcSwM0X2ag" value="tiers$"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_FBg0krb4Ee-oWcSwM0X2ag" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_FBjQ0Lb4Ee-oWcSwM0X2ag" name="ID_Tiers" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjQ0bb4Ee-oWcSwM0X2ag" value="ID_Tiers"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjQ0rb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjQ07b4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjQ1Lb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjQ1bb4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjQ1rb4Ee-oWcSwM0X2ag" name="f_type_nature_relation" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjQ17b4Ee-oWcSwM0X2ag" value="f_type_nature_relation"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjQ2Lb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjQ2bb4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjQ2rb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjQ27b4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjQ3Lb4Ee-oWcSwM0X2ag" name="zone_geographique" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjQ3bb4Ee-oWcSwM0X2ag" value="zone_geographique"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjQ3rb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjQ37b4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjQ4Lb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjQ4bb4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjQ4rb4Ee-oWcSwM0X2ag" name="f_cat_tiers" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjQ47b4Ee-oWcSwM0X2ag" value="f_cat_tiers"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjQ5Lb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjQ5bb4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjQ5rb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjQ57b4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjQ6Lb4Ee-oWcSwM0X2ag" name="date_creation_tiers" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjQ6bb4Ee-oWcSwM0X2ag" value="date_creation_tiers"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjQ6rb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjQ67b4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjQ7Lb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjQ7bb4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjQ7rb4Ee-oWcSwM0X2ag" name="F_PAYS_NATIONALITE" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjQ77b4Ee-oWcSwM0X2ag" value="F_PAYS_NATIONALITE"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjQ8Lb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjQ8bb4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjQ8rb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjQ87b4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjQ9Lb4Ee-oWcSwM0X2ag" name="f_pays_residence" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjQ9bb4Ee-oWcSwM0X2ag" value="f_pays_residence"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjQ9rb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjQ97b4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjQ-Lb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjQ-bb4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjQ-rb4Ee-oWcSwM0X2ag" name="f_pays_immatriculation" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjQ-7b4Ee-oWcSwM0X2ag" value="f_pays_immatriculation"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjQ_Lb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjQ_bb4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjQ_rb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjQ_7b4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRALb4Ee-oWcSwM0X2ag" name="f_agent_economique" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRAbb4Ee-oWcSwM0X2ag" value="f_agent_economique"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjRArb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRA7b4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjRBLb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjRBbb4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRBrb4Ee-oWcSwM0X2ag" name="f_categorie_juridique" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRB7b4Ee-oWcSwM0X2ag" value="f_categorie_juridique"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjRCLb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRCbb4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjRCrb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjRC7b4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRDLb4Ee-oWcSwM0X2ag" name="f_canal_acheminement" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRDbb4Ee-oWcSwM0X2ag" value="f_canal_acheminement"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjRDrb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRD7b4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjRELb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjREbb4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRErb4Ee-oWcSwM0X2ag" name="raison_sociale" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRE7b4Ee-oWcSwM0X2ag" value="raison_sociale"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjRFLb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRFbb4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjRFrb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjRF7b4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRGLb4Ee-oWcSwM0X2ag" name="raison_sociale_abregee" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRGbb4Ee-oWcSwM0X2ag" value="raison_sociale_abregee"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjRGrb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRG7b4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjRHLb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjRHbb4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRHrb4Ee-oWcSwM0X2ag" name="siren" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRH7b4Ee-oWcSwM0X2ag" value="siren"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjRILb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRIbb4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjRIrb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjRI7b4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRJLb4Ee-oWcSwM0X2ag" name="siret" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRJbb4Ee-oWcSwM0X2ag" value="siret"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjRJrb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRJ7b4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjRKLb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjRKbb4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRKrb4Ee-oWcSwM0X2ag" name="f_section_naf" position="16">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRK7b4Ee-oWcSwM0X2ag" value="f_section_naf"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjRLLb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRLbb4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjRLrb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjRL7b4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRMLb4Ee-oWcSwM0X2ag" name="f_sous_section_naf" position="17">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRMbb4Ee-oWcSwM0X2ag" value="f_sous_section_naf"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjRMrb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRM7b4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjRNLb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjRNbb4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRNrb4Ee-oWcSwM0X2ag" name="f_regroupement_naf" position="18">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRN7b4Ee-oWcSwM0X2ag" value="f_regroupement_naf"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjROLb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRObb4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjROrb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjRO7b4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRPLb4Ee-oWcSwM0X2ag" name="f_code_naf" position="19">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRPbb4Ee-oWcSwM0X2ag" value="f_code_naf"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjRPrb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRP7b4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjRQLb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjRQbb4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRQrb4Ee-oWcSwM0X2ag" name="f_code_nace" position="20">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRQ7b4Ee-oWcSwM0X2ag" value="f_code_nace"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjRRLb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRRbb4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjRRrb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjRR7b4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FBjRSLb4Ee-oWcSwM0X2ag" name="code_ridet" position="21">
        <attribute defType="com.stambia.rdbms.column.name" id="_FBjRSbb4Ee-oWcSwM0X2ag" value="code_ridet"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_FBjRSrb4Ee-oWcSwM0X2ag" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FBjRS7b4Ee-oWcSwM0X2ag" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_FBjRTLb4Ee-oWcSwM0X2ag" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FBjRTbb4Ee-oWcSwM0X2ag" value="VARCHAR"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_lvkEQLeqEe-HWORqlyIdiQ" name="banque$">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_lvkEQbeqEe-HWORqlyIdiQ" value="banque$"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_lvkEQreqEe-HWORqlyIdiQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_lvpj0LeqEe-HWORqlyIdiQ" name="ID_Tiers" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvpj0beqEe-HWORqlyIdiQ" value="ID_Tiers"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvpj0reqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvpj07eqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvpj1LeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvpj1beqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvpj1reqEe-HWORqlyIdiQ" name="id_banque" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvpj17eqEe-HWORqlyIdiQ" value="id_banque"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvpj2LeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvpj2beqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvpj2reqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvpj27eqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvpj3LeqEe-HWORqlyIdiQ" name="nombanque" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvpj3beqEe-HWORqlyIdiQ" value="nombanque"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvpj3reqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvpj37eqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvpj4LeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvpj4beqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvpj4reqEe-HWORqlyIdiQ" name="sigle" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvpj47eqEe-HWORqlyIdiQ" value="sigle"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvpj5LeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvpj5beqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvpj5reqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvpj57eqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvpj6LeqEe-HWORqlyIdiQ" name="nom_agence" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvpj6beqEe-HWORqlyIdiQ" value="nom_agence"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvpj6reqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvpj67eqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvpj7LeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvpj7beqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvpj7reqEe-HWORqlyIdiQ" name="nom_agence_br" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvpj77eqEe-HWORqlyIdiQ" value="nom_agence_br"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvpj8LeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvpj8beqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvpj8reqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvpj87eqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvpj9LeqEe-HWORqlyIdiQ" name="adresse_agence" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvpj9beqEe-HWORqlyIdiQ" value="adresse_agence"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvpj9reqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvpj97eqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvpj-LeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvpj-beqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvpj-reqEe-HWORqlyIdiQ" name="ville_agence" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvpj-7eqEe-HWORqlyIdiQ" value="ville_agence"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvpj_LeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvpj_beqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvpj_reqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvpj_7eqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvpkALeqEe-HWORqlyIdiQ" name="f_pays" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvpkAbeqEe-HWORqlyIdiQ" value="f_pays"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvpkAreqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvpkA7eqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvpkBLeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvpkBbeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvpkBreqEe-HWORqlyIdiQ" name="mail_agence" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvpkB7eqEe-HWORqlyIdiQ" value="mail_agence"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvpkCLeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvpkCbeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvpkCreqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvpkC7eqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvpkDLeqEe-HWORqlyIdiQ" name="tel_agence" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvpkDbeqEe-HWORqlyIdiQ" value="tel_agence"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvpkDreqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqK4LeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqK4beqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqK4reqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqK47eqEe-HWORqlyIdiQ" name="fax_agence" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqK5LeqEe-HWORqlyIdiQ" value="fax_agence"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqK5beqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqK5reqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqK57eqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqK6LeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqK6beqEe-HWORqlyIdiQ" name="compte_defaut" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqK6reqEe-HWORqlyIdiQ" value="compte_defaut"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqK67eqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqK7LeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqK7beqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqK7reqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqK77eqEe-HWORqlyIdiQ" name="compte_actif" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqK8LeqEe-HWORqlyIdiQ" value="compte_actif"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqK8beqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqK8reqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqK87eqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqK9LeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqK9beqEe-HWORqlyIdiQ" name="INDICATEUR_DEBIT_OFFICE" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqK9reqEe-HWORqlyIdiQ" value="INDICATEUR_DEBIT_OFFICE"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqK97eqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqK-LeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqK-beqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqK-reqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqK-7eqEe-HWORqlyIdiQ" name="inititule_du_compte" position="16">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqK_LeqEe-HWORqlyIdiQ" value="inititule_du_compte"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqK_beqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqK_reqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqK_7eqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLALeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLAbeqEe-HWORqlyIdiQ" name="date_ouverture" position="17">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLAreqEe-HWORqlyIdiQ" value="date_ouverture"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLA7eqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLBLeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLBbeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLBreqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLB7eqEe-HWORqlyIdiQ" name="date_de_fermeture" position="18">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLCLeqEe-HWORqlyIdiQ" value="date_de_fermeture"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLCbeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLCreqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLC7eqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLDLeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLDbeqEe-HWORqlyIdiQ" name="f_devise" position="19">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLDreqEe-HWORqlyIdiQ" value="f_devise"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLD7eqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLELeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLEbeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLEreqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLE7eqEe-HWORqlyIdiQ" name="f_pays_compte" position="20">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLFLeqEe-HWORqlyIdiQ" value="f_pays_compte"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLFbeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLFreqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLF7eqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLGLeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLGbeqEe-HWORqlyIdiQ" name="f_type_utilisation_compte" position="21">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLGreqEe-HWORqlyIdiQ" value="f_type_utilisation_compte"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLG7eqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLHLeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLHbeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLHreqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLH7eqEe-HWORqlyIdiQ" name="f_nature_compte" position="22">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLILeqEe-HWORqlyIdiQ" value="f_nature_compte"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLIbeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLIreqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLI7eqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLJLeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLJbeqEe-HWORqlyIdiQ" name="code_banque" position="23">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLJreqEe-HWORqlyIdiQ" value="code_banque"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLJ7eqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLKLeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLKbeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLKreqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLK7eqEe-HWORqlyIdiQ" name="code_guichet" position="24">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLLLeqEe-HWORqlyIdiQ" value="code_guichet"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLLbeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLLreqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLL7eqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLMLeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLMbeqEe-HWORqlyIdiQ" name="numero_compte" position="25">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLMreqEe-HWORqlyIdiQ" value="numero_compte"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLM7eqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLNLeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLNbeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLNreqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLN7eqEe-HWORqlyIdiQ" name="cle_rib" position="26">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLOLeqEe-HWORqlyIdiQ" value="cle_rib"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLObeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLOreqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLO7eqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLPLeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLPbeqEe-HWORqlyIdiQ" name="bic8" position="27">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLPreqEe-HWORqlyIdiQ" value="bic8"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLP7eqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLQLeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLQbeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLQreqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLQ7eqEe-HWORqlyIdiQ" name="bic11" position="28">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLRLeqEe-HWORqlyIdiQ" value="bic11"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLRbeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLRreqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLR7eqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLSLeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLSbeqEe-HWORqlyIdiQ" name="iban" position="29">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLSreqEe-HWORqlyIdiQ" value="iban"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLS7eqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLTLeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLTbeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLTreqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLT7eqEe-HWORqlyIdiQ" name="bban" position="30">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLULeqEe-HWORqlyIdiQ" value="bban"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLUbeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLUreqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLU7eqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLVLeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLVbeqEe-HWORqlyIdiQ" name="cle_iban" position="31">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLVreqEe-HWORqlyIdiQ" value="cle_iban"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLV7eqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLWLeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLWbeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLWreqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLW7eqEe-HWORqlyIdiQ" name="numero_aba" position="32">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLXLeqEe-HWORqlyIdiQ" value="numero_aba"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLXbeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLXreqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLX7eqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLYLeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLYbeqEe-HWORqlyIdiQ" name="swift_banque" position="33">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLYreqEe-HWORqlyIdiQ" value="swift_banque"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLY7eqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLZLeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLZbeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLZreqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLZ7eqEe-HWORqlyIdiQ" name="f_pays_swift" position="34">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLaLeqEe-HWORqlyIdiQ" value="f_pays_swift"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLabeqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLareqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLa7eqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLbLeqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_lvqLbbeqEe-HWORqlyIdiQ" name="NUMERO_COMPTE_ACCT" position="35">
        <attribute defType="com.stambia.rdbms.column.name" id="_lvqLbreqEe-HWORqlyIdiQ" value="NUMERO_COMPTE_ACCT"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_lvqLb7eqEe-HWORqlyIdiQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_lvqLcLeqEe-HWORqlyIdiQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_lvqLcbeqEe-HWORqlyIdiQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_lvqLcreqEe-HWORqlyIdiQ" value="VARCHAR"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_DqOr8LfREe-6BZFGswrzLA" name="coordonnee adresse$">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_DqPTALfREe-6BZFGswrzLA" value="coordonnee adresse$"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_DqPTAbfREe-6BZFGswrzLA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_DqWnwLfREe-6BZFGswrzLA" name="ID_Tiers" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqWnwbfREe-6BZFGswrzLA" value="ID_Tiers"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqWnwrfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqWnw7fREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqWnxLfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqXO0LfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqXO0bfREe-6BZFGswrzLA" name="id_coordonneecom" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqXO0rfREe-6BZFGswrzLA" value="id_coordonneecom"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqXO07fREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqXO1LfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqXO1bfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqXO1rfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqXO17fREe-6BZFGswrzLA" name="f_type_adresse" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqXO2LfREe-6BZFGswrzLA" value="f_type_adresse"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqXO2bfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqXO2rfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqXO27fREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqXO3LfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqXO3bfREe-6BZFGswrzLA" name="numerovoie" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqXO3rfREe-6BZFGswrzLA" value="numerovoie"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqXO37fREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqXO4LfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqXO4bfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqXO4rfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqXO47fREe-6BZFGswrzLA" name="f_type_voie" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqXO5LfREe-6BZFGswrzLA" value="f_type_voie"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqXO5bfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqXO5rfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqXO57fREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqXO6LfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqXO6bfREe-6BZFGswrzLA" name="nomvoie" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqXO6rfREe-6BZFGswrzLA" value="nomvoie"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqXO67fREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqXO7LfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqXO7bfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqXO7rfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqXO77fREe-6BZFGswrzLA" name="ll_boitepostale" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqXO8LfREe-6BZFGswrzLA" value="ll_boitepostale"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqXO8bfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqXO8rfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqXO87fREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqXO9LfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqXO9bfREe-6BZFGswrzLA" name="cd_postal" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqXO9rfREe-6BZFGswrzLA" value="cd_postal"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqXO97fREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqXO-LfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqXO-bfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqXO-rfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqXO-7fREe-6BZFGswrzLA" name="ll_ville" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqXO_LfREe-6BZFGswrzLA" value="ll_ville"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqXO_bfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqXO_rfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqXO_7fREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqXPALfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqXPAbfREe-6BZFGswrzLA" name="ll_lieudit" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqXPArfREe-6BZFGswrzLA" value="ll_lieudit"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqXPA7fREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqXPBLfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqXPBbfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqXPBrfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqXPB7fREe-6BZFGswrzLA" name="ll_region" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqXPCLfREe-6BZFGswrzLA" value="ll_region"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqXPCbfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqXPCrfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqX14LfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqX14bfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqX14rfREe-6BZFGswrzLA" name="f_pays" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqX147fREe-6BZFGswrzLA" value="f_pays"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqX15LfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqX15bfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqX15rfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqX157fREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqX16LfREe-6BZFGswrzLA" name="ll_nomdestinataire" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqX16bfREe-6BZFGswrzLA" value="ll_nomdestinataire"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqX16rfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqX167fREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqX17LfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqX17bfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqX17rfREe-6BZFGswrzLA" name="dat_debutadresse" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqX177fREe-6BZFGswrzLA" value="dat_debutadresse"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqX18LfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqX18bfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqX18rfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqX187fREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqX19LfREe-6BZFGswrzLA" name="dat_fin" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqX19bfREe-6BZFGswrzLA" value="dat_fin"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqX19rfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqX197fREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqX1-LfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqX1-bfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqX1-rfREe-6BZFGswrzLA" name="f_langue_communication" position="16">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqX1-7fREe-6BZFGswrzLA" value="f_langue_communication"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqX1_LfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqX1_bfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqX1_rfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqX1_7fREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqX2ALfREe-6BZFGswrzLA" name="f_langue_edition" position="17">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqX2AbfREe-6BZFGswrzLA" value="f_langue_edition"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqX2ArfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqX2A7fREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqX2BLfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqX2BbfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqX2BrfREe-6BZFGswrzLA" name="ll_telport" position="18">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqX2B7fREe-6BZFGswrzLA" value="ll_telport"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqX2CLfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqX2CbfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqX2CrfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqX2C7fREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqX2DLfREe-6BZFGswrzLA" name="ll_telfixe" position="19">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqX2DbfREe-6BZFGswrzLA" value="ll_telfixe"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqX2DrfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqX2D7fREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqX2ELfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqX2EbfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqX2ErfREe-6BZFGswrzLA" name="ll_telfax" position="20">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqX2E7fREe-6BZFGswrzLA" value="ll_telfax"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqX2FLfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqX2FbfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqX2FrfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqX2F7fREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqX2GLfREe-6BZFGswrzLA" name="ll_mailadresse" position="21">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqX2GbfREe-6BZFGswrzLA" value="ll_mailadresse"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqX2GrfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqX2G7fREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqX2HLfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqX2HbfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_DqX2HrfREe-6BZFGswrzLA" name="ll_telex" position="22">
        <attribute defType="com.stambia.rdbms.column.name" id="_DqX2H7fREe-6BZFGswrzLA" value="ll_telex"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_DqX2ILfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_DqX2IbfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_DqX2IrfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_DqX2I7fREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_DqzTsLfREe-6BZFGswrzLA" name="role sur une nature de relation$">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_DqzTsbfREe-6BZFGswrzLA" value="role sur une nature de relation$"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_DqzTsrfREe-6BZFGswrzLA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Dq0h0LfREe-6BZFGswrzLA" name="f_nature_de_relation_tiers" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Dq0h0bfREe-6BZFGswrzLA" value="f_nature_de_relation_tiers"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_Dq0h0rfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Dq0h07fREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_Dq0h1LfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Dq0h1bfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Dq0h1rfREe-6BZFGswrzLA" name="id_rolenature" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Dq0h17fREe-6BZFGswrzLA" value="id_rolenature"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_Dq0h2LfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Dq0h2bfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_Dq0h2rfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Dq0h27fREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Dq0h3LfREe-6BZFGswrzLA" name="f_type_role_nature_relation" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_Dq0h3bfREe-6BZFGswrzLA" value="f_type_role_nature_relation"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_Dq0h3rfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Dq0h37fREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_Dq0h4LfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Dq0h4bfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Dq0h4rfREe-6BZFGswrzLA" name="dat_debutrole" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_Dq0h47fREe-6BZFGswrzLA" value="dat_debutrole"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_Dq0h5LfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Dq0h5bfREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_Dq0h5rfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Dq0h57fREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Dq0h6LfREe-6BZFGswrzLA" name="date_fin_de_role" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_Dq0h6bfREe-6BZFGswrzLA" value="date_fin_de_role"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_Dq0h6rfREe-6BZFGswrzLA" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Dq0h67fREe-6BZFGswrzLA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_Dq0h7LfREe-6BZFGswrzLA" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Dq0h7bfREe-6BZFGswrzLA" value="VARCHAR"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_VggwIL2nEe-tfsN_kpKWQQ" name="entite lie à la nature relation$">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_VggwIb2nEe-tfsN_kpKWQQ" value="entite lie à la nature relation$"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_VggwIr2nEe-tfsN_kpKWQQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Vgh-QL2nEe-tfsN_kpKWQQ" name="id_naturerelation" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Vgh-Qb2nEe-tfsN_kpKWQQ" value="id_naturerelation"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_Vgh-Qr2nEe-tfsN_kpKWQQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Vgh-Q72nEe-tfsN_kpKWQQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_Vgh-RL2nEe-tfsN_kpKWQQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Vgh-Rb2nEe-tfsN_kpKWQQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Vgh-Rr2nEe-tfsN_kpKWQQ" name="id_entiteutilisantnature" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Vgh-R72nEe-tfsN_kpKWQQ" value="id_entiteutilisantnature"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_Vgh-SL2nEe-tfsN_kpKWQQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Vgh-Sb2nEe-tfsN_kpKWQQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_Vgh-Sr2nEe-tfsN_kpKWQQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Vgh-S72nEe-tfsN_kpKWQQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Vgh-TL2nEe-tfsN_kpKWQQ" name="f_entite" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_Vgh-Tb2nEe-tfsN_kpKWQQ" value="f_entite"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_Vgh-Tr2nEe-tfsN_kpKWQQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Vgh-T72nEe-tfsN_kpKWQQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_Vgh-UL2nEe-tfsN_kpKWQQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Vgh-Ub2nEe-tfsN_kpKWQQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Vgh-Ur2nEe-tfsN_kpKWQQ" name="dat_debutentite" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_Vgh-U72nEe-tfsN_kpKWQQ" value="dat_debutentite"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_Vgh-VL2nEe-tfsN_kpKWQQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Vgh-Vb2nEe-tfsN_kpKWQQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_Vgh-Vr2nEe-tfsN_kpKWQQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Vgh-V72nEe-tfsN_kpKWQQ" value="VARCHAR"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Vgh-WL2nEe-tfsN_kpKWQQ" name="dat_finentite" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_Vgh-Wb2nEe-tfsN_kpKWQQ" value="dat_finentite"/>
        <attribute defType="com.stambia.rdbms.column.autoIncrement" id="_Vgh-Wr2nEe-tfsN_kpKWQQ" value="false"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Vgh-W72nEe-tfsN_kpKWQQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.remarks" id="_Vgh-XL2nEe-tfsN_kpKWQQ" value=""/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Vgh-Xb2nEe-tfsN_kpKWQQ" value="VARCHAR"/>
      </node>
    </node>
  </node>
</md:node>