title: Then
---
# QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9\>.Then\<TResult\> Method

Matches when all observable sequences have an available value and projects the values.

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
Public Function Then(Of TResult) ( _
    selector As Expression(Of Func(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, TResult)) _
) As QueryablePlan(Of TResult)
```

```vb
'Usage
Dim instance As QueryablePattern
Dim selector As Expression(Of Func(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, TResult))
Dim returnValue As QueryablePlan(Of TResult)

returnValue = instance.Then(selector)
```

```csharp
public QueryablePlan<TResult> Then<TResult>(
    Expression<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, TResult>> selector
)
```

```c++
public:
generic<typename TResult>
QueryablePlan<TResult>^ Then(
    Expression<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, TResult>^>^ selector
)
```

```fsharp
member Then : 
        selector:Expression<Func<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9, 'TResult>> -> QueryablePlan<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The type of the return value of the selector function.

#### Parameters

- selector  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Dd386894)\<[T1](QueryablePattern/QueryablePattern(T1,), [T2](QueryablePattern/QueryablePattern(T1,), [T3](QueryablePattern/QueryablePattern(T1,), [T4](QueryablePattern/QueryablePattern(T1,), [T5](QueryablePattern/QueryablePattern(T1,), [T6](QueryablePattern/QueryablePattern(T1,), [T7](QueryablePattern/QueryablePattern(T1,), [T8](QueryablePattern/QueryablePattern(T1,), [T9](QueryablePattern/QueryablePattern(T1,), TResult\>\>  
  The function that projects the result to the next observer.

#### Return Value

Type: [System.Reactive.Joins.QueryablePlan](QueryablePlan/QueryablePlan(TResult))\<TResult\>  
The execution plan for join patterns.

## See Also

#### Reference

[QueryablePattern\<T1, T2, T3, T4, T5, T6, T7, T8, T9\> Class](QueryablePattern/QueryablePattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
