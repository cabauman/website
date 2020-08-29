title: Constructors
---
# QueryablePattern Constructor

Initializes a new instance of the [QueryablePattern](QueryablePattern/QueryablePattern) class.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Protected Sub New ( _
    expression As Expression _
)
```

```vb
'Usage
Dim expression As Expression

Dim instance As New QueryablePattern(expression)
```

```csharp
protected QueryablePattern(
    Expression expression
)
```

```c++
protected:
QueryablePattern(
    Expression^ expression
)
```

```fsharp
new : 
        expression:Expression -> QueryablePattern
```

```jscript
protected function QueryablePattern(
    expression : Expression
)
```

#### Parameters

- expression  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb356138)  
  The expression type of the queryable pattern.

## See Also

#### Reference

[QueryablePattern Class](QueryablePattern/QueryablePattern)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
