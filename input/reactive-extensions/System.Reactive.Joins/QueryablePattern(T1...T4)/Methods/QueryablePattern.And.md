title: And
---
# QueryablePattern\<T1, T2, T3, T4\>.And\<T5\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T5) ( _
    other As IObservable(Of T5) _
) As QueryablePattern(Of T1, T2, T3, T4, T5)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T5)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5> And<T5>(
    IObservable<T5> other
)
```

```c++
public:
generic<typename T5>
QueryablePattern<T1, T2, T3, T4, T5>^ And(
    IObservable<T5>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T5> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T5  
  The type of the fifth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T5\>  
  The fifth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), T5\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
