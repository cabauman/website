title: And
---
# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15\>.And\<T16\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T16) ( _
    other As IObservable(Of T16) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T16)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16> And<T16>(
    IObservable<T16> other
)
```

```c++
public:
generic<typename T16>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>^ And(
    IObservable<T16>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T16> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9, 'T10, 'T11, 'T12, 'T13, 'T14, 'T15, 'T16> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T16  
  The type of the sixteenth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T16\>  
  The sixteenth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), [T8](QueryablePattern/QueryablePattern(T1,), [T9](QueryablePattern/QueryablePattern(T1,), [T10](QueryablePattern/QueryablePattern(T1,), [T11](QueryablePattern/QueryablePattern(T1,), [T12](QueryablePattern/QueryablePattern(T1,), [T13](QueryablePattern/QueryablePattern(T1,), [T14](QueryablePattern/QueryablePattern(T1,), [T15](QueryablePattern/QueryablePattern(T1,), T16\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
