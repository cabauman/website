title: And
---
# Pattern\<T1, T2, T3, T4, T5\>.And\<T6\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T6) ( _
    other As IObservable(Of T6) _
) As Pattern(Of T1, T2, T3, T4, T5, T6)
```

```vb
'Usage
Dim instance As Pattern
Dim other As IObservable(Of T6)
Dim returnValue As Pattern(Of T1, T2, T3, T4, T5, T6)

returnValue = instance.And(other)
```

```csharp
public Pattern<T1, T2, T3, T4, T5, T6> And<T6>(
    IObservable<T6> other
)
```

```c++
public:
generic<typename T6>
Pattern<T1, T2, T3, T4, T5, T6>^ And(
    IObservable<T6>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T6> -> Pattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T6  
  The type of the sixth component of the pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T6\>  
  The sixth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.Pattern](Pattern/Pattern(T1,)\<[T1](Pattern/Pattern(T1,), [T2](Pattern/Pattern(T1,), [T3](Pattern/Pattern(T1,), [T4](Pattern/Pattern(T1,), [T5](Pattern/Pattern(T1,), T6\>  
The join pattern.

## See Also

#### Reference

[Pattern\<T1, T2, T3, T4, T5\> Class](Pattern/Pattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
