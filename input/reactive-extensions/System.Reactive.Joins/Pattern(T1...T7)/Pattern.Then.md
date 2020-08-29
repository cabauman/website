title: Then
---
# Pattern\<T1, T2, T3, T4, T5, T6, T7\>.Then\<TResult\> Method

Matches when all observable sequences have an available value and projects the values.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Function Then(Of TResult) ( _
    selector As Func(Of T1, T2, T3, T4, T5, T6, T7, TResult) _
) As Plan(Of TResult)
```

```vb
'Usage
Dim instance As Pattern
Dim selector As Func(Of T1, T2, T3, T4, T5, T6, T7, TResult)
Dim returnValue As Plan(Of TResult)

returnValue = instance.Then(selector)
```

```csharp
public Plan<TResult> Then<TResult>(
    Func<T1, T2, T3, T4, T5, T6, T7, TResult> selector
)
```

```c++
public:
generic<typename TResult>
Plan<TResult>^ Then(
    Func<T1, T2, T3, T4, T5, T6, T7, TResult>^ selector
)
```

```fsharp
member Then : 
        selector:Func<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'TResult> -> Plan<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The type of the return value of the selector function.

#### Parameters

- selector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Dd289456)\<[T1](Pattern/Pattern(T1,), [T2](Pattern/Pattern(T1,), [T3](Pattern/Pattern(T1,), [T4](Pattern/Pattern(T1,), [T5](Pattern/Pattern(T1,), [T6](Pattern/Pattern(T1,), [T7](Pattern/Pattern(T1,), TResult\>  
  The function that projects the result to the next observer.

#### Return Value

Type: [System.Reactive.Joins.Plan](Plan/Plan(TResult))\<TResult\>  
The execution plan for join patterns.

## See Also

#### Reference

[Pattern\<T1, T2, T3, T4, T5, T6, T7\> Class](Pattern/Pattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
