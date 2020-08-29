title: QueryablePattern<T1...T5>
---
# QueryablePattern\<T1, T2, T3, T4, T5\> Class

Represents a join queryable pattern.

## Inheritance Hierarchy

[System.Object](https://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern)  
    System.Reactive.Joins.QueryablePattern\<T1, T2, T3, T4, T5\>

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Class QueryablePattern(Of T1, T2, T3, T4, T5) _
    Inherits QueryablePattern
```

```vb
'Usage
Dim instance As QueryablePattern(Of T1, T2, T3, T4, T5)
```

```csharp
public class QueryablePattern<T1, T2, T3, T4, T5> : QueryablePattern
```

```c++
generic<typename T1, typename T2, typename T3, typename T4, typename T5>
public ref class QueryablePattern : public QueryablePattern
```

```fsharp
type QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5> =  
    class
        inherit QueryablePattern
    end
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T1  
  The type of the first component of the queryable pattern.

- T2  
  The type of the second component of the queryable pattern.

- T3  
  The type of the third component of the queryable pattern.

- T4  
  The type of the fourth component of the queryable pattern.

- T5  
  The type of the fifth component of the queryable pattern.

The QueryablePattern\<T1, T2, T3, T4, T5\> type exposes the following members.

## Properties

NameDescription![Public property](https://reactiveui.net/assets/img/Hh211972.pubproperty(en-us,VS.103).gif "Public property")[Expression](Expression/QueryablePattern.Expression)Gets the expression tree that is associated with the instance of queryable pattern. (Inherited from [QueryablePattern](QueryablePattern/QueryablePattern).)Top

## Methods

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[And<T6>](https://msdn.microsoft.com/en-us/library/m:system.reactive.joins.queryablepattern%605.and%60%601(system.iobservable%7b%60%600%7d)(v=VS.103))Matches when all observable sequences have an available value.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Equals](https://msdn.microsoft.com/en-us/library/m:system.object.equals(system.object)(v=VS.103))(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Protected method](https://reactiveui.net/assets/img/Hh303103.protmethod(en-us,VS.103).gif "Protected method")[Finalize](https://msdn.microsoft.com/en-us/library/4k87zsw7)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[GetHashCode](https://msdn.microsoft.com/en-us/library/zdee4b3y)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[GetType](https://msdn.microsoft.com/en-us/library/dfwy45w9)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Protected method](https://reactiveui.net/assets/img/Hh303103.protmethod(en-us,VS.103).gif "Protected method")[MemberwiseClone](https://msdn.microsoft.com/en-us/library/57ctke0a)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Then<TResult>](https://msdn.microsoft.com/en-us/library/m:system.reactive.joins.queryablepattern%605.then%60%601(system.linq.expressions.expression%7bsystem.func%7b%600%2c%601%2c%602%2c%603%2c%604%2c%60%600%7d%7d)(v=VS.103))Matches when all observable sequences have an available value and projects the values.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[ToString](https://msdn.microsoft.com/en-us/library/7bxwbwt2)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)Top

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
