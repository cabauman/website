title: Single
---
# Observable.Single Method

Returns the only element of an observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Single<TSource>(IObservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.single%60%601(system.iobservable%7b%60%600%7d)(v=VS.103))Returns the only element of an observable sequence and throws an exception if there is not exactly one element in the observable sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Single<TSource>(IObservable<TSource>, Func<TSource, Boolean>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.single%60%601(system.iobservable%7b%60%600%7d%2csystem.func%7b%60%600%2csystem.boolean%7d)(v=VS.103))Returns the only element of an observable sequence that matches the predicate and throws an exception if there is not exactly one element in the observable sequence.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Single\<TSource\>(IObservable\<TSource\>, Func\<TSource, Boolean\>)

Returns the only element of an observable sequence that matches the predicate and throws an exception if there is not exactly one element in the observable sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Single(Of TSource) ( _
    source As IObservable(Of TSource), _
    predicate As Func(Of TSource, Boolean) _
) As TSource
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim predicate As Func(Of TSource, Boolean)
Dim returnValue As TSource

returnValue = source.Single(predicate)
```

```csharp
public static TSource Single<TSource>(
    this IObservable<TSource> source,
    Func<TSource, bool> predicate
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static TSource Single(
    IObservable<TSource>^ source, 
    Func<TSource, bool>^ predicate
)
```

```fsharp
static member Single : 
        source:IObservable<'TSource> * 
        predicate:Func<'TSource, bool> -> 'TSource 
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
  The source observable sequence.

- predicate  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, [Boolean](https://msdn.microsoft.com/en-us/library/a28wyd50)\>  
  A predicate function to evaluate for elements in the sequence.

#### Return Value

Type: TSource  
The single element in the observable sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Single\<TSource\>(IObservable\<TSource\>)

Returns the only element of an observable sequence and throws an exception if there is not exactly one element in the observable sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Single(Of TSource) ( _
    source As IObservable(Of TSource) _
) As TSource
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim returnValue As TSource

returnValue = source.Single()
```

```csharp
public static TSource Single<TSource>(
    this IObservable<TSource> source
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static TSource Single(
    IObservable<TSource>^ source
)
```

```fsharp
static member Single : 
        source:IObservable<'TSource> -> 'TSource 
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
  The source observable sequence.

#### Return Value

Type: TSource  
The single element in the observable sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
