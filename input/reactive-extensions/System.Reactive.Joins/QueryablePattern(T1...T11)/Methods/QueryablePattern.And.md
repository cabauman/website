title: And
---
# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11\>.And\<T12\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T12) ( _
    other As IObservable(Of T12) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T12)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12> And<T12>(
    IObservable<T12> other
)
```

```c++
public:
generic<typename T12>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>^ And(
    IObservable<T12>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T12> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9, 'T10, 'T11, 'T12> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T12  
  The type of the twelfth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T12\>  
  The twelfth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), [T8](QueryablePattern/QueryablePattern(T1,), [T9](QueryablePattern/QueryablePattern(T1,), [T10](QueryablePattern/QueryablePattern(T1,), [T11](QueryablePattern/QueryablePattern(T1,), T12\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
