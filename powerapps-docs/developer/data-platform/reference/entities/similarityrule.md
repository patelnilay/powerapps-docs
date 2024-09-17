---
title: "Similarity Rule (SimilarityRule) table/entity reference (Microsoft Dataverse)"
description: "Includes schema information and supported messages for the Similarity Rule (SimilarityRule) table/entity with Microsoft Dataverse."
ms.date: 08/30/2024
ms.service: powerapps
ms.topic: reference
author: phecke
ms.author: pehecke
search.audienceType: 
  - developer
---

# Similarity Rule (SimilarityRule) table/entity reference



## Properties

The following table lists selected properties for the Similarity Rule (SimilarityRule) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Similarity Rule** |
| **DisplayCollectionName** | **Similarity Rules** |
| **SchemaName** | `SimilarityRule` |
| **CollectionSchemaName** | `SimilarityRules` |
| **EntitySetName** | `similarityrules`|
| **LogicalName** | `similarityrule` |
| **LogicalCollectionName** | `similarityrules` |
| **PrimaryIdAttribute** | `similarityruleid` |
| **PrimaryNameAttribute** |`name` |
| **TableType** | `Standard` |
| **OwnershipType** | `OrganizationOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ActiveRuleFetchXML](#BKMK_ActiveRuleFetchXML)
- [BaseEntityName](#BKMK_BaseEntityName)
- [Description](#BKMK_Description)
- [ExcludeInactiveRecords](#BKMK_ExcludeInactiveRecords)
- [FetchXmlList](#BKMK_FetchXmlList)
- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [IntroducedVersion](#BKMK_IntroducedVersion)
- [MatchingEntityName](#BKMK_MatchingEntityName)
- [MaxKeyWords](#BKMK_MaxKeyWords)
- [name](#BKMK_name)
- [NgramSize](#BKMK_NgramSize)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [RuleConditionXml](#BKMK_RuleConditionXml)
- [SimilarityRuleId](#BKMK_SimilarityRuleId)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [TransactionCurrencyId](#BKMK_TransactionCurrencyId)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)

### <a name="BKMK_ActiveRuleFetchXML"></a> ActiveRuleFetchXML

|Property|Value|
|---|---|
|Description|**Generated Fetch xml from Active rule and rule conditions.**|
|DisplayName|**Active Rule Fetch Xml**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`activerulefetchxml`|
|RequiredLevel|None|
|Type|Memo|
|Format|TextArea|
|FormatName|TextArea|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1073741823|

### <a name="BKMK_BaseEntityName"></a> BaseEntityName

|Property|Value|
|---|---|
|Description|**Record type of the record being evaluated for potential similarities.**|
|DisplayName|**Base Record Type**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`baseentityname`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|160|

### <a name="BKMK_Description"></a> Description

|Property|Value|
|---|---|
|Description|**Description of the similarity detection rule.**|
|DisplayName|**Description**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`description`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|2000|

### <a name="BKMK_ExcludeInactiveRecords"></a> ExcludeInactiveRecords

|Property|Value|
|---|---|
|Description|**Determines whether to flag inactive records as similarities**|
|DisplayName|**Exclude Inactive Records**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`excludeinactiverecords`|
|RequiredLevel|None|
|Type|Boolean|
|GlobalChoiceName|`similarityrule_excludeinactiverecords`|
|DefaultValue|False|
|True Label|True|
|False Label|False|

### <a name="BKMK_FetchXmlList"></a> FetchXmlList

|Property|Value|
|---|---|
|Description|**Fetch Xml**|
|DisplayName|**Fetch Xml**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`fetchxmllist`|
|RequiredLevel|None|
|Type|Memo|
|Format|TextArea|
|FormatName|TextArea|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|500000|

### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

|Property|Value|
|---|---|
|Description|**Sequence number of the import that created this record.**|
|DisplayName|**Import Sequence Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`importsequencenumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_IntroducedVersion"></a> IntroducedVersion

|Property|Value|
|---|---|
|Description|**Version in which the similarity rule is introduced.**|
|DisplayName|**Introduced Version**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`introducedversion`|
|RequiredLevel|None|
|Type|String|
|Format|VersionNumber|
|FormatName|VersionNumber|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|48|

### <a name="BKMK_MatchingEntityName"></a> MatchingEntityName

|Property|Value|
|---|---|
|Description|**Record type of the records being evaluated as potential similarities.**|
|DisplayName|**Matching Record Type**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`matchingentityname`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|160|

### <a name="BKMK_MaxKeyWords"></a> MaxKeyWords

|Property|Value|
|---|---|
|Description|**Enter the maximum number of keywords and key phrases to use with text analytics.**|
|DisplayName|**Maximum Number of Key Phrases**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`maxkeywords`|
|RequiredLevel|ApplicationRequired|
|Type|Integer|
|MaxValue|1000|
|MinValue|0|

### <a name="BKMK_name"></a> name

|Property|Value|
|---|---|
|Description|**The name of the custom entity.**|
|DisplayName|**Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`name`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|100|

### <a name="BKMK_NgramSize"></a> NgramSize

|Property|Value|
|---|---|
|Description|**Enter the maximum number of words in a key phrase to use with text analytics.**|
|DisplayName|**Maximum Key Phrase Words**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`ngramsize`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|3|
|MinValue|1|

### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|---|---|
|Description|**Date and time that the record was migrated.**|
|DisplayName|**Record Created On**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`overriddencreatedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_RuleConditionXml"></a> RuleConditionXml

|Property|Value|
|---|---|
|Description|**ConditionXml for similarity rule conditions.**|
|DisplayName|**Rule Conditions Xml**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`ruleconditionxml`|
|RequiredLevel|None|
|Type|Memo|
|Format|TextArea|
|FormatName|TextArea|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1073741823|

### <a name="BKMK_SimilarityRuleId"></a> SimilarityRuleId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Similarity Rule**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`similarityruleid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|---|---|
|Description|**Status of the Similarity Rule**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`similarityrule_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Draft**<br />DefaultStatus: 1<br />InvariantName: `Draft`|
|1|Label: **Active**<br />DefaultStatus: 2<br />InvariantName: `Active`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the Similarity Rule**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue|0|
|GlobalChoiceName|`similarityrule_statuscode`|

#### statuscode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Draft**<br />State:0<br />TransitionData: None|
|1|Label: **Active**<br />State:1<br />TransitionData: None|

### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Time Zone Rule Version Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`timezoneruleversionnumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-1|

### <a name="BKMK_TransactionCurrencyId"></a> TransactionCurrencyId

|Property|Value|
|---|---|
|Description|**Exchange rate for the currency associated with the SimilarityRule with respect to the base currency.**|
|DisplayName|**Currency**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`transactioncurrencyid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|transactioncurrency|

### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|---|---|
|Description|**Time zone code that was in use when the record was created.**|
|DisplayName|**UTC Conversion Time Zone Code**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`utcconversiontimezonecode`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-1|


## Read-only columns/attributes

These columns/attributes return false for both **IsValidForCreate** and **IsValidForUpdate**. Listed by **SchemaName**.

- [BaseEntityTypeCode](#BKMK_BaseEntityTypeCode)
- [ComponentState](#BKMK_ComponentState)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [ExchangeRate](#BKMK_ExchangeRate)
- [IsManaged](#BKMK_IsManaged)
- [MatchingEntityTypeCode](#BKMK_MatchingEntityTypeCode)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [OrganizationId](#BKMK_OrganizationId)
- [OverwriteTime](#BKMK_OverwriteTime)
- [SimilarityRuleIdUnique](#BKMK_SimilarityRuleIdUnique)
- [SolutionId](#BKMK_SolutionId)
- [SupportingSolutionId](#BKMK_SupportingSolutionId)
- [VersionNumber](#BKMK_VersionNumber)

### <a name="BKMK_BaseEntityTypeCode"></a> BaseEntityTypeCode

|Property|Value|
|---|---|
|Description|**Record type of the record being evaluated for potential similarities.**|
|DisplayName|**Base Record Type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`baseentitytypecode`|
|RequiredLevel|SystemRequired|
|Type|Picklist|
|DefaultFormValue|0|
|GlobalChoiceName|`similarityrule_baseentitytypecode`|

#### BaseEntityTypeCode Choices/Options

|Value|Label|
|---|---|
|1|**Account**|
|2|**Contact**|
|5|**Note**|
|6|**Business Unit Map**|
|7|**Owner**|
|8|**User**|
|9|**Team**|
|10|**Business Unit**|
|14|**System User Principal**|
|29|**Subscription**|
|30|**Filter Template**|
|31|**Privilege Object Type Code**|
|33|**Subscription Synchronization Information**|
|35|**Tracking information for deleted entities**|
|36|**Client update**|
|37|**Subscription Manually Tracked Object**|
|42|**SystemUser BusinessUnit Entity Map**|
|44|**Field Sharing**|
|45|**Subscription Statistic Offline**|
|46|**Subscription Statistic Outlook**|
|47|**Subscription Sync Entry Offline**|
|48|**Subscription Sync Entry Outlook**|
|50|**Position**|
|51|**System User Manager Map**|
|52|**User Search Facet**|
|54|**Global Search Configuration**|
|55|**FileAttachment**|
|60|**SystemUserAuthorizationChangeTracker**|
|61|**PrincipalEntityBusinessUnitMap**|
|72|**Record Filter**|
|73|**EntityRecordFilter**|
|74|**Secured Masking Rule**|
|75|**Privilege Checker Run**|
|76|**Privilege Checker Log**|
|78|**Virtual Entity Data Provider**|
|85|**Virtual Entity Data Source**|
|92|**Team template**|
|99|**Social Profile**|
|101|**Service Plan**|
|103|**Privileges Removal Setting**|
|126|**Indexed Article**|
|127|**Article**|
|129|**Subject**|
|132|**Announcement**|
|135|**Activity Party**|
|150|**User Settings**|
|300|**Canvas App**|
|301|**Callback Registration**|
|372|**Connector**|
|373|**Connection Instance**|
|380|**Environment Variable Definition**|
|381|**Environment Variable Value**|
|400|**AI Template**|
|401|**AI Model**|
|402|**AI Configuration**|
|418|**Dataflow**|
|430|**Entity Analytics Config**|
|431|**Image Attribute Configuration**|
|432|**Entity Image Configuration**|
|950|**New Process**|
|951|**Translation Process**|
|955|**Expired Process**|
|1001|**Attachment**|
|1002|**Attachment**|
|1003|**Internal Address**|
|1007|**Image Descriptor**|
|1016|**Article Template**|
|1019|**Organization**|
|1021|**Organization UI**|
|1023|**Privilege**|
|1030|**System Form**|
|1031|**User Dashboard**|
|1036|**Security Role**|
|1037|**Role Template**|
|1039|**View**|
|1043|**String Map**|
|1071|**Address**|
|1072|**Subscription Clients**|
|1075|**Status Map**|
|1082|**Article Comment**|
|1086|**User Fiscal Calendar**|
|1094|**Authorization Server**|
|1095|**Partner Application**|
|1111|**System Chart**|
|1112|**User Chart**|
|1113|**Ribbon Tab To Command Mapping**|
|1115|**Ribbon Context Group**|
|1116|**Ribbon Command**|
|1117|**Ribbon Rule**|
|1120|**Application Ribbons**|
|1130|**Ribbon Difference**|
|1140|**Replication Backlog**|
|1189|**Document Suggestions**|
|1190|**SuggestionCardTemplate**|
|1200|**Field Security Profile**|
|1201|**Field Permission**|
|1203|**Team Profiles**|
|1204|**Application**|
|1234|**Channel Property Group**|
|1236|**Channel Property**|
|1300|**SocialInsightsConfiguration**|
|1309|**Saved Organization Insights Configuration**|
|1400|**Sync Attribute Mapping Profile**|
|1401|**Sync Attribute Mapping**|
|1403|**Team Sync-Attribute Mapping Profiles**|
|1404|**Principal Sync Attribute Map**|
|2000|**Annual Fiscal Calendar**|
|2001|**Semiannual Fiscal Calendar**|
|2002|**Quarterly Fiscal Calendar**|
|2003|**Monthly Fiscal Calendar**|
|2004|**Fixed Monthly Fiscal Calendar**|
|2010|**Email Template**|
|2012|**Unresolved Address**|
|2013|**Territory**|
|2015|**Theme**|
|2016|**User Mapping**|
|2020|**Queue**|
|2023|**QueueItemCount**|
|2024|**QueueMemberCount**|
|2027|**License**|
|2029|**Queue Item**|
|2500|**User Entity UI Settings**|
|2501|**User Entity Instance Data**|
|3000|**Integration Status**|
|3005|**Channel Access Profile**|
|3008|**External Party**|
|3231|**Connection Role**|
|3233|**Connection Role Object Type Code**|
|3234|**Connection**|
|4003|**Calendar**|
|4004|**Calendar Rule**|
|4011|**Inter Process Lock**|
|4023|**Email Hash**|
|4101|**Display String Map**|
|4102|**Display String**|
|4110|**Notification**|
|4120|**Exchange Sync Id Mapping**|
|4200|**Activity**|
|4201|**Appointment**|
|4202|**Email**|
|4204|**Fax**|
|4207|**Letter**|
|4210|**Phone Call**|
|4212|**Task**|
|4216|**Social Activity**|
|4220|**UntrackedEmail**|
|4230|**Saved View**|
|4231|**Metadata Difference**|
|4232|**Business Data Localized Label**|
|4250|**Recurrence Rule**|
|4251|**Recurring Appointment**|
|4299|**Email Search**|
|4410|**Data Import**|
|4411|**Data Map**|
|4412|**Import Source File**|
|4413|**Import Data**|
|4414|**Duplicate Detection Rule**|
|4415|**Duplicate Record**|
|4416|**Duplicate Rule Condition**|
|4417|**Column Mapping**|
|4418|**List Value Mapping**|
|4419|**Lookup Mapping**|
|4420|**Owner Mapping**|
|4423|**Import Log**|
|4424|**Bulk Delete Operation**|
|4425|**Bulk Delete Failure**|
|4426|**Transformation Mapping**|
|4427|**Transformation Parameter Mapping**|
|4428|**Import Entity Mapping**|
|4450|**Data Performance Dashboard**|
|4490|**Office Document**|
|4500|**Relationship Role**|
|4501|**Relationship Role Map**|
|4502|**Customer Relationship**|
|4567|**Auditing**|
|4579|**Ribbon Client Metadata.**|
|4600|**Entity Map**|
|4601|**Attribute Map**|
|4602|**Plug-in Type**|
|4603|**Plug-in Type Statistic**|
|4605|**Plug-in Assembly**|
|4606|**Sdk Message**|
|4607|**Sdk Message Filter**|
|4608|**Sdk Message Processing Step**|
|4609|**Sdk Message Request**|
|4610|**Sdk Message Response**|
|4611|**Sdk Message Response Field**|
|4613|**Sdk Message Pair**|
|4614|**Sdk Message Request Field**|
|4615|**Sdk Message Processing Step Image**|
|4616|**Sdk Message Processing Step Secure Configuration**|
|4618|**Service Endpoint**|
|4619|**Plug-in Trace Log**|
|4700|**System Job**|
|4702|**Workflow Wait Subscription**|
|4703|**Process**|
|4704|**Process Dependency**|
|4705|**ISV Config**|
|4706|**Process Log**|
|4707|**Application File**|
|4708|**Organization Statistic**|
|4709|**Site Map**|
|4710|**Process Session**|
|4711|**Expander Event**|
|4712|**Process Trigger**|
|4720|**Flow Session**|
|4724|**Process Stage**|
|4725|**Business Process Flow Instance**|
|4800|**Web Wizard**|
|4802|**Wizard Page**|
|4803|**Web Wizard Access Privilege**|
|4810|**Time Zone Definition**|
|4811|**Time Zone Rule**|
|4812|**Time Zone Localized Name**|
|5000|**Recently Used**|
|5004|**NL2SQ Registration Information**|
|7000|**System Application Metadata**|
|7001|**User Application Metadata**|
|7100|**Solution**|
|7101|**Publisher**|
|7102|**Publisher Address**|
|7103|**Solution Component**|
|7104|**Solution Component Definition**|
|7105|**Dependency**|
|7106|**Dependency Node**|
|7107|**Invalid Dependency**|
|7108|**Dependency Feature**|
|7200|**RuntimeDependency**|
|7755|**ElasticFileAttachment**|
|8000|**Post**|
|8001|**Post Role**|
|8002|**Post Regarding**|
|8003|**Follow**|
|8005|**Comment**|
|8006|**Like**|
|8040|**ACIViewMapper**|
|8050|**Trace**|
|8051|**Trace Association**|
|8052|**Trace Regarding**|
|8181|**Routing Rule Set**|
|8199|**Rule Item**|
|8700|**AppModule Metadata**|
|8701|**AppModule Metadata Dependency**|
|8702|**AppModule Metadata Async Operation**|
|8840|**Hierarchy Rule**|
|9006|**Model-driven App**|
|9007|**App Module Component**|
|9009|**App Module Roles**|
|9011|**App Config Master**|
|9012|**App Configuration**|
|9013|**App Configuration Instance**|
|9100|**Report**|
|9101|**Report Related Entity**|
|9102|**Report Related Category**|
|9103|**Report Visibility**|
|9104|**Report Link**|
|9105|**Currency**|
|9106|**Mail Merge Template**|
|9107|**Import Job**|
|9201|**LocalConfigStore**|
|9300|**Record Creation and Update Rule**|
|9301|**Record Creation and Update Rule Item**|
|9333|**Web Resource**|
|9400|**Channel Access Profile Rule**|
|9401|**Channel Access Profile Rule Item**|
|9502|**SharePoint Site**|
|9507|**Sharepoint Document**|
|9508|**Document Location**|
|9509|**SharePoint Data**|
|9510|**Rollup Properties**|
|9511|**Rollup Job**|
|9600|**Goal**|
|9602|**Rollup Query**|
|9603|**Goal Metric**|
|9604|**Rollup Field**|
|9605|**Email Server Profile**|
|9606|**Mailbox**|
|9607|**Mailbox Statistics**|
|9608|**Mailbox Auto Tracking Folder**|
|9609|**Mailbox Tracking Category**|
|9650|**Process Configuration**|
|9690|**Organization Insights Notification**|
|9699|**Organization Insights Metric**|
|9750|**SLA**|
|9751|**SLA Item**|
|9752|**SLA KPI Instance**|
|9753|**Custom Control**|
|9754|**Custom Control Resource**|
|9755|**Custom Control Default Config**|
|9800|**Entity**|
|9808|**Attribute**|
|9809|**OptionSet**|
|9810|**Entity Key**|
|9811|**Entity Relationship**|
|9812|**Managed Property**|
|9813|**Relationship Entity**|
|9814|**Relationship Attribute**|
|9815|**Entity Index**|
|9816|**Index Attribute**|
|9820|**Secured Masking Column**|
|9866|**Mobile Offline Profile**|
|9867|**Mobile Offline Profile Item**|
|9868|**Mobile Offline Profile Item Association**|
|9869|**Sync Error**|
|9870|**Offline Command Definition**|
|9875|**Language Provisioning State**|
|9880|**Ribbon Metadata To Process**|
|9890|**SolutionHistoryData**|
|9900|**Navigation Setting**|
|9910|**MultiEntitySearch**|
|9912|**Multi Select Option Value**|
|9919|**Hierarchy Security Configuration**|
|9930|**Knowledge Base Record**|
|9932|**Time Stamp Date Mapping**|
|9936|**Azure Service Connection**|
|9940|**Document Template**|
|9941|**Personal Document Template**|
|9945|**Text Analytics Entity Mapping**|
|9947|**Knowledge Search Model**|
|9949|**Advanced Similarity Rule**|
|9950|**Office Graph Document**|
|9951|**Similarity Rule**|
|9953|**Knowledge Article**|
|9955|**Knowledge Article Views**|
|9957|**Language**|
|9958|**Feedback**|
|9959|**Category**|
|9960|**Knowledge Article Category**|
|9961|**DelveActionHub**|
|9962|**Action Card**|
|9968|**ActionCardUserState**|
|9973|**Action Card User Settings**|
|9983|**Action Card Type**|
|9986|**Interaction for Email**|
|9987|**External Party Item**|
|9996|**HolidayWrapper**|
|9997|**Email Signature**|
|10000|**Solution Component Attribute Configuration**|
|10001|**Solution Component Batch Configuration**|
|10002|**Solution Component Configuration**|
|10003|**Solution Component Relationship Configuration**|
|10004|**Solution History**|
|10005|**Solution History Data Source**|
|10006|**Component Layer**|
|10007|**Component Layer Data Source**|
|10008|**Package**|
|10009|**Package History**|
|10011|**StageSolutionUpload**|
|10012|**ExportSolutionUpload**|
|10013|**FeatureControlSetting**|
|10014|**Solution Component Summary**|
|10015|**Solution Component Count Summary**|
|10016|**Solution Component Data Source**|
|10017|**Solution Component Count Data Source**|
|10018|**Microsoft Entra ID**|
|10019|**Staged Entity**|
|10020|**Staged Entity Attribute**|
|10021|**Staged Metadata Async Operation**|
|10022|**Key Vault Reference**|
|10023|**Managed Identity**|
|10024|**Catalog**|
|10025|**Catalog Assignment**|
|10026|**Internal Catalog Assignment**|
|10027|**Custom API**|
|10028|**Custom API Request Parameter**|
|10029|**Custom API Response Property**|
|10030|**Plugin Package**|
|10031|**NonRelational Data Source**|
|10032|**ProvisionLanguageForUser**|
|10033|**Shared Object**|
|10034|**Shared Workspace**|
|10035|**Shared Workspace Pool**|
|10036|**Data Lake Folder**|
|10037|**Data Lake Folder Permission**|
|10038|**Data Lake Workspace**|
|10039|**Data Lake Workspace Permission**|
|10040|**Data Processing configuration**|
|10041|**Exported Excel**|
|10042|**RetainedData Excel**|
|10043|**Synapse Database**|
|10044|**Synapse Link External Table State**|
|10045|**Synapse Link Profile**|
|10046|**Synapse Link Profile Entity**|
|10047|**Synapse Link Profile Entity State**|
|10048|**Synapse Link Schedule**|
|10049|**Component Version**|
|10050|**Component Version Data Source**|
|10051|**Component Version (Internal)**|
|10052|**DataflowRefreshHistory**|
|10053|**EntityRefreshHistory**|
|10054|**Shared Link Setting**|
|10055|**DelegatedAuthorization**|
|10057|**CascadeGrantRevokeAccessRecordsTracker**|
|10058|**CascadeGrantRevokeAccessVersionTracker**|
|10059|**RevokeInheritedAccessRecordsTracker**|
|10060|**TdsMetadata**|
|10061|**Model-Driven App Element**|
|10062|**Model-Driven App Component Node's Edge**|
|10063|**Model-Driven App Component Node**|
|10064|**Model-Driven App Setting**|
|10065|**Model-Driven App User Setting**|
|10066|**Organization Setting**|
|10067|**Setting Definition**|
|10068|**CanvasApp Extended Metadata**|
|10069|**Service Plan Mapping**|
|10070|**Service Plan Custom Control**|
|10072|**ApplicationUser**|
|10075|**OData v4 Data Source**|
|10076|**Workflow Binary**|
|10077|**Credential**|
|10078|**Desktop Flow Module**|
|10079|**Flow Capacity Assignment**|
|10080|**Flow Credential Application**|
|10081|**Flow Event**|
|10082|**Flow Machine**|
|10083|**Flow Machine Group**|
|10084|**Flow Machine Image**|
|10085|**Flow Machine Image Version**|
|10086|**Flow Machine Network**|
|10087|**ProcessStageParameter**|
|10088|**Work Queue**|
|10089|**Work Queue Item**|
|10090|**Desktop Flow Binary**|
|10091|**Flow Log**|
|10092|**Flow Run**|
|10093|**Action Approval Model**|
|10094|**Approval**|
|10095|**Approval Request**|
|10096|**Approval Response**|
|10097|**Approval Step**|
|10098|**Await All Action Approval Model**|
|10099|**Await All Approval Model**|
|10100|**Basic Approval Model Data**|
|10101|**Flow Approval**|
|10110|**Connection Reference**|
|10111|**DVFileSearch**|
|10112|**DVFileSearchAttribute**|
|10113|**DVFileSearchEntity**|
|10114|**DVTableSearch**|
|10115|**DVTableSearchAttribute**|
|10116|**DVTableSearchEntity**|
|10117|**AICopilot**|
|10118|**AIPluginAuth**|
|10119|**AI Plugin Conversation Starter**|
|10120|**AI Plugin Conversation Starter Mapping**|
|10121|**AI Plugin Governance**|
|10122|**AI Plugin Governance Extended**|
|10123|**AIPluginOperationResponseTemplate**|
|10124|**AIPluginTitle**|
|10125|**SideloadedAIPlugin**|
|10126|**AIPlugin**|
|10127|**AIPluginExternalSchema**|
|10128|**AIPluginExternalSchemaProperty**|
|10129|**AIPluginInstance**|
|10130|**AIPluginOperation**|
|10131|**AIPluginOperationParameter**|
|10132|**AIPluginUserSetting**|
|10134|**AI Event**|
|10135|**AI Builder Feedback Loop**|
|10136|**AI Form Processing Document**|
|10137|**AI Object Detection Image**|
|10138|**AI Object Detection Label**|
|10139|**AI Object Detection Bounding Box**|
|10140|**AI Object Detection Image Mapping**|
|10142|**AI Builder Dataset**|
|10143|**AI Builder Dataset File**|
|10144|**AI Builder Dataset Record**|
|10145|**AI Builder Datasets Container**|
|10146|**AI Builder File**|
|10147|**AI Builder File Attached Data**|
|10148|**Help Page**|
|10149|**Tour**|
|10150|**BotContent**|
|10151|**ConversationTranscript**|
|10152|**Copilot**|
|10153|**Copilot component**|
|10154|**Copilot component collection**|
|10165|**Comment**|
|10166|**Fabric AISkill**|
|10167|**App Insights Metadata**|
|10168|**Dataflow Connection Reference**|
|10169|**Schedule**|
|10170|**Dataflow Template**|
|10171|**Dataflow DatalakeFolder**|
|10172|**Data Movement Service Request**|
|10173|**Data Movement Service Request Status**|
|10174|**DMS Sync Request**|
|10175|**DMS Sync Status**|
|10176|**Knowledge Asset Configuration**|
|10177|**Module Run Detail**|
|10178|**Salesforce Structured Object**|
|10179|**Salesforce Structured QnA Config**|
|10180|**Workflow Action Status**|
|10181|**FederatedKnowledgeConfiguration**|
|10182|**FederatedKnowledgeEntityConfiguration**|
|10183|**PDF Setting**|
|10184|**Activity File Attachment**|
|10185|**Teams chat**|
|10186|**Service Configuration**|
|10187|**SLA KPI**|
|10188|**Integrated search provider**|
|10189|**Knowledge Management Setting**|
|10190|**Knowledge Federated Article**|
|10191|**Knowledge Federated Article Incident**|
|10192|**Search provider**|
|10193|**Knowledge Article Image**|
|10194|**Knowledge Configuration**|
|10195|**Knowledge Interaction Insight**|
|10196|**Knowledge Search Insight**|
|10197|**Favorite knowledge article**|
|10198|**Knowledge article language setting**|
|10199|**Knowledge Article Attachment**|
|10200|**Knowledge personalization**|
|10201|**Knowledge Article Template**|
|10202|**Knowledge search personal filter config**|
|10203|**Knowledge search filter**|
|10205|**SupportUserTable**|
|10206|**FxExpression**|
|10207|**PowerfxRule**|
|10208|**Planner Business Scenario**|
|10209|**Planner Sync Action**|
|10210|**Ms Graph Resource To Subscription**|
|10211|**Virtual Entity  Metadata**|
|10212|**Background Operation**|
|10213|**Report Parameter**|
|10214|**MobileOfflineProfileExtension**|
|10215|**MobileOfflineProfileItemFilter**|
|10216|**TeamMobileOfflineProfileMembership**|
|10217|**UserMobileOfflineProfileMembership**|
|10218|**OrganizationDataSyncSubscription**|
|10219|**OrganizationDataSyncSubscriptionEntity**|
|10220|**OrganizationDataSyncSubscriptionFnoTable**|
|10221|**OrganizationDataSyncFnoState**|
|10222|**OrganizationDataSyncState**|
|10223|**ArchiveCleanupInfo**|
|10224|**ArchiveCleanupOperation**|
|10225|**BulkArchiveConfig**|
|10226|**BulkArchiveFailureDetail**|
|10227|**BulkArchiveOperation**|
|10228|**BulkArchiveOperationDetail**|
|10229|**EnableArchivalRequest**|
|10230|**MetadataForArchival**|
|10231|**ReconciliationEntityInfo**|
|10232|**ReconciliationEntityStepInfo**|
|10233|**ReconciliationInfo**|
|10234|**RetentionCleanupInfo**|
|10235|**RetentionCleanupOperation**|
|10236|**RetentionConfig**|
|10237|**RetentionFailureDetail**|
|10238|**RetentionOperation**|
|10239|**RetentionOperationDetail**|
|10240|**Notification**|
|10241|**User Rating**|
|10242|**Mobile App**|
|10243|**Insights Store Data Source**|
|10244|**Insights Store Virtual Entity**|
|10245|**RoleEditorLayout**|
|10246|**Deleted Record Reference**|
|10247|**Restore Deleted Records Configuration**|
|10248|**App Action**|
|10249|**App Action Migration**|
|10250|**App Action Rule**|
|10253|**Card**|
|10254|**Card State Item**|
|10257|**Entity link chat configuration**|
|10258|**Rich Text Attachment**|
|10259|**Custom Control Extended Setting**|
|10260|**Timeline Pin**|
|10261|**Virtual Connector Data Source**|
|10262|**Virtual Table Column Candidate**|
|10264|**PM Analysis History**|
|10265|**PM Business Rule Automation Config**|
|10266|**PM Calendar**|
|10267|**PM Calendar Version**|
|10268|**PM Inferred Task**|
|10269|**PM Process Extended Metadata Version**|
|10270|**PM Process Template**|
|10271|**PM Process User Settings**|
|10272|**PM Process Version**|
|10273|**PM Recording**|
|10274|**PM Simulation**|
|10275|**PM Template**|
|10276|**PM View**|
|10277|**Analysis Component**|
|10278|**Analysis Job**|
|10279|**Analysis Override**|
|10280|**Analysis Result**|
|10281|**Analysis Result Detail**|
|10282|**Solution Health Rule**|
|10283|**Solution Health Rule Argument**|
|10284|**Solution Health Rule Set**|
|10285|**Power BI Dataset**|
|10286|**powerbidatasetapdx**|
|10287|**Power BI Mashup Parameter**|
|10288|**Power BI Report**|
|10289|**powerbireportapdx**|
|10290|**File Upload**|
|10291|**MainFewShot**|
|10292|**MakerFewShot**|
|10293|**SearchAttributeSettings**|
|10294|**SearchCustomAnalyzer**|
|10295|**SearchRelationshipSettings**|
|10296|**SearchResultsCache**|
|10297|**Search Telemetry**|
|10298|**ViewAsExampleQuestion**|
|10299|**CopilotExampleQuestion**|
|10300|**CopilotGlossaryTerm**|
|10301|**CopilotSynonyms**|
|10302|**Site Component**|
|10303|**Site**|
|10304|**Site Language**|
|10305|**Power Pages Site Published**|
|10308|**External Identity**|
|10309|**Invitation**|
|10310|**Invite Redemption**|
|10311|**Portal Comment**|
|10312|**Setting**|
|10313|**Multistep Form Session**|
|10317|**Ad Placement**|
|10318|**Column Permission**|
|10319|**Column Permission Profile**|
|10320|**Content Snippet**|
|10321|**Basic Form**|
|10322|**Basic Form Metadata**|
|10323|**List**|
|10324|**Table Permission**|
|10325|**Page Template**|
|10326|**Poll Placement**|
|10327|**Power Pages Core Entity DS**|
|10328|**Publishing State**|
|10329|**Publishing State Transition Rule**|
|10330|**Redirect**|
|10331|**Shortcut**|
|10332|**Site Marker**|
|10333|**Site Setting**|
|10334|**Web File**|
|10335|**Multistep Form**|
|10336|**Multistep Form Metadata**|
|10337|**Form Step**|
|10338|**Web Link**|
|10339|**Web Link Set**|
|10340|**Web Page**|
|10341|**Web Page Access Control Rule**|
|10342|**Web Role**|
|10343|**Website**|
|10344|**Website Access**|
|10345|**Website Language**|
|10346|**Web Template**|
|10353|**Power Pages Scan Report**|
|10354|**Power Pages Log**|
|10359|**Catalog Submission Files**|
|10360|**Package Submission Store**|
|10531|**Form Mapping**|
|18085|**Event Expander Breadcrumb**|

### <a name="BKMK_ComponentState"></a> ComponentState

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Component State**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`componentstate`|
|RequiredLevel|SystemRequired|
|Type|Picklist|
|DefaultFormValue|-1|
|GlobalChoiceName|`componentstate`|

#### ComponentState Choices/Options

|Value|Label|
|---|---|
|0|**Published**|
|1|**Unpublished**|
|2|**Deleted**|
|3|**Deleted Unpublished**|

### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|---|---|
|Description|**Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.**|
|DisplayName|**Created On**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`createdon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the delegate user who created the record.**|
|DisplayName|**Created By (Delegate)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_ExchangeRate"></a> ExchangeRate

|Property|Value|
|---|---|
|Description|**Exchange rate for the currency associated with the SimilarityRule with respect to the base currency.**|
|DisplayName|**ExchangeRate**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`exchangerate`|
|RequiredLevel|None|
|Type|Decimal|
|ImeMode|Disabled|
|MaxValue|100000000000|
|MinValue|1E-12|
|Precision|12|
|SourceTypeMask|0|

### <a name="BKMK_IsManaged"></a> IsManaged

|Property|Value|
|---|---|
|Description|**Is Managed**|
|DisplayName|**State**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`ismanaged`|
|RequiredLevel|SystemRequired|
|Type|Boolean|
|GlobalChoiceName|`ismanaged`|
|DefaultValue|False|
|True Label|Managed|
|False Label|Unmanaged|

### <a name="BKMK_MatchingEntityTypeCode"></a> MatchingEntityTypeCode

|Property|Value|
|---|---|
|Description|**Record type of the records being evaluated as potential similarities.**|
|DisplayName|**Matching Record Type**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`matchingentitytypecode`|
|RequiredLevel|SystemRequired|
|Type|Picklist|
|DefaultFormValue|0|
|GlobalChoiceName|`similarityrule_matchingentitytypecode`|

#### MatchingEntityTypeCode Choices/Options

|Value|Label|
|---|---|
|1|**Account**|
|2|**Contact**|
|5|**Note**|
|6|**Business Unit Map**|
|7|**Owner**|
|8|**User**|
|9|**Team**|
|10|**Business Unit**|
|14|**System User Principal**|
|29|**Subscription**|
|30|**Filter Template**|
|31|**Privilege Object Type Code**|
|33|**Subscription Synchronization Information**|
|35|**Tracking information for deleted entities**|
|36|**Client update**|
|37|**Subscription Manually Tracked Object**|
|42|**SystemUser BusinessUnit Entity Map**|
|44|**Field Sharing**|
|45|**Subscription Statistic Offline**|
|46|**Subscription Statistic Outlook**|
|47|**Subscription Sync Entry Offline**|
|48|**Subscription Sync Entry Outlook**|
|50|**Position**|
|51|**System User Manager Map**|
|52|**User Search Facet**|
|54|**Global Search Configuration**|
|55|**FileAttachment**|
|60|**SystemUserAuthorizationChangeTracker**|
|61|**PrincipalEntityBusinessUnitMap**|
|72|**Record Filter**|
|73|**EntityRecordFilter**|
|74|**Secured Masking Rule**|
|75|**Privilege Checker Run**|
|76|**Privilege Checker Log**|
|78|**Virtual Entity Data Provider**|
|85|**Virtual Entity Data Source**|
|92|**Team template**|
|99|**Social Profile**|
|101|**Service Plan**|
|103|**Privileges Removal Setting**|
|126|**Indexed Article**|
|127|**Article**|
|129|**Subject**|
|132|**Announcement**|
|135|**Activity Party**|
|150|**User Settings**|
|300|**Canvas App**|
|301|**Callback Registration**|
|372|**Connector**|
|373|**Connection Instance**|
|380|**Environment Variable Definition**|
|381|**Environment Variable Value**|
|400|**AI Template**|
|401|**AI Model**|
|402|**AI Configuration**|
|418|**Dataflow**|
|430|**Entity Analytics Config**|
|431|**Image Attribute Configuration**|
|432|**Entity Image Configuration**|
|950|**New Process**|
|951|**Translation Process**|
|955|**Expired Process**|
|1001|**Attachment**|
|1002|**Attachment**|
|1003|**Internal Address**|
|1007|**Image Descriptor**|
|1016|**Article Template**|
|1019|**Organization**|
|1021|**Organization UI**|
|1023|**Privilege**|
|1030|**System Form**|
|1031|**User Dashboard**|
|1036|**Security Role**|
|1037|**Role Template**|
|1039|**View**|
|1043|**String Map**|
|1071|**Address**|
|1072|**Subscription Clients**|
|1075|**Status Map**|
|1082|**Article Comment**|
|1086|**User Fiscal Calendar**|
|1094|**Authorization Server**|
|1095|**Partner Application**|
|1111|**System Chart**|
|1112|**User Chart**|
|1113|**Ribbon Tab To Command Mapping**|
|1115|**Ribbon Context Group**|
|1116|**Ribbon Command**|
|1117|**Ribbon Rule**|
|1120|**Application Ribbons**|
|1130|**Ribbon Difference**|
|1140|**Replication Backlog**|
|1189|**Document Suggestions**|
|1190|**SuggestionCardTemplate**|
|1200|**Field Security Profile**|
|1201|**Field Permission**|
|1203|**Team Profiles**|
|1204|**Application**|
|1234|**Channel Property Group**|
|1236|**Channel Property**|
|1300|**SocialInsightsConfiguration**|
|1309|**Saved Organization Insights Configuration**|
|1400|**Sync Attribute Mapping Profile**|
|1401|**Sync Attribute Mapping**|
|1403|**Team Sync-Attribute Mapping Profiles**|
|1404|**Principal Sync Attribute Map**|
|2000|**Annual Fiscal Calendar**|
|2001|**Semiannual Fiscal Calendar**|
|2002|**Quarterly Fiscal Calendar**|
|2003|**Monthly Fiscal Calendar**|
|2004|**Fixed Monthly Fiscal Calendar**|
|2010|**Email Template**|
|2012|**Unresolved Address**|
|2013|**Territory**|
|2015|**Theme**|
|2016|**User Mapping**|
|2020|**Queue**|
|2023|**QueueItemCount**|
|2024|**QueueMemberCount**|
|2027|**License**|
|2029|**Queue Item**|
|2500|**User Entity UI Settings**|
|2501|**User Entity Instance Data**|
|3000|**Integration Status**|
|3005|**Channel Access Profile**|
|3008|**External Party**|
|3231|**Connection Role**|
|3233|**Connection Role Object Type Code**|
|3234|**Connection**|
|4003|**Calendar**|
|4004|**Calendar Rule**|
|4011|**Inter Process Lock**|
|4023|**Email Hash**|
|4101|**Display String Map**|
|4102|**Display String**|
|4110|**Notification**|
|4120|**Exchange Sync Id Mapping**|
|4200|**Activity**|
|4201|**Appointment**|
|4202|**Email**|
|4204|**Fax**|
|4207|**Letter**|
|4210|**Phone Call**|
|4212|**Task**|
|4216|**Social Activity**|
|4220|**UntrackedEmail**|
|4230|**Saved View**|
|4231|**Metadata Difference**|
|4232|**Business Data Localized Label**|
|4250|**Recurrence Rule**|
|4251|**Recurring Appointment**|
|4299|**Email Search**|
|4410|**Data Import**|
|4411|**Data Map**|
|4412|**Import Source File**|
|4413|**Import Data**|
|4414|**Duplicate Detection Rule**|
|4415|**Duplicate Record**|
|4416|**Duplicate Rule Condition**|
|4417|**Column Mapping**|
|4418|**List Value Mapping**|
|4419|**Lookup Mapping**|
|4420|**Owner Mapping**|
|4423|**Import Log**|
|4424|**Bulk Delete Operation**|
|4425|**Bulk Delete Failure**|
|4426|**Transformation Mapping**|
|4427|**Transformation Parameter Mapping**|
|4428|**Import Entity Mapping**|
|4450|**Data Performance Dashboard**|
|4490|**Office Document**|
|4500|**Relationship Role**|
|4501|**Relationship Role Map**|
|4502|**Customer Relationship**|
|4567|**Auditing**|
|4579|**Ribbon Client Metadata.**|
|4600|**Entity Map**|
|4601|**Attribute Map**|
|4602|**Plug-in Type**|
|4603|**Plug-in Type Statistic**|
|4605|**Plug-in Assembly**|
|4606|**Sdk Message**|
|4607|**Sdk Message Filter**|
|4608|**Sdk Message Processing Step**|
|4609|**Sdk Message Request**|
|4610|**Sdk Message Response**|
|4611|**Sdk Message Response Field**|
|4613|**Sdk Message Pair**|
|4614|**Sdk Message Request Field**|
|4615|**Sdk Message Processing Step Image**|
|4616|**Sdk Message Processing Step Secure Configuration**|
|4618|**Service Endpoint**|
|4619|**Plug-in Trace Log**|
|4700|**System Job**|
|4702|**Workflow Wait Subscription**|
|4703|**Process**|
|4704|**Process Dependency**|
|4705|**ISV Config**|
|4706|**Process Log**|
|4707|**Application File**|
|4708|**Organization Statistic**|
|4709|**Site Map**|
|4710|**Process Session**|
|4711|**Expander Event**|
|4712|**Process Trigger**|
|4720|**Flow Session**|
|4724|**Process Stage**|
|4725|**Business Process Flow Instance**|
|4800|**Web Wizard**|
|4802|**Wizard Page**|
|4803|**Web Wizard Access Privilege**|
|4810|**Time Zone Definition**|
|4811|**Time Zone Rule**|
|4812|**Time Zone Localized Name**|
|5000|**Recently Used**|
|5004|**NL2SQ Registration Information**|
|7000|**System Application Metadata**|
|7001|**User Application Metadata**|
|7100|**Solution**|
|7101|**Publisher**|
|7102|**Publisher Address**|
|7103|**Solution Component**|
|7104|**Solution Component Definition**|
|7105|**Dependency**|
|7106|**Dependency Node**|
|7107|**Invalid Dependency**|
|7108|**Dependency Feature**|
|7200|**RuntimeDependency**|
|7755|**ElasticFileAttachment**|
|8000|**Post**|
|8001|**Post Role**|
|8002|**Post Regarding**|
|8003|**Follow**|
|8005|**Comment**|
|8006|**Like**|
|8040|**ACIViewMapper**|
|8050|**Trace**|
|8051|**Trace Association**|
|8052|**Trace Regarding**|
|8181|**Routing Rule Set**|
|8199|**Rule Item**|
|8700|**AppModule Metadata**|
|8701|**AppModule Metadata Dependency**|
|8702|**AppModule Metadata Async Operation**|
|8840|**Hierarchy Rule**|
|9006|**Model-driven App**|
|9007|**App Module Component**|
|9009|**App Module Roles**|
|9011|**App Config Master**|
|9012|**App Configuration**|
|9013|**App Configuration Instance**|
|9100|**Report**|
|9101|**Report Related Entity**|
|9102|**Report Related Category**|
|9103|**Report Visibility**|
|9104|**Report Link**|
|9105|**Currency**|
|9106|**Mail Merge Template**|
|9107|**Import Job**|
|9201|**LocalConfigStore**|
|9300|**Record Creation and Update Rule**|
|9301|**Record Creation and Update Rule Item**|
|9333|**Web Resource**|
|9400|**Channel Access Profile Rule**|
|9401|**Channel Access Profile Rule Item**|
|9502|**SharePoint Site**|
|9507|**Sharepoint Document**|
|9508|**Document Location**|
|9509|**SharePoint Data**|
|9510|**Rollup Properties**|
|9511|**Rollup Job**|
|9600|**Goal**|
|9602|**Rollup Query**|
|9603|**Goal Metric**|
|9604|**Rollup Field**|
|9605|**Email Server Profile**|
|9606|**Mailbox**|
|9607|**Mailbox Statistics**|
|9608|**Mailbox Auto Tracking Folder**|
|9609|**Mailbox Tracking Category**|
|9650|**Process Configuration**|
|9690|**Organization Insights Notification**|
|9699|**Organization Insights Metric**|
|9750|**SLA**|
|9751|**SLA Item**|
|9752|**SLA KPI Instance**|
|9753|**Custom Control**|
|9754|**Custom Control Resource**|
|9755|**Custom Control Default Config**|
|9800|**Entity**|
|9808|**Attribute**|
|9809|**OptionSet**|
|9810|**Entity Key**|
|9811|**Entity Relationship**|
|9812|**Managed Property**|
|9813|**Relationship Entity**|
|9814|**Relationship Attribute**|
|9815|**Entity Index**|
|9816|**Index Attribute**|
|9820|**Secured Masking Column**|
|9866|**Mobile Offline Profile**|
|9867|**Mobile Offline Profile Item**|
|9868|**Mobile Offline Profile Item Association**|
|9869|**Sync Error**|
|9870|**Offline Command Definition**|
|9875|**Language Provisioning State**|
|9880|**Ribbon Metadata To Process**|
|9890|**SolutionHistoryData**|
|9900|**Navigation Setting**|
|9910|**MultiEntitySearch**|
|9912|**Multi Select Option Value**|
|9919|**Hierarchy Security Configuration**|
|9930|**Knowledge Base Record**|
|9932|**Time Stamp Date Mapping**|
|9936|**Azure Service Connection**|
|9940|**Document Template**|
|9941|**Personal Document Template**|
|9945|**Text Analytics Entity Mapping**|
|9947|**Knowledge Search Model**|
|9949|**Advanced Similarity Rule**|
|9950|**Office Graph Document**|
|9951|**Similarity Rule**|
|9953|**Knowledge Article**|
|9955|**Knowledge Article Views**|
|9957|**Language**|
|9958|**Feedback**|
|9959|**Category**|
|9960|**Knowledge Article Category**|
|9961|**DelveActionHub**|
|9962|**Action Card**|
|9968|**ActionCardUserState**|
|9973|**Action Card User Settings**|
|9983|**Action Card Type**|
|9986|**Interaction for Email**|
|9987|**External Party Item**|
|9996|**HolidayWrapper**|
|9997|**Email Signature**|
|10000|**Solution Component Attribute Configuration**|
|10001|**Solution Component Batch Configuration**|
|10002|**Solution Component Configuration**|
|10003|**Solution Component Relationship Configuration**|
|10004|**Solution History**|
|10005|**Solution History Data Source**|
|10006|**Component Layer**|
|10007|**Component Layer Data Source**|
|10008|**Package**|
|10009|**Package History**|
|10011|**StageSolutionUpload**|
|10012|**ExportSolutionUpload**|
|10013|**FeatureControlSetting**|
|10014|**Solution Component Summary**|
|10015|**Solution Component Count Summary**|
|10016|**Solution Component Data Source**|
|10017|**Solution Component Count Data Source**|
|10018|**Microsoft Entra ID**|
|10019|**Staged Entity**|
|10020|**Staged Entity Attribute**|
|10021|**Staged Metadata Async Operation**|
|10022|**Key Vault Reference**|
|10023|**Managed Identity**|
|10024|**Catalog**|
|10025|**Catalog Assignment**|
|10026|**Internal Catalog Assignment**|
|10027|**Custom API**|
|10028|**Custom API Request Parameter**|
|10029|**Custom API Response Property**|
|10030|**Plugin Package**|
|10031|**NonRelational Data Source**|
|10032|**ProvisionLanguageForUser**|
|10033|**Shared Object**|
|10034|**Shared Workspace**|
|10035|**Shared Workspace Pool**|
|10036|**Data Lake Folder**|
|10037|**Data Lake Folder Permission**|
|10038|**Data Lake Workspace**|
|10039|**Data Lake Workspace Permission**|
|10040|**Data Processing configuration**|
|10041|**Exported Excel**|
|10042|**RetainedData Excel**|
|10043|**Synapse Database**|
|10044|**Synapse Link External Table State**|
|10045|**Synapse Link Profile**|
|10046|**Synapse Link Profile Entity**|
|10047|**Synapse Link Profile Entity State**|
|10048|**Synapse Link Schedule**|
|10049|**Component Version**|
|10050|**Component Version Data Source**|
|10051|**Component Version (Internal)**|
|10052|**DataflowRefreshHistory**|
|10053|**EntityRefreshHistory**|
|10054|**Shared Link Setting**|
|10055|**DelegatedAuthorization**|
|10057|**CascadeGrantRevokeAccessRecordsTracker**|
|10058|**CascadeGrantRevokeAccessVersionTracker**|
|10059|**RevokeInheritedAccessRecordsTracker**|
|10060|**TdsMetadata**|
|10061|**Model-Driven App Element**|
|10062|**Model-Driven App Component Node's Edge**|
|10063|**Model-Driven App Component Node**|
|10064|**Model-Driven App Setting**|
|10065|**Model-Driven App User Setting**|
|10066|**Organization Setting**|
|10067|**Setting Definition**|
|10068|**CanvasApp Extended Metadata**|
|10069|**Service Plan Mapping**|
|10070|**Service Plan Custom Control**|
|10072|**ApplicationUser**|
|10075|**OData v4 Data Source**|
|10076|**Workflow Binary**|
|10077|**Credential**|
|10078|**Desktop Flow Module**|
|10079|**Flow Capacity Assignment**|
|10080|**Flow Credential Application**|
|10081|**Flow Event**|
|10082|**Flow Machine**|
|10083|**Flow Machine Group**|
|10084|**Flow Machine Image**|
|10085|**Flow Machine Image Version**|
|10086|**Flow Machine Network**|
|10087|**ProcessStageParameter**|
|10088|**Work Queue**|
|10089|**Work Queue Item**|
|10090|**Desktop Flow Binary**|
|10091|**Flow Log**|
|10092|**Flow Run**|
|10093|**Action Approval Model**|
|10094|**Approval**|
|10095|**Approval Request**|
|10096|**Approval Response**|
|10097|**Approval Step**|
|10098|**Await All Action Approval Model**|
|10099|**Await All Approval Model**|
|10100|**Basic Approval Model Data**|
|10101|**Flow Approval**|
|10110|**Connection Reference**|
|10111|**DVFileSearch**|
|10112|**DVFileSearchAttribute**|
|10113|**DVFileSearchEntity**|
|10114|**DVTableSearch**|
|10115|**DVTableSearchAttribute**|
|10116|**DVTableSearchEntity**|
|10117|**AICopilot**|
|10118|**AIPluginAuth**|
|10119|**AI Plugin Conversation Starter**|
|10120|**AI Plugin Conversation Starter Mapping**|
|10121|**AI Plugin Governance**|
|10122|**AI Plugin Governance Extended**|
|10123|**AIPluginOperationResponseTemplate**|
|10124|**AIPluginTitle**|
|10125|**SideloadedAIPlugin**|
|10126|**AIPlugin**|
|10127|**AIPluginExternalSchema**|
|10128|**AIPluginExternalSchemaProperty**|
|10129|**AIPluginInstance**|
|10130|**AIPluginOperation**|
|10131|**AIPluginOperationParameter**|
|10132|**AIPluginUserSetting**|
|10134|**AI Event**|
|10135|**AI Builder Feedback Loop**|
|10136|**AI Form Processing Document**|
|10137|**AI Object Detection Image**|
|10138|**AI Object Detection Label**|
|10139|**AI Object Detection Bounding Box**|
|10140|**AI Object Detection Image Mapping**|
|10142|**AI Builder Dataset**|
|10143|**AI Builder Dataset File**|
|10144|**AI Builder Dataset Record**|
|10145|**AI Builder Datasets Container**|
|10146|**AI Builder File**|
|10147|**AI Builder File Attached Data**|
|10148|**Help Page**|
|10149|**Tour**|
|10150|**BotContent**|
|10151|**ConversationTranscript**|
|10152|**Copilot**|
|10153|**Copilot component**|
|10154|**Copilot component collection**|
|10165|**Comment**|
|10166|**Fabric AISkill**|
|10167|**App Insights Metadata**|
|10168|**Dataflow Connection Reference**|
|10169|**Schedule**|
|10170|**Dataflow Template**|
|10171|**Dataflow DatalakeFolder**|
|10172|**Data Movement Service Request**|
|10173|**Data Movement Service Request Status**|
|10174|**DMS Sync Request**|
|10175|**DMS Sync Status**|
|10176|**Knowledge Asset Configuration**|
|10177|**Module Run Detail**|
|10178|**Salesforce Structured Object**|
|10179|**Salesforce Structured QnA Config**|
|10180|**Workflow Action Status**|
|10181|**FederatedKnowledgeConfiguration**|
|10182|**FederatedKnowledgeEntityConfiguration**|
|10183|**PDF Setting**|
|10184|**Activity File Attachment**|
|10185|**Teams chat**|
|10186|**Service Configuration**|
|10187|**SLA KPI**|
|10188|**Integrated search provider**|
|10189|**Knowledge Management Setting**|
|10190|**Knowledge Federated Article**|
|10191|**Knowledge Federated Article Incident**|
|10192|**Search provider**|
|10193|**Knowledge Article Image**|
|10194|**Knowledge Configuration**|
|10195|**Knowledge Interaction Insight**|
|10196|**Knowledge Search Insight**|
|10197|**Favorite knowledge article**|
|10198|**Knowledge article language setting**|
|10199|**Knowledge Article Attachment**|
|10200|**Knowledge personalization**|
|10201|**Knowledge Article Template**|
|10202|**Knowledge search personal filter config**|
|10203|**Knowledge search filter**|
|10205|**SupportUserTable**|
|10206|**FxExpression**|
|10207|**PowerfxRule**|
|10208|**Planner Business Scenario**|
|10209|**Planner Sync Action**|
|10210|**Ms Graph Resource To Subscription**|
|10211|**Virtual Entity  Metadata**|
|10212|**Background Operation**|
|10213|**Report Parameter**|
|10214|**MobileOfflineProfileExtension**|
|10215|**MobileOfflineProfileItemFilter**|
|10216|**TeamMobileOfflineProfileMembership**|
|10217|**UserMobileOfflineProfileMembership**|
|10218|**OrganizationDataSyncSubscription**|
|10219|**OrganizationDataSyncSubscriptionEntity**|
|10220|**OrganizationDataSyncSubscriptionFnoTable**|
|10221|**OrganizationDataSyncFnoState**|
|10222|**OrganizationDataSyncState**|
|10223|**ArchiveCleanupInfo**|
|10224|**ArchiveCleanupOperation**|
|10225|**BulkArchiveConfig**|
|10226|**BulkArchiveFailureDetail**|
|10227|**BulkArchiveOperation**|
|10228|**BulkArchiveOperationDetail**|
|10229|**EnableArchivalRequest**|
|10230|**MetadataForArchival**|
|10231|**ReconciliationEntityInfo**|
|10232|**ReconciliationEntityStepInfo**|
|10233|**ReconciliationInfo**|
|10234|**RetentionCleanupInfo**|
|10235|**RetentionCleanupOperation**|
|10236|**RetentionConfig**|
|10237|**RetentionFailureDetail**|
|10238|**RetentionOperation**|
|10239|**RetentionOperationDetail**|
|10240|**Notification**|
|10241|**User Rating**|
|10242|**Mobile App**|
|10243|**Insights Store Data Source**|
|10244|**Insights Store Virtual Entity**|
|10245|**RoleEditorLayout**|
|10246|**Deleted Record Reference**|
|10247|**Restore Deleted Records Configuration**|
|10248|**App Action**|
|10249|**App Action Migration**|
|10250|**App Action Rule**|
|10253|**Card**|
|10254|**Card State Item**|
|10257|**Entity link chat configuration**|
|10258|**Rich Text Attachment**|
|10259|**Custom Control Extended Setting**|
|10260|**Timeline Pin**|
|10261|**Virtual Connector Data Source**|
|10262|**Virtual Table Column Candidate**|
|10264|**PM Analysis History**|
|10265|**PM Business Rule Automation Config**|
|10266|**PM Calendar**|
|10267|**PM Calendar Version**|
|10268|**PM Inferred Task**|
|10269|**PM Process Extended Metadata Version**|
|10270|**PM Process Template**|
|10271|**PM Process User Settings**|
|10272|**PM Process Version**|
|10273|**PM Recording**|
|10274|**PM Simulation**|
|10275|**PM Template**|
|10276|**PM View**|
|10277|**Analysis Component**|
|10278|**Analysis Job**|
|10279|**Analysis Override**|
|10280|**Analysis Result**|
|10281|**Analysis Result Detail**|
|10282|**Solution Health Rule**|
|10283|**Solution Health Rule Argument**|
|10284|**Solution Health Rule Set**|
|10285|**Power BI Dataset**|
|10286|**powerbidatasetapdx**|
|10287|**Power BI Mashup Parameter**|
|10288|**Power BI Report**|
|10289|**powerbireportapdx**|
|10290|**File Upload**|
|10291|**MainFewShot**|
|10292|**MakerFewShot**|
|10293|**SearchAttributeSettings**|
|10294|**SearchCustomAnalyzer**|
|10295|**SearchRelationshipSettings**|
|10296|**SearchResultsCache**|
|10297|**Search Telemetry**|
|10298|**ViewAsExampleQuestion**|
|10299|**CopilotExampleQuestion**|
|10300|**CopilotGlossaryTerm**|
|10301|**CopilotSynonyms**|
|10302|**Site Component**|
|10303|**Site**|
|10304|**Site Language**|
|10305|**Power Pages Site Published**|
|10308|**External Identity**|
|10309|**Invitation**|
|10310|**Invite Redemption**|
|10311|**Portal Comment**|
|10312|**Setting**|
|10313|**Multistep Form Session**|
|10317|**Ad Placement**|
|10318|**Column Permission**|
|10319|**Column Permission Profile**|
|10320|**Content Snippet**|
|10321|**Basic Form**|
|10322|**Basic Form Metadata**|
|10323|**List**|
|10324|**Table Permission**|
|10325|**Page Template**|
|10326|**Poll Placement**|
|10327|**Power Pages Core Entity DS**|
|10328|**Publishing State**|
|10329|**Publishing State Transition Rule**|
|10330|**Redirect**|
|10331|**Shortcut**|
|10332|**Site Marker**|
|10333|**Site Setting**|
|10334|**Web File**|
|10335|**Multistep Form**|
|10336|**Multistep Form Metadata**|
|10337|**Form Step**|
|10338|**Web Link**|
|10339|**Web Link Set**|
|10340|**Web Page**|
|10341|**Web Page Access Control Rule**|
|10342|**Web Role**|
|10343|**Website**|
|10344|**Website Access**|
|10345|**Website Language**|
|10346|**Web Template**|
|10353|**Power Pages Scan Report**|
|10354|**Power Pages Log**|
|10359|**Catalog Submission Files**|
|10360|**Package Submission Store**|
|10531|**Form Mapping**|
|18085|**Event Expander Breadcrumb**|

### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|---|---|
|Description|**Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.**|
|DisplayName|**Modified On**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`modifiedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the delegate user who modified the record.**|
|DisplayName|**Modified By (Delegate)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_OrganizationId"></a> OrganizationId

|Property|Value|
|---|---|
|Description|**Unique identifier for the organization**|
|DisplayName|**Organization Id**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`organizationid`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|organization|

### <a name="BKMK_OverwriteTime"></a> OverwriteTime

|Property|Value|
|---|---|
|Description|**Date and time when the record was created.**|
|DisplayName|**Created On**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`overwritetime`|
|RequiredLevel|SystemRequired|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_SimilarityRuleIdUnique"></a> SimilarityRuleIdUnique

|Property|Value|
|---|---|
|Description|**Unique identifier of the Similarity Rule used when synchronizing customizations for the Microsoft Dynamics 365 client for Outlook**|
|DisplayName|**SimilarityRule**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`similarityruleidunique`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_SolutionId"></a> SolutionId

|Property|Value|
|---|---|
|Description|**Unique identifier of the associated solution.**|
|DisplayName|**Solution**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`solutionid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_SupportingSolutionId"></a> SupportingSolutionId

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Solution**|
|IsValidForForm|False|
|IsValidForRead|False|
|LogicalName|`supportingsolutionid`|
|RequiredLevel|None|
|Type|Uniqueidentifier|

### <a name="BKMK_VersionNumber"></a> VersionNumber

|Property|Value|
|---|---|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`versionnumber`|
|RequiredLevel|None|
|Type|BigInt|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|

## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

- [lk_similarityrule_createdonbehalfby](#BKMK_lk_similarityrule_createdonbehalfby)
- [lk_similarityrule_modifiedonbehalfby](#BKMK_lk_similarityrule_modifiedonbehalfby)
- [organization_similarityrule](#BKMK_organization_similarityrule)
- [TransactionCurrency_SimilarityRule](#BKMK_TransactionCurrency_SimilarityRule)

### <a name="BKMK_lk_similarityrule_createdonbehalfby"></a> lk_similarityrule_createdonbehalfby

One-To-Many Relationship: [systemuser lk_similarityrule_createdonbehalfby](systemuser.md#BKMK_lk_similarityrule_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_similarityrule_modifiedonbehalfby"></a> lk_similarityrule_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_similarityrule_modifiedonbehalfby](systemuser.md#BKMK_lk_similarityrule_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_organization_similarityrule"></a> organization_similarityrule

One-To-Many Relationship: [organization organization_similarityrule](organization.md#BKMK_organization_similarityrule)

|Property|Value|
|---|---|
|ReferencedEntity|`organization`|
|ReferencedAttribute|`organizationid`|
|ReferencingAttribute|`organizationid`|
|ReferencingEntityNavigationPropertyName|`organizationid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_TransactionCurrency_SimilarityRule"></a> TransactionCurrency_SimilarityRule

One-To-Many Relationship: [transactioncurrency TransactionCurrency_SimilarityRule](transactioncurrency.md#BKMK_TransactionCurrency_SimilarityRule)

|Property|Value|
|---|---|
|ReferencedEntity|`transactioncurrency`|
|ReferencedAttribute|`transactioncurrencyid`|
|ReferencingAttribute|`transactioncurrencyid`|
|ReferencingEntityNavigationPropertyName|`transactioncurrencyid`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `Restrict`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

### <a name="BKMK_similarityrule_AsyncOperations"></a> similarityrule_AsyncOperations

Many-To-One Relationship: [asyncoperation similarityrule_AsyncOperations](asyncoperation.md#BKMK_similarityrule_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`similarityrule_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   
<xref:Microsoft.Dynamics.CRM.similarityrule?displayProperty=fullName>