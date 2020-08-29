title: And
---
# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7\>.And\<T8\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T8) ( _
    other As IObservable(Of T8) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T8)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8> And<T8>(
    IObservable<T8> other
)
```

```c++
public:
generic<typename T8>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8>^ And(
    IObservable<T8>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T8> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T8  
  The type of the eighth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T8\>  
  The eighth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), T8\>

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
