title: SubscribeOn
---
# DispatcherObservable.SubscribeOn Method

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[SubscribeOn<TSource>(IObservable<TSource>, DispatcherScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.dispatcherobservable.subscribeon%60%601(system.iobservable%7b%60%600%7d%2csystem.reactive.concurrency.dispatcherscheduler)(v=VS.103))![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[SubscribeOn<TSource>(IObservable<TSource>, Dispatcher)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.dispatcherobservable.subscribeon%60%601(system.iobservable%7b%60%600%7d%2csystem.windows.threading.dispatcher)(v=VS.103))Top

## See Also

#### Reference

[DispatcherObservable Class](DispatcherObservable/DispatcherObservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# SubscribeOn\<TSource\>(IObservable\<TSource\>, Dispatcher)

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Windows.Threading (in System.Reactive.Windows.Threading.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function SubscribeOn(Of TSource) ( _
    source As IObservable(Of TSource), _
    dispatcher As Dispatcher _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim dispatcher As Dispatcher
Dim returnValue As IObservable(Of TSource)

returnValue = source.SubscribeOn(dispatcher)
```

```csharp
public static IObservable<TSource> SubscribeOn<TSource>(
    this IObservable<TSource> source,
    Dispatcher dispatcher
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ SubscribeOn(
    IObservable<TSource>^ source, 
    Dispatcher^ dispatcher
)
```

```fsharp
static member SubscribeOn : 
        source:IObservable<'TSource> * 
        dispatcher:Dispatcher -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>

- dispatcher  
  Type: [System.Windows.Threading.Dispatcher](https://msdn.microsoft.com/en-us/library/ms615907)

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[DispatcherObservable Class](DispatcherObservable/DispatcherObservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# SubscribeOn\<TSource\>(IObservable\<TSource\>, DispatcherScheduler)

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Windows.Threading (in System.Reactive.Windows.Threading.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function SubscribeOn(Of TSource) ( _
    source As IObservable(Of TSource), _
    scheduler As DispatcherScheduler _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim scheduler As DispatcherScheduler
Dim returnValue As IObservable(Of TSource)

returnValue = source.SubscribeOn(scheduler)
```

```csharp
public static IObservable<TSource> SubscribeOn<TSource>(
    this IObservable<TSource> source,
    DispatcherScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ SubscribeOn(
    IObservable<TSource>^ source, 
    DispatcherScheduler^ scheduler
)
```

```fsharp
static member SubscribeOn : 
        source:IObservable<'TSource> * 
        scheduler:DispatcherScheduler -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>

- scheduler  
  Type: [System.Reactive.Concurrency.DispatcherScheduler](DispatcherScheduler/DispatcherScheduler)

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[DispatcherObservable Class](DispatcherObservable/DispatcherObservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
