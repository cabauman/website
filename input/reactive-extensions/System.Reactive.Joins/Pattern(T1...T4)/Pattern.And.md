title: And
---
# Pattern\<T1, T2, T3, T4\>.And\<T5\> Method

Matches when all observable sequences have an available value.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Function And(Of T5) ( _
    other As IObservable(Of T5) _
) As Pattern(Of T1, T2, T3, T4, T5)
```

```vb
'Usage
Dim instance As Pattern
Dim other As IObservable(Of T5)
Dim returnValue As Pattern(Of T1, T2, T3, T4, T5)

returnValue = instance.And(other)
```

```csharp
public Pattern<T1, T2, T3, T4, T5> And<T5>(
    IObservable<T5> other
)
```

```c++
public:
generic<typename T5>
Pattern<T1, T2, T3, T4, T5>^ And(
    IObservable<T5>^ other
)
```

```fsharp
member And : 
        other:IObservable<'T5> -> Pattern<'T1, 'T2, 'T3, 'T4, 'T5> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T5  
  The type of the fifth component of the pattern.

#### Parameters

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T5\>  
  The fifth component of the pattern.

#### Return Value

Type: [System.Reactive.Joins.Pattern](Pattern/Pattern(T1,)\<[T1](Pattern/Pattern(T1,), [T2](Pattern/Pattern(T1,), [T3](Pattern/Pattern(T1,), [T4](Pattern/Pattern(T1,), T5\>  
The join pattern.

## See Also

#### Reference

[Pattern\<T1, T2, T3, T4\> Class](Pattern/Pattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
