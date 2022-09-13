# R2


## Description

Breaking down what R2 Actually is.

## Overview

R2 is VAIF'S new and improved redacted; revamped system. This system has been fully upgraded and updated including all API(s) to support the release of our new applications. This is a faster, smoother, and more secure system with 10x the processing power as before. This system was specifically designed to improve productivity and overall system performance. 


## Author

Michael Griffin, CEO

## Macros used

There are no macros links in this template.

## Template links

There are no template links in this template.

## Discovery rules

|Name|Description|Type|Key and additional info|
|----|-----------|----|----|
|Covid19 - Selected Countries|<p>-</p>|`External check`|covid19_affectedcountries.py<p>Update: 1h</p>|


## Items collected

|Name|Description|Type|Key and additional info|
|----|-----------|----|----|
|Covid19 - Total of Active Cases|<p>-</p>|`Dependent item`|covid19.data[ActiveCases]<p>Update: 0</p>|
|Covid19 - Total of New Cases|<p>-</p>|`Dependent item`|covid19.data[NewCases]<p>Update: 0</p>|
|Covid19 - Total Recovered|<p>-</p>|`Dependent item`|covid19.data[TotalRecovered]<p>Update: 0</p>|
|Covid19 Full Info|<p>-</p>|`External check`|covid19_status.py<p>Update: 60m</p>|
|Covid19 - Total  Cases per 1M habitants|<p>-</p>|`Dependent item`|covid19.data[CasesperMillion]<p>Update: 0</p>|
|Covid19 - Total of New Deaths|<p>-</p>|`Dependent item`|covid19.data[NewDeaths]<p>Update: 0</p>|
|Covid19 - Total Cases|<p>-</p>|`Dependent item`|covid19.data[TotalCases]<p>Update: 0</p>|
|Covid19 - Total of Serious,Critical Cases|<p>-</p>|`Dependent item`|covid19.data[Serious]<p>Update: 0</p>|
|Covid19 - Total of Deaths|<p>-</p>|`Dependent item`|covid19.data[TotalDeaths]<p>Update: 0</p>|
|[ {#COUNTRY_NAME} | {#COUNTRY_IBAN} ] - TotalCases|<p>-</p>|`Calculated`|covid19.data["{#COUNTRY_NAME}", TotalCases]<p>Update: 30m</p><p>LLD</p>|
|[ {#COUNTRY_NAME} | {#COUNTRY_IBAN} ] - ActiveCases|<p>-</p>|`Dependent item`|covid19.data["{#COUNTRY_NAME}", ActiveCases]<p>Update: 0</p><p>LLD</p>|
|[ {#COUNTRY_NAME} | {#COUNTRY_IBAN} ] - Cases per Million habitants|<p>-</p>|`Dependent item`|covid19.data["{#COUNTRY_NAME}", CasesperMillion]<p>Update: 0</p><p>LLD</p>|
|[ {#COUNTRY_NAME} | {#COUNTRY_IBAN} ] - NewCases|<p>-</p>|`Dependent item`|covid19.data[ "{#COUNTRY_NAME}", NewCases]<p>Update: 0</p><p>LLD</p>|
|[ {#COUNTRY_NAME} | {#COUNTRY_IBAN} ] - NewDeaths|<p>-</p>|`Dependent item`|covid19.data["{#COUNTRY_NAME}", NewDeaths]<p>Update: 0</p><p>LLD</p>|
|[ {#COUNTRY_NAME} | {#COUNTRY_IBAN} ] - Serious,Critical|<p>-</p>|`Dependent item`|covid19.data["{#COUNTRY_NAME}", Serious]<p>Update: 0</p><p>LLD</p>|
|[ {#COUNTRY_NAME} | {#COUNTRY_IBAN} ] - TotalDeaths|<p>-</p>|`Dependent item`|covid19.data["{#COUNTRY_NAME}", TotalDeaths]<p>Update: 0</p><p>LLD</p>|
|[ {#COUNTRY_NAME} | {#COUNTRY_IBAN} ] - TotalRecovered|<p>-</p>|`Dependent item`|covid19.data["{#COUNTRY_NAME}", TotalRecovered]<p>Update: 0</p><p>LLD</p>|


## Triggers

There are no triggers in this template.

