title: And
---
# Pattern\<T1, T2\>.And\<T3\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T3) ( _
    other As IObservable(Of T3) _
) As Pattern(Of T1, T2, T3)
```

```vb
'Usage
Dim instance As Pattern
Dim other As IObservable(Of T3)
Dim returnValue As Pattern(Of T1, T2, T3)

returnValue = instance.And(other)
```

```csharp
public Pattern<T1, T2, T3> And<T3>(
    IObservable<T3> other
)
```

```c++
public:
generic<typename T3>
Pattern<T1, T2, T3>^ And(
    IObservable<T3>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T3> -> Pattern<'T1, 'T2, 'T3> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T3  
  The type of the third component of the pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T3\>  
  The third observable sequence.

#### Return Value

Type: [System.Reactive.Joins.Pattern](Pattern/Pattern(T1,)\<[T1](Pattern/Pattern(T1,), [T2](Pattern/Pattern(T1,), T3\>  
The join pattern.

## See Also

#### Reference

[Pattern\<T1, T2\> Class](Pattern/Pattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
