title: And
---
# Pattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14\>.And\<T15\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T15) ( _
    other As IObservable(Of T15) _
) As Pattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15)
```

```vb
'Usage
Dim instance As Pattern
Dim other As IObservable(Of T15)
Dim returnValue As Pattern(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15)

returnValue = instance.And(other)
```

```csharp
public Pattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15> And<T15>(
    IObservable<T15> other
)
```

```c++
public:
generic<typename T15>
Pattern<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>^ And(
    IObservable<T15>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T15> -> Pattern<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9, 'T10, 'T11, 'T12, 'T13, 'T14, 'T15> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T15  
  The type of the fifteenth component of the pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T15\>  
  The fifteenth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.Pattern](Pattern/Pattern(T1,)\<[T1](Pattern/Pattern(T1,), [T2](Pattern/Pattern(T1,), [T3](Pattern/Pattern(T1,), [T4](Pattern/Pattern(T1,), [T5](Pattern/Pattern(T1,), [T6](Pattern/Pattern(T1,), [T7](Pattern/Pattern(T1,), [T8](Pattern/Pattern(T1,), [T9](Pattern/Pattern(T1,), [T10](Pattern/Pattern(T1,), [T11](Pattern/Pattern(T1,), [T12](Pattern/Pattern(T1,), [T13](Pattern/Pattern(T1,), [T14](Pattern/Pattern(T1,), T15\>  
The join pattern.

## See Also

#### Reference

[Pattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14\> Class](Pattern/Pattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
