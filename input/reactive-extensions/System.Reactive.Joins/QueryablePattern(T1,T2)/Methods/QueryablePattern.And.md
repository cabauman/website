title: And
---
# QueryablePattern\<T1, T2\>.And\<T3\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T3) ( _
    other As IObservable(Of T3) _
) As QueryablePattern(Of T1, T2, T3)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T3)
Dim returnValue As QueryablePattern(Of T1, T2, T3)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3> And<T3>(
    IObservable<T3> other
)
```

```c++
public:
generic<typename T3>
QueryablePattern<T1, T2, T3>^ And(
    IObservable<T3>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T3> -> QueryablePattern<'T1, 'T2, 'T3> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T3  
  The type of the third observable sequence.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T3\>  
  The third observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), T3\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
