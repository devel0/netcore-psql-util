# Util Class
**Namespace:** SearchAThing.PsqlUtil

**Inheritance:** Object → Util

(No Description)

## Signature
```csharp
public static class Util
```
## Methods
|**Name**|**Summary**|
|---|---|
|[EnableFirstLastAggregateFunctions](Util/EnableFirstLastAggregateFunctions.md) (static)|add first and last aggregate functions<br/>            https://wiki.postgresql.org/wiki/First/last_(aggregate)|
|[Equals](Util/Equals.md)||
|[GetHashCode](Util/GetHashCode.md)||
|[GetType](Util/GetType.md)||
|[IsPsqlNull](Util/IsPsqlNull.md) (static)|states if given object is null or DBNull|
|[ToPsql](Util/ToPsql.md) (static)|retrieve psql representation of boolean<br/>            "TRUE" or "FALSE" string|
|[ToPsql](Util/ToPsql.md#topsqlnullablebool) (static)|retrieve psql representation of boolean<br/>            "TRUE" or "FALSE" string<br/>            or "null" string if given argument is null|
|[ToPsql](Util/ToPsql.md#topsqlint) (static)|retrieve psql representation of integer<br/>            (number without quotes)|
|[ToPsql](Util/ToPsql.md#topsqlnullableint) (static)|retrieve psql representation of integer<br/>            (number without quotes)<br/>            of "null" string if given argument is null|
|[ToPsql](Util/ToPsql.md#topsqlstring) (static)|retrieve psql repsentation of string<br/>            'string' enquoted and escaped<br/>            or "null" stringif given argument is null|
|[ToPsql](Util/ToPsql.md#topsqldatetime) (static)|retrieve psql representation of datetime<br/>            'YYYY-MM-DD hh:mm:ss.millis'|
|[ToPsql](Util/ToPsql.md#topsqlnullablesystemdatetime) (static)|retrieve psql representation of datetime<br/>            'YYYY-MM-DD hh:mm:ss.millis'<br/>            or "null" string if given argument is null|
|[ToPsql](Util/ToPsql.md#topsqldouble) (static)|retrieve psql representation of double<br/>            (number without quotes)|
|[ToPsql](Util/ToPsql.md#topsqlnullabledouble) (static)|retrieve psql representation of double<br/>            (number without quotes)<br/>            of "null" string if given argument is null|
|[ToPsql](Util/ToPsql.md#topsqlienumerabledouble) (static)|retrieve psql representation of double array<br/>            '{val1,val2,...,valn}'<br/>            list enquoted, using invariant culture<br/>            return "null" string if entire array is a null|
|[ToPsql](Util/ToPsql.md#topsqlienumerablesystemnullabledouble) (static)|retrieve psql representation of nullable double array<br/>            '{val1,val2,null,...,valn}'<br/>            list enquoted, using invariant culture and evaluating null to "null" strings|
|[ToString](Util/ToString.md)||
## Conversions
