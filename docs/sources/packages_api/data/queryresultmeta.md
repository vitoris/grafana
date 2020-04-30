+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "QueryResultMeta"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
+++

## QueryResultMeta interface

<b>Signature</b>

```typescript
export interface QueryResultMeta 
```
<b>Import</b>

```typescript
import { QueryResultMeta } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [alignmentPeriod](#alignmentperiod-property) | <code>string</code> |  |
|  [custom](#custom-property) | <code>Record&lt;string, any&gt;</code> | DatasSource Specific Values |
|  [gmdMeta](#gmdmeta-property) | <code>any[]</code> | Legacy data source specific, should be moved to custom |
|  [json](#json-property) | <code>boolean</code> |  |
|  [limit](#limit-property) | <code>number</code> |  |
|  [notices](#notices-property) | <code>QueryResultMetaNotice[]</code> | Meta Notices |
|  [query](#query-property) | <code>string</code> |  |
|  [rawQuery](#rawquery-property) | <code>string</code> |  |
|  [searchWords](#searchwords-property) | <code>string[]</code> |  |
|  [stats](#stats-property) | <code>QueryResultMetaStat[]</code> | Stats |
|  [transformations](#transformations-property) | <code>string[]</code> | Used to track transformation ids that where part of the processing |

### alignmentPeriod property

<b>Signature</b>

```typescript
alignmentPeriod?: string;
```

### custom property

DatasSource Specific Values

<b>Signature</b>

```typescript
custom?: Record<string, any>;
```

### gmdMeta property

Legacy data source specific, should be moved to custom

<b>Signature</b>

```typescript
gmdMeta?: any[];
```

### json property

<b>Signature</b>

```typescript
json?: boolean;
```

### limit property

<b>Signature</b>

```typescript
limit?: number;
```

### notices property

Meta Notices

<b>Signature</b>

```typescript
notices?: QueryResultMetaNotice[];
```

### query property

<b>Signature</b>

```typescript
query?: string;
```

### rawQuery property

<b>Signature</b>

```typescript
rawQuery?: string;
```

### searchWords property

<b>Signature</b>

```typescript
searchWords?: string[];
```

### stats property

Stats

<b>Signature</b>

```typescript
stats?: QueryResultMetaStat[];
```

### transformations property

Used to track transformation ids that where part of the processing

<b>Signature</b>

```typescript
transformations?: string[];
```