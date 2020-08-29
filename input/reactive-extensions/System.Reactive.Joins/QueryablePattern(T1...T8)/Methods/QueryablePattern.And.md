title: And
---
# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8\>.And\<T9\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T9) ( _
    other As IObservable(Of T9) _
) As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim other As IObservable(Of T9)
Dim returnValue As QueryablePattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9)

returnValue = instance.And(other)
```

```csharp
public QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9> And<T9>(
    IObservable<T9> other
)
```

```c++
public:
generic<typename T9>
QueryablePattern<T1, T2, T3, T4, T5, T6, T7, T8, T9>^ And(
    IObservable<T9>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T9> -> QueryablePattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T9  
  The type of the ninth component of the queryable pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T9\>  
  The ninth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.QueryablePattern](QueryablePattern/QueryablePattern(T1,)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), [T8](QueryablePattern/QueryablePattern(T1,), T9\>  
The join queryable pattern.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
