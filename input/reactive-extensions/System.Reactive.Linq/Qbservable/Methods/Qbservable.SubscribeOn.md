title: SubscribeOn
---
# Qbservable.SubscribeOn Method

Asynchronously subscribes and unsubscribes observers on the specified scheduler and context.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[SubscribeOn<TSource>(IQbservable<TSource>, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.subscribeon%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Asynchronously subscribes and unsubscribes observers on the specified synchronization context.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[SubscribeOn<TSource>(IQbservable<TSource>, SynchronizationContext)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.subscribeon%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.threading.synchronizationcontext)(v=VS.103))Asynchronously subscribes and unsubscribes observers on the specified synchronization context.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# SubscribeOn\<TSource\>(IQbservable\<TSource\>, SynchronizationContext)

Asynchronously subscribes and unsubscribes observers on the specified synchronization context.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function SubscribeOn(Of TSource) ( _
    source As IQbservable(Of TSource), _
    context As SynchronizationContext _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim context As SynchronizationContext
Dim returnValue As IQbservable(Of TSource)

returnValue = source.SubscribeOn(context)
```

```csharp
public static IQbservable<TSource> SubscribeOn<TSource>(
    this IQbservable<TSource> source,
    SynchronizationContext context
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ SubscribeOn(
    IQbservable<TSource>^ source, 
    SynchronizationContext^ context
)
```

```fsharp
static member SubscribeOn : 
        source:IQbservable<'TSource> * 
        context:SynchronizationContext -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  The source sequence.

- context  
  Type: [System.Threading.SynchronizationContext](https://msdn.microsoft.com/en-us/library/wx31754f)  
  The synchronization context to perform subscription and unsubscription actions on.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The source sequence whose subscriptions and unsubscriptions happen on the specified synchronization context.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# SubscribeOn\<TSource\>(IQbservable\<TSource\>, IScheduler)

Asynchronously subscribes and unsubscribes observers on the specified synchronization context.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function SubscribeOn(Of TSource) ( _
    source As IQbservable(Of TSource), _
    scheduler As IScheduler _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim scheduler As IScheduler
Dim returnValue As IQbservable(Of TSource)

returnValue = source.SubscribeOn(scheduler)
```

```csharp
public static IQbservable<TSource> SubscribeOn<TSource>(
    this IQbservable<TSource> source,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ SubscribeOn(
    IQbservable<TSource>^ source, 
    IScheduler^ scheduler
)
```

```fsharp
static member SubscribeOn : 
        source:IQbservable<'TSource> * 
        scheduler:IScheduler -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  The source sequence.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The synchronization context to perform subscription and unsubscription actions on.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The source sequence whose subscriptions and unsubscriptions happen on the specified synchronization context.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
