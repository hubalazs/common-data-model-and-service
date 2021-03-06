---
title: QuoteLineScheduleOfValue - Common Data Model | Microsoft Docs
description: List of billing milestones and invoice amounts for this quote line.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Quote Line Milestone

List of billing milestones and invoice amounts for this quote line.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/QuoteLineScheduleOfValue.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/QuoteLineScheduleOfValue  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[ownerId](#ownerId)|Owner Id|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[quoteLineScheduleOfValueId](#quoteLineScheduleOfValueId)|Unique identifier for entity instances|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[stateCode](#stateCode)|Status of the Quote Line Schedule Of Value|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[stateCode_display](#stateCode_display)||<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[statusCode](#statusCode)|Reason for the status of the Quote Line Schedule Of Value|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[statusCode_display](#statusCode_display)||<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[name](#name)|Type the name of the custom entity.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[amount](#amount)|Enter the value of the amount on the billing milestone.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[milestoneDate](#milestoneDate)|Enter the date on which the milestone is to be invoiced. This, in conjunction with the Invoice status, will be used by the invoice creation job.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[invoiceStatus](#invoiceStatus)|Select whether this milestone was invoiced. Valid values are Not ready for invoicing, Ready for Invoicing, On an invoice, and Invoiced.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[invoiceStatus_display](#invoiceStatus_display)||<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[isDataImport](#isDataImport)|Indicates if this record was created via import. It's purpose is to support data import.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[projectTask](#projectTask)|Select the project task that is tracking the work for this billing milestone.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[tax](#tax)||<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[taxBase](#taxBase)|Value of the tax in base currency.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[amountAfterTax](#amountAfterTax)||<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|
|[amountAfterTaxBase](#amountAfterTaxBase)|Value of the amount_after_tax in base currency.|<a href="QuoteLineScheduleOfValue.md" target="_blank">projectServiceAutomation/QuoteLineScheduleOfValue</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#quoteLineScheduleOfValueId name="quoteLineScheduleOfValueId">quoteLineScheduleOfValueId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Line Schedule Of Value</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_quotelinescheduleofvalueid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Quote Line Schedule Of Value  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Quote Line Schedule Of Value</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Quote Line Schedule Of Value  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Quote Line Schedule Of Value</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_name</td></tr></table>

### <a href=#amount name="amount">amount</a>

Enter the value of the amount on the billing milestone.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line Amount</td></tr><tr><td>description</td><td>Enter the value of the amount on the billing milestone.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount_base</td></tr></table>

### <a href=#milestoneDate name="milestoneDate">milestoneDate</a>

Enter the date on which the milestone is to be invoiced. This, in conjunction with the Invoice status, will be used by the invoice creation job.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Milestone Date</td></tr><tr><td>description</td><td>Enter the date on which the milestone is to be invoiced. This, in conjunction with the Invoice status, will be used by the invoice creation job.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoicedate</td></tr></table>

### <a href=#invoiceStatus name="invoiceStatus">invoiceStatus</a>

Select whether this milestone was invoiced. Valid values are Not ready for invoicing, Ready for Invoicing, On an invoice, and Invoiced.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Status</td></tr><tr><td>description</td><td>Select whether this milestone was invoiced. Valid values are Not ready for invoicing, Ready for Invoicing, On an invoice, and Invoiced.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoicestatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Not Ready for invoicing</td><td>192350000</td></tr><tr><td>en</td><td>Ready for invoicing</td><td>192350001</td></tr><tr><td>en</td><td>Customer invoice created</td><td>192350002</td></tr><tr><td>en</td><td>Customer invoice posted</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#invoiceStatus_display name="invoiceStatus_display">invoiceStatus_display</a>

First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isDataImport name="isDataImport">isDataImport</a>

Indicates if this record was created via import. It's purpose is to support data import.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>isdataimport</td></tr><tr><td>description</td><td>Indicates if this record was created via import. It's purpose is to support data import.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_isdataimport</td></tr></table>

### <a href=#projectTask name="projectTask">projectTask</a>

Select the project task that is tracking the work for this billing milestone.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Task</td></tr><tr><td>description</td><td>Select the project task that is tracking the work for this billing milestone.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_projecttask</td></tr></table>

### <a href=#tax name="tax">tax</a>

First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>tax</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_tax</td></tr></table>

### <a href=#taxBase name="taxBase">taxBase</a>

Value of the tax in base currency.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>tax (Base)</td></tr><tr><td>description</td><td>Value of the tax in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_tax_base</td></tr></table>

### <a href=#amountAfterTax name="amountAfterTax">amountAfterTax</a>

First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Milestone Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount_after_tax</td></tr></table>

### <a href=#amountAfterTaxBase name="amountAfterTaxBase">amountAfterTaxBase</a>

Value of the amount_after_tax in base currency.  
First included in: projectServiceAutomation/QuoteLineScheduleOfValue (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>amount_after_tax (Base)</td></tr><tr><td>description</td><td>Value of the amount_after_tax in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount_after_tax_base</td></tr></table>
