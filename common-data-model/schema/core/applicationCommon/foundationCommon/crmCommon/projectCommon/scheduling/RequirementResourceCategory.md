---
title: RequirementResourceCategory - Common Data Model | Microsoft Docs
description: Requirement Resource Category
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Requirement Resource Category

Requirement Resource Category  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/scheduling/RequirementResourceCategory.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/scheduling/RequirementResourceCategory  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[ownerId](#ownerId)|Owner Id|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[requirementResourceCategoryId](#requirementResourceCategoryId)|A unique identifier for an entity instance.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[stateCode](#stateCode)|Status of the Requirement Resource Category|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[stateCode_display](#stateCode_display)||<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[statusCode](#statusCode)|Reason for the status of the Requirement Resource Category|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[statusCode_display](#statusCode_display)||<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[name](#name)|The name of the custom entity.|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[resourceCategory](#resourceCategory)|Resource Category|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[resourceRequirement](#resourceRequirement)|Resource Requirement|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|
|[isPrimary](#isPrimary)|Yes if resource category requirement is primary. If it's primary then it can't be deleted|<a href="RequirementResourceCategory.md" target="_blank">scheduling/RequirementResourceCategory</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#requirementResourceCategoryId name="requirementResourceCategoryId">requirementResourceCategoryId</a>

A unique identifier for an entity instance.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirement Resource Category</td></tr><tr><td>description</td><td>A unique identifier for an entity instance.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_requirementresourcecategoryid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Requirement Resource Category  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Requirement Resource Category</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Requirement Resource Category  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Requirement Resource Category</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

Resource Category  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Category</td></tr><tr><td>description</td><td>Resource Category</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategory</td></tr></table>

### <a href=#resourceRequirement name="resourceRequirement">resourceRequirement</a>

Resource Requirement  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource Requirement</td></tr><tr><td>description</td><td>Resource Requirement</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcerequirement</td></tr></table>

### <a href=#isPrimary name="isPrimary">isPrimary</a>

Yes if resource category requirement is primary. If it's primary then it can't be deleted  
First included in: scheduling/RequirementResourceCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Primary</td></tr><tr><td>description</td><td>Yes if resource category requirement is primary. If it's primary then it can't be deleted</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_isprimary</td></tr></table>
