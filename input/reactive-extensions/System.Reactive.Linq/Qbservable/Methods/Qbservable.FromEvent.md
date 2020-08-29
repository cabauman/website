title: FromEvent
---
# Qbservable.FromEvent Method

Converts a .NET event to a queryable observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEvent<TEventArgs>(IQbservableProvider, Expression<Action<Action<TEventArgs>>>, Expression<Action<Action<TEventArgs>>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.fromevent%60%601(system.reactive.linq.iqbservableprovider%2csystem.linq.expressions.expression%7bsystem.action%7bsystem.action%7b%60%600%7d%7d%7d%2csystem.linq.expressions.expression%7bsystem.action%7bsystem.action%7b%60%600%7d%7d%7d)(v=VS.103))Converts a .NET event to a queryable observable sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEvent(IQbservableProvider, Expression<Action<Action>>, Expression<Action<Action>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.fromevent(system.reactive.linq.iqbservableprovider%2csystem.linq.expressions.expression%7bsystem.action%7bsystem.action%7d%7d%2csystem.linq.expressions.expression%7bsystem.action%7bsystem.action%7d%7d)(v=VS.103))Converts a .NET event to a queryable observable sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEvent<TDelegate, TEventArgs>(IQbservableProvider, Expression<Action<TDelegate>>, Expression<Action<TDelegate>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.fromevent%60%602(system.reactive.linq.iqbservableprovider%2csystem.linq.expressions.expression%7bsystem.action%7b%60%600%7d%7d%2csystem.linq.expressions.expression%7bsystem.action%7b%60%600%7d%7d)(v=VS.103))Converts a .NET event to a queryable observable sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEvent<TDelegate, TEventArgs>(IQbservableProvider, Expression<Func<Action<TEventArgs>, TDelegate>>, Expression<Action<TDelegate>>, Expression<Action<TDelegate>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.fromevent%60%602(system.reactive.linq.iqbservableprovider%2csystem.linq.expressions.expression%7bsystem.func%7bsystem.action%7b%60%601%7d%2c%60%600%7d%7d%2csystem.linq.expressions.expression%7bsystem.action%7b%60%600%7d%7d%2csystem.linq.expressions.expression%7bsystem.action%7b%60%600%7d%7d)(v=VS.103))Converts a .NET event to a queryable observable sequence.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEvent(IQbservableProvider, Expression\<Action\<Action\>\>, Expression\<Action\<Action\>\>)

Converts a .NET event to a queryable observable sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FromEvent ( _
    provider As IQbservableProvider, _
    addHandler As Expression(Of Action(Of Action)), _
    removeHandler As Expression(Of Action(Of Action)) _
) As IQbservable(Of Unit)
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim addHandler As Expression(Of Action(Of Action))
Dim removeHandler As Expression(Of Action(Of Action))
Dim returnValue As IQbservable(Of Unit)

returnValue = provider.FromEvent(addHandler, _
    removeHandler)
```

```csharp
public static IQbservable<Unit> FromEvent(
    this IQbservableProvider provider,
    Expression<Action<Action>> addHandler,
    Expression<Action<Action>> removeHandler
)
```

```c++
[ExtensionAttribute]
public:
static IQbservable<Unit>^ FromEvent(
    IQbservableProvider^ provider, 
    Expression<Action<Action^>^>^ addHandler, 
    Expression<Action<Action^>^>^ removeHandler
)
```

```fsharp
static member FromEvent : 
        provider:IQbservableProvider * 
        addHandler:Expression<Action<Action>> * 
        removeHandler:Expression<Action<Action>> -> IQbservable<Unit> 
```

```jscript
public static function FromEvent(
    provider : IQbservableProvider, 
    addHandler : Expression<Action<Action>>, 
    removeHandler : Expression<Action<Action>>
) : IQbservable<Unit>
```

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- addHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[Action](https://msdn.microsoft.com/en-us/library/Bb534741)\>\>  
  Action that attaches the given event handler to the underlying .NET event.

- removeHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[Action](https://msdn.microsoft.com/en-us/library/Bb534741)\>\>  
  Action that detaches the given event handler from the underlying .NET event.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[Unit](Unit/Unit)\>  
Observable sequence that contains data representations of invocations of the underlying .NET event.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEvent\<TDelegate, TEventArgs\>(IQbservableProvider, Expression\<Action\<TDelegate\>\>, Expression\<Action\<TDelegate\>\>)

Converts a .NET event to a queryable observable sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FromEvent(Of TDelegate, TEventArgs) ( _
    provider As IQbservableProvider, _
    addHandler As Expression(Of Action(Of TDelegate)), _
    removeHandler As Expression(Of Action(Of TDelegate)) _
) As IQbservable(Of TEventArgs)
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim addHandler As Expression(Of Action(Of TDelegate))
Dim removeHandler As Expression(Of Action(Of TDelegate))
Dim returnValue As IQbservable(Of TEventArgs)

returnValue = provider.FromEvent(addHandler, _
    removeHandler)
```

```csharp
public static IQbservable<TEventArgs> FromEvent<TDelegate, TEventArgs>(
    this IQbservableProvider provider,
    Expression<Action<TDelegate>> addHandler,
    Expression<Action<TDelegate>> removeHandler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TDelegate, typename TEventArgs>
static IQbservable<TEventArgs>^ FromEvent(
    IQbservableProvider^ provider, 
    Expression<Action<TDelegate>^>^ addHandler, 
    Expression<Action<TDelegate>^>^ removeHandler
)
```

```fsharp
static member FromEvent : 
        provider:IQbservableProvider * 
        addHandler:Expression<Action<'TDelegate>> * 
        removeHandler:Expression<Action<'TDelegate>> -> IQbservable<'TEventArgs> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TDelegate  
  The type of delegate.

- TEventArgs  
  The type of event.

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- addHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TDelegate\>\>  
  Action that attaches the given event handler to the underlying .NET event.

- removeHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TDelegate\>\>  
  Action that detaches the given event handler from the underlying .NET event.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TEventArgs\>  
The queryable observable sequence that contains data representations of invocations of the underlying .NET event.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEvent\<TDelegate, TEventArgs\>(IQbservableProvider, Expression\<Func\<Action\<TEventArgs\>, TDelegate\>\>, Expression\<Action\<TDelegate\>\>, Expression\<Action\<TDelegate\>\>)

Converts a .NET event to a queryable observable sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FromEvent(Of TDelegate, TEventArgs) ( _
    provider As IQbservableProvider, _
    conversion As Expression(Of Func(Of Action(Of TEventArgs), TDelegate)), _
    addHandler As Expression(Of Action(Of TDelegate)), _
    removeHandler As Expression(Of Action(Of TDelegate)) _
) As IQbservable(Of TEventArgs)
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim conversion As Expression(Of Func(Of Action(Of TEventArgs), TDelegate))
Dim addHandler As Expression(Of Action(Of TDelegate))
Dim removeHandler As Expression(Of Action(Of TDelegate))
Dim returnValue As IQbservable(Of TEventArgs)

returnValue = provider.FromEvent(conversion, _
    addHandler, removeHandler)
```

```csharp
public static IQbservable<TEventArgs> FromEvent<TDelegate, TEventArgs>(
    this IQbservableProvider provider,
    Expression<Func<Action<TEventArgs>, TDelegate>> conversion,
    Expression<Action<TDelegate>> addHandler,
    Expression<Action<TDelegate>> removeHandler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TDelegate, typename TEventArgs>
static IQbservable<TEventArgs>^ FromEvent(
    IQbservableProvider^ provider, 
    Expression<Func<Action<TEventArgs>^, TDelegate>^>^ conversion, 
    Expression<Action<TDelegate>^>^ addHandler, 
    Expression<Action<TDelegate>^>^ removeHandler
)
```

```fsharp
static member FromEvent : 
        provider:IQbservableProvider * 
        conversion:Expression<Func<Action<'TEventArgs>, 'TDelegate>> * 
        addHandler:Expression<Action<'TDelegate>> * 
        removeHandler:Expression<Action<'TDelegate>> -> IQbservable<'TEventArgs> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TDelegate  
  The type of delegate.

- TEventArgs  
  The type of event.

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- conversion  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TEventArgs\>, TDelegate\>\>  
  A function used to convert the given event handler to a delegate compatible with the underlying .NET event. The resulting delegate is used in calls to the addHandler and removeHandler action parameters.

- addHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TDelegate\>\>  
  Action that attaches the given event handler to the underlying .NET event.

- removeHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TDelegate\>\>  
  Action that detaches the given event handler from the underlying .NET event.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TEventArgs\>  
The queryable observable sequence that contains data representations of invocations of the underlying .NET event.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEvent\<TEventArgs\>(IQbservableProvider, Expression\<Action\<Action\<TEventArgs\>\>\>, Expression\<Action\<Action\<TEventArgs\>\>\>)

Converts a .NET event to a queryable observable sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FromEvent(Of TEventArgs) ( _
    provider As IQbservableProvider, _
    addHandler As Expression(Of Action(Of Action(Of TEventArgs))), _
    removeHandler As Expression(Of Action(Of Action(Of TEventArgs))) _
) As IQbservable(Of TEventArgs)
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim addHandler As Expression(Of Action(Of Action(Of TEventArgs)))
Dim removeHandler As Expression(Of Action(Of Action(Of TEventArgs)))
Dim returnValue As IQbservable(Of TEventArgs)

returnValue = provider.FromEvent(addHandler, _
    removeHandler)
```

```csharp
public static IQbservable<TEventArgs> FromEvent<TEventArgs>(
    this IQbservableProvider provider,
    Expression<Action<Action<TEventArgs>>> addHandler,
    Expression<Action<Action<TEventArgs>>> removeHandler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TEventArgs>
static IQbservable<TEventArgs>^ FromEvent(
    IQbservableProvider^ provider, 
    Expression<Action<Action<TEventArgs>^>^>^ addHandler, 
    Expression<Action<Action<TEventArgs>^>^>^ removeHandler
)
```

```fsharp
static member FromEvent : 
        provider:IQbservableProvider * 
        addHandler:Expression<Action<Action<'TEventArgs>>> * 
        removeHandler:Expression<Action<Action<'TEventArgs>>> -> IQbservable<'TEventArgs> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TEventArgs  
  The type of event.

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- addHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TEventArgs\>\>\>  
  Action that attaches the given event handler to the underlying .NET event.

- removeHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TEventArgs\>\>\>  
  Action that detaches the given event handler from the underlying .NET event.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TEventArgs\>  
Observable sequence that contains data representations of invocations of the underlying .NET event.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
