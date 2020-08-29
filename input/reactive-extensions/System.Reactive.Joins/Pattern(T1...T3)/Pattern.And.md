title: And
---
# Pattern\<T1, T2, T3\>.And\<T4\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T4) ( _
    other As IObservable(Of T4) _
) As Pattern(Of T1, T2, T3, T4)
```

```vb
'Usage
Dim instance As Pattern
Dim other As IObservable(Of T4)
Dim returnValue As Pattern(Of T1, T2, T3, T4)

returnValue = instance.And(other)
```

```csharp
public Pattern<T1, T2, T3, T4> And<T4>(
    IObservable<T4> other
)
```

```c++
public:
generic<typename T4>
Pattern<T1, T2, T3, T4>^ And(
    IObservable<T4>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T4> -> Pattern<'T1, 'T2, 'T3, 'T4> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T4  
  The type of the fourth component of the pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T4\>  
  The fourth observable sequence.

#### Return Value

Type: [System.Reactive.Joins.Pattern](Pattern/Pattern(T1,)\<[T1](Pattern/Pattern(T1,), [T2](Pattern/Pattern(T1,), [T3](Pattern/Pattern(T1,), T4\>  
The join pattern.

## See Also

#### Reference

[Pattern\<T1, T2, T3\> Class](Pattern/Pattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
