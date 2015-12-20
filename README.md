# CRM-Google-Map

## Overview
CRM Google Maps integration displays fully-functional maps, so you'll have Google location information and directions to your contacts or 
accounts right inside Dynamic CRM. Using a simple configuration in Dynamic CRM, An administrator can add the Google Maps integration 
in a matter of minutes to any CRM module containing an address field-even custom modules.

## Install steps
1.Import managed solution in CRM
2.Create section in form as a web resource 
3.Bind address part fields from your entity as additional parameters as shown bellow - 
format is yourCaption1=new_field1&yourCaption2=new_field2
new_field1, new_field2, ... ,new_fieldN are entity fields containing address parts such as address line 1, city, region, country etc. 
Lookup fields are supported also. 

