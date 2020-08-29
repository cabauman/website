title: And
---
# Pattern\<T1, T2, T3, T4, T5, T6, T7, T8\>.And\<T9\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T9) ( _
    other As IObservable(Of T9) _
) As Pattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9)
```

```vb
'Usage
Dim instance As Pattern
Dim other As IObservable(Of T9)
Dim returnValue As Pattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9)

returnValue = instance.And(other)
```

```csharp
public Pattern<T1, T2, T3, T4, T5, T6, T7, T8, T9> And<T9>(
    IObservable<T9> other
)
```

```c++
public:
generic<typename T9>
Pattern<T1, T2, T3, T4, T5, T6, T7, T8, T9>^ And(
    IObservable<T9>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T9> -> Pattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T9  
  The type of the ninth component of the pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T9\>  
  The ninth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.Pattern](Pattern/Pattern(T1,)\<[T1](Pattern/Pattern(T1,), [T2](Pattern/Pattern(T1,), [T3](Pattern/Pattern(T1,), [T4](Pattern/Pattern(T1,), [T5](Pattern/Pattern(T1,), [T6](Pattern/Pattern(T1,), [T7](Pattern/Pattern(T1,), [T8](Pattern/Pattern(T1,), T9\>  
The join pattern.

## See Also

#### Reference

[Pattern\<T1, T2, T3, T4, T5, T6, T7, T8\> Class](Pattern/Pattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
