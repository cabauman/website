title: SkipWhile
---
# Observable.SkipWhile Method

Bypasses values in an observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[SkipWhile<TSource>(IObservable<TSource>, Func<TSource, Boolean>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.skipwhile%60%601(system.iobservable%7b%60%600%7d%2csystem.func%7b%60%600%2csystem.boolean%7d)(v=VS.103))Bypasses values in an observable sequence as long as a specified condition is true and then returns the remaining values.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[SkipWhile<TSource>(IObservable<TSource>, Func<TSource, Int32, Boolean>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.skipwhile%60%601(system.iobservable%7b%60%600%7d%2csystem.func%7b%60%600%2csystem.int32%2csystem.boolean%7d)(v=VS.103))Bypasses values in an observable sequence as long as a specified condition is true and then returns the remaining values.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# SkipWhile\<TSource\>(IObservable\<TSource\>, Func\<TSource, Boolean\>)

Bypasses values in an observable sequence as long as a specified condition is true and then returns the remaining values.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function SkipWhile(Of TSource) ( _
    source As IObservable(Of TSource), _
    predicate As Func(Of TSource, Boolean) _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim predicate As Func(Of TSource, Boolean)
Dim returnValue As IObservable(Of TSource)

returnValue = source.SkipWhile(predicate)
```

```csharp
public static IObservable<TSource> SkipWhile<TSource>(
    this IObservable<TSource> source,
    Func<TSource, bool> predicate
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ SkipWhile(
    IObservable<TSource>^ source, 
    Func<TSource, bool>^ predicate
)
```

```fsharp
static member SkipWhile : 
        source:IObservable<'TSource> * 
        predicate:Func<'TSource, bool> -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  An observable sequence to return elements from.

- predicate  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, [Boolean](https://msdn.microsoft.com/en-us/library/a28wyd50)\>  
  A function to test each element for a condition.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
An observable sequence that contains the elements from the input sequence starting at the first element in the linear series that does not pass the test specified by predicate.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# SkipWhile\<TSource\>(IObservable\<TSource\>, Func\<TSource, Int32, Boolean\>)

Bypasses values in an observable sequence as long as a specified condition is true and then returns the remaining values.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function SkipWhile(Of TSource) ( _
    source As IObservable(Of TSource), _
    predicate As Func(Of TSource, Integer, Boolean) _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim predicate As Func(Of TSource, Integer, Boolean)
Dim returnValue As IObservable(Of TSource)

returnValue = source.SkipWhile(predicate)
```

```csharp
public static IObservable<TSource> SkipWhile<TSource>(
    this IObservable<TSource> source,
    Func<TSource, int, bool> predicate
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ SkipWhile(
    IObservable<TSource>^ source, 
    Func<TSource, int, bool>^ predicate
)
```

```fsharp
static member SkipWhile : 
        source:IObservable<'TSource> * 
        predicate:Func<'TSource, int, bool> -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  An observable sequence to return elements from.

- predicate  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb534647)\<TSource, [Int32](https://msdn.microsoft.com/en-us/library/td2s409d), [Boolean](https://msdn.microsoft.com/en-us/library/a28wyd50)\>  
  A function to test each element for a condition; the second parameter of the function represents the index of the source element.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
An observable sequence that contains the elements from the input sequence starting at the first element in the linear series that does not pass the test specified by predicate.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
