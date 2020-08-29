title: PublishLast
---
# Observable.PublishLast Method

Returns a connectable observable sequence that shares a single subscription that contains the last notification only.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[PublishLast<TSource>(IObservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.publishlast%60%601(system.iobservable%7b%60%600%7d)(v=VS.103))Returns a connectable observable sequence that shares a single subscription to the underlying sequence containing only the last notification.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[PublishLast<TSource, TResult>(IObservable<TSource>, Func<IObservable<TSource>, IObservable<TResult>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.publishlast%60%602(system.iobservable%7b%60%600%7d%2csystem.func%7bsystem.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%7d)(v=VS.103))Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence containing only the last notification.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# PublishLast\<TSource\>(IObservable\<TSource\>)

Returns a connectable observable sequence that shares a single subscription to the underlying sequence containing only the last notification.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function PublishLast(Of TSource) ( _
    source As IObservable(Of TSource) _
) As IConnectableObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim returnValue As IConnectableObservable(Of TSource)

returnValue = source.PublishLast()
```

```csharp
public static IConnectableObservable<TSource> PublishLast<TSource>(
    this IObservable<TSource> source
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IConnectableObservable<TSource>^ PublishLast(
    IObservable<TSource>^ source
)
```

```fsharp
static member PublishLast : 
        source:IObservable<'TSource> -> IConnectableObservable<'TSource> 
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
  The source sequence whose elements will be multicasted through a single shared subscription.

#### Return Value

Type: [System.Reactive.Subjects.IConnectableObservable](IConnectableObservable/IConnectableObservable(T))\<TSource\>  
A connectable observable sequence that shares a single subscription to the underlying sequence containing only the last notification.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# PublishLast\<TSource, TResult\>(IObservable\<TSource\>, Func\<IObservable\<TSource\>, IObservable\<TResult\>\>)

Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence containing only the last notification.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function PublishLast(Of TSource, TResult) ( _
    source As IObservable(Of TSource), _
    selector As Func(Of IObservable(Of TSource), IObservable(Of TResult)) _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim selector As Func(Of IObservable(Of TSource), IObservable(Of TResult))
Dim returnValue As IObservable(Of TResult)

returnValue = source.PublishLast(selector)
```

```csharp
public static IObservable<TResult> PublishLast<TSource, TResult>(
    this IObservable<TSource> source,
    Func<IObservable<TSource>, IObservable<TResult>> selector
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TResult>
static IObservable<TResult>^ PublishLast(
    IObservable<TSource>^ source, 
    Func<IObservable<TSource>^, IObservable<TResult>^>^ selector
)
```

```fsharp
static member PublishLast : 
        source:IObservable<'TSource> * 
        selector:Func<IObservable<'TSource>, IObservable<'TResult>> -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TResult  
  The type of result.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

- selector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>, [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>\>  
  The selector function which can use the multicasted source sequence as many times as needed, without causing multiple subscriptions to the source sequence.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that contains the elements of a sequence produced by multicasting the source sequence within a selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
