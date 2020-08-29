title: And
---
# Pattern\<T1, T2, T3, T4, T5, T6, T7\>.And\<T8\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T8) ( _
    other As IObservable(Of T8) _
) As Pattern(Of T1, T2, T3, T4, T5, T6, T7, T8)
```

```vb
'Usage
Dim instance As Pattern
Dim other As IObservable(Of T8)
Dim returnValue As Pattern(Of T1, T2, T3, T4, T5, T6, T7, T8)

returnValue = instance.And(other)
```

```csharp
public Pattern<T1, T2, T3, T4, T5, T6, T7, T8> And<T8>(
    IObservable<T8> other
)
```

```c++
public:
generic<typename T8>
Pattern<T1, T2, T3, T4, T5, T6, T7, T8>^ And(
    IObservable<T8>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T8> -> Pattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T8  
  The type of the eighth component of the pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T8\>  
  The eighth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.Pattern](Pattern/Pattern(T1,)\<[T1](Pattern/Pattern(T1,), [T2](Pattern/Pattern(T1,), [T3](Pattern/Pattern(T1,), [T4](Pattern/Pattern(T1,), [T5](Pattern/Pattern(T1,), [T6](Pattern/Pattern(T1,), [T7](Pattern/Pattern(T1,), T8\>  
The join pattern.

## See Also

#### Reference

[Pattern\<T1, T2, T3, T4, T5, T6, T7\> Class](Pattern/Pattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
