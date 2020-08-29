title: And
---
# QueryablePattern\<T1, T2, T3, T4, T5, T6\>.And\<T7\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T7) ( _
    other As IObservable(Of T7) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T7)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7> And<T7>(
    IObservable<T7> other
)
```

```c++
public:
generic<typename T7>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7>^ And(
    IObservable<T7>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T7> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T7  
  The type of the seventh component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T7\>  
  The seventh observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), T7\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
