+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "TemplateSrv"
keywords = ["grafana","documentation","sdk","@grafana/runtime"]
type = "docs"
+++

## TemplateSrv interface

Via the TemplateSrv consumers get access to all the available template variables that can be used within the current active dashboard.

For a more in-depth description visit: https://grafana.com/docs/grafana/latest/variables/templates-and-variables

<b>Signature</b>

```typescript
export interface TemplateSrv 
```
<b>Import</b>

```typescript
import { TemplateSrv } from '@grafana/runtime';
```
<b>Methods</b>

|  Method | Description |
|  --- | --- |
|  [getVariables()](#getvariables-method) |  |

### getVariables method

<b>Signature</b>

```typescript
getVariables(): VariableModel[];
```
<b>Returns:</b>

`VariableModel[]`
