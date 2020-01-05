# SearchAThing.PsqlUtil.Util.ToPsql method
## ToPsql(bool)
retrieve psql representation of boolean
            "TRUE" or "FALSE" string

### Signature
```csharp
public static string ToPsql(bool value)
```
### Returns

### Remarks


<p>&nbsp;</p>
<p>&nbsp;</p>
<hr/>

## ToPsql(Nullable<bool>)
retrieve psql representation of boolean
            "TRUE" or "FALSE" string
            or "null" string if given argument is null

### Signature
```csharp
public static string ToPsql(Nullable<bool> value)
```
### Returns

### Remarks


<p>&nbsp;</p>
<p>&nbsp;</p>
<hr/>

## ToPsql(int)
retrieve psql representation of integer
            (number without quotes)

### Signature
```csharp
public static string ToPsql(int value)
```
### Returns

### Remarks


<p>&nbsp;</p>
<p>&nbsp;</p>
<hr/>

## ToPsql(Nullable<int>)
retrieve psql representation of integer
            (number without quotes)
            of "null" string if given argument is null

### Signature
```csharp
public static string ToPsql(Nullable<int> value)
```
### Returns

### Remarks


<p>&nbsp;</p>
<p>&nbsp;</p>
<hr/>

## ToPsql(string)
retrieve psql repsentation of string
            'string' enquoted and escaped
            or "null" stringif given argument is null

### Signature
```csharp
public static string ToPsql(string str)
```
### Returns

### Remarks


<p>&nbsp;</p>
<p>&nbsp;</p>
<hr/>

## ToPsql(DateTime)
retrieve psql representation of datetime
            'YYYY-MM-DD hh:mm:ss.millis'

### Signature
```csharp
public static string ToPsql(DateTime dt)
```
### Returns

### Remarks


<p>&nbsp;</p>
<p>&nbsp;</p>
<hr/>

## ToPsql(Nullable<System.DateTime>)
retrieve psql representation of datetime
            'YYYY-MM-DD hh:mm:ss.millis'
            or "null" string if given argument is null

### Signature
```csharp
public static string ToPsql(Nullable<System.DateTime> dt)
```
### Returns

### Remarks


<p>&nbsp;</p>
<p>&nbsp;</p>
<hr/>

## ToPsql(double)
retrieve psql representation of double
            (number without quotes)

### Signature
```csharp
public static string ToPsql(double value)
```
### Returns

### Remarks


<p>&nbsp;</p>
<p>&nbsp;</p>
<hr/>

## ToPsql(Nullable<double>)
retrieve psql representation of double
            (number without quotes)
            of "null" string if given argument is null

### Signature
```csharp
public static string ToPsql(Nullable<double> value)
```
### Returns

### Remarks


<p>&nbsp;</p>
<p>&nbsp;</p>
<hr/>

## ToPsql(IEnumerable<double>)
retrieve psql representation of double array
            '{val1,val2,...,valn}'
            list enquoted, using invariant culture
            return "null" string if entire array is a null

### Signature
```csharp
public static string ToPsql(IEnumerable<double> ary)
```
### Returns

### Remarks


<p>&nbsp;</p>
<p>&nbsp;</p>
<hr/>

## ToPsql(IEnumerable<System.Nullable<double>>)
retrieve psql representation of nullable double array
            '{val1,val2,null,...,valn}'
            list enquoted, using invariant culture and evaluating null to "null" strings

### Signature
```csharp
public static string ToPsql(IEnumerable<System.Nullable<double>> ary)
```
### Returns

### Remarks

