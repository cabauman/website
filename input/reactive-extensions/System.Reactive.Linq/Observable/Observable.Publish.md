title: Publish
---
# Observable.Publish Method

Returns a connectable observable sequence that shares a single subscription.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Publish<TSource>(IObservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.publish%60%601(system.iobservable%7b%60%600%7d)(v=VS.103))Returns a connectable observable sequence that shares a single subscription to the underlying sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Publish<TSource, TResult>(IObservable<TSource>, Func<IObservable<TSource>, IObservable<TResult>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.publish%60%602(system.iobservable%7b%60%600%7d%2csystem.func%7bsystem.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%7d)(v=VS.103))Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Publish<TSource>(IObservable<TSource>, TSource)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.publish%60%601(system.iobservable%7b%60%600%7d%2c%60%600)(v=VS.103))Returns a connectable observable sequence that shares a single subscription to the underlying sequence and starts with initialValue.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Publish<TSource, TResult>(IObservable<TSource>, Func<IObservable<TSource>, IObservable<TResult>>, TSource)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.publish%60%602(system.iobservable%7b%60%600%7d%2csystem.func%7bsystem.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%7d%2c%60%600)(v=VS.103))Returns a connectable observable sequence that shares a single subscription to the underlying sequence and starts with initialValue.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Publish\<TSource\>(IObservable\<TSource\>)

Returns a connectable observable sequence that shares a single subscription to the underlying sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Publish(Of TSource) ( _
    source As IObservable(Of TSource) _
) As IConnectableObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim returnValue As IConnectableObservable(Of TSource)

returnValue = source.Publish()
```

```csharp
public static IConnectableObservable<TSource> Publish<TSource>(
    this IObservable<TSource> source
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IConnectableObservable<TSource>^ Publish(
    IObservable<TSource>^ source
)
```

```fsharp
static member Publish : 
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
A connectable observable sequence that shares a single subscription to the underlying sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Publish\<TSource\>(IObservable\<TSource\>, TSource)

Returns a connectable observable sequence that shares a single subscription to the underlying sequence and starts with initialValue.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Publish(Of TSource) ( _
    source As IObservable(Of TSource), _
    initialValue As TSource _
) As IConnectableObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim initialValue As TSource
Dim returnValue As IConnectableObservable(Of TSource)

returnValue = source.Publish(initialValue)
```

```csharp
public static IConnectableObservable<TSource> Publish<TSource>(
    this IObservable<TSource> source,
    TSource initialValue
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IConnectableObservable<TSource>^ Publish(
    IObservable<TSource>^ source, 
    TSource initialValue
)
```

```fsharp
static member Publish : 
        source:IObservable<'TSource> * 
        initialValue:'TSource -> IConnectableObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

- initialValue  
  Type: TSource  
  The selector function which can use the multicasted source sequence as many times as needed, without causing multiple subscriptions to the source sequence.

#### Return Value

Type: [System.Reactive.Subjects.IConnectableObservable](IConnectableObservable/IConnectableObservable(T))\<TSource\>  
The connectable observable sequence that shares a single subscription to the underlying sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Publish\<TSource, TResult\>(IObservable\<TSource\>, Func\<IObservable\<TSource\>, IObservable\<TResult\>\>, TSource)

Returns a connectable observable sequence that shares a single subscription to the underlying sequence and starts with initialValue.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Publish(Of TSource, TResult) ( _
    source As IObservable(Of TSource), _
    selector As Func(Of IObservable(Of TSource), IObservable(Of TResult)), _
    initialValue As TSource _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim selector As Func(Of IObservable(Of TSource), IObservable(Of TResult))
Dim initialValue As TSource
Dim returnValue As IObservable(Of TResult)

returnValue = source.Publish(selector, _
    initialValue)
```

```csharp
public static IObservable<TResult> Publish<TSource, TResult>(
    this IObservable<TSource> source,
    Func<IObservable<TSource>, IObservable<TResult>> selector,
    TSource initialValue
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TResult>
static IObservable<TResult>^ Publish(
    IObservable<TSource>^ source, 
    Func<IObservable<TSource>^, IObservable<TResult>^>^ selector, 
    TSource initialValue
)
```

```fsharp
static member Publish : 
        source:IObservable<'TSource> * 
        selector:Func<IObservable<'TSource>, IObservable<'TResult>> * 
        initialValue:'TSource -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TResult  
  The type of Result.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

- selector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>, [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>\>  
  The selector function which can use the multicasted source sequence as many times as needed, without causing multiple subscriptions to the source sequence.

- initialValue  
  Type: TSource  
  The initial value received by observers upon subscription.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that contains the elements of a sequence produced by multicasting the source sequence within a selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Publish\<TSource, TResult\>(IObservable\<TSource\>, Func\<IObservable\<TSource\>, IObservable\<TResult\>\>)

Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Publish(Of TSource, TResult) ( _
    source As IObservable(Of TSource), _
    selector As Func(Of IObservable(Of TSource), IObservable(Of TResult)) _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim selector As Func(Of IObservable(Of TSource), IObservable(Of TResult))
Dim returnValue As IObservable(Of TResult)

returnValue = source.Publish(selector)
```

```csharp
public static IObservable<TResult> Publish<TSource, TResult>(
    this IObservable<TSource> source,
    Func<IObservable<TSource>, IObservable<TResult>> selector
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TResult>
static IObservable<TResult>^ Publish(
    IObservable<TSource>^ source, 
    Func<IObservable<TSource>^, IObservable<TResult>^>^ selector
)
```

```fsharp
static member Publish : 
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
