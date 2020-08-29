title: FromEventPattern
---
# Qbservable.FromEventPattern Method

Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern<TEventArgs>(IQbservableProvider, Expression<Action<EventHandler<TEventArgs>>>, Expression<Action<EventHandler<TEventArgs>>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.fromeventpattern%60%601(system.reactive.linq.iqbservableprovider%2csystem.linq.expressions.expression%7bsystem.action%7bsystem.eventhandler%7b%60%600%7d%7d%7d%2csystem.linq.expressions.expression%7bsystem.action%7bsystem.eventhandler%7b%60%600%7d%7d%7d)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an queryable observable sequence with the specified add handler and remove handler.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern(IQbservableProvider, Expression<Action<EventHandler>>, Expression<Action<EventHandler>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.fromeventpattern(system.reactive.linq.iqbservableprovider%2csystem.linq.expressions.expression%7bsystem.action%7bsystem.eventhandler%7d%7d%2csystem.linq.expressions.expression%7bsystem.action%7bsystem.eventhandler%7d%7d)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to a queryable observable sequence with a specified add handler and remove handler.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern<TDelegate, TEventArgs>(IQbservableProvider, Expression<Action<TDelegate>>, Expression<Action<TDelegate>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.fromeventpattern%60%602(system.reactive.linq.iqbservableprovider%2csystem.linq.expressions.expression%7bsystem.action%7b%60%600%7d%7d%2csystem.linq.expressions.expression%7bsystem.action%7b%60%600%7d%7d)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an queryable observable sequence with the specified add handler and remove handler.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern<TEventArgs>(IQbservableProvider, Object, String)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.fromeventpattern%60%601(system.reactive.linq.iqbservableprovider%2csystem.object%2csystem.string)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence, using reflection to find an instance event.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern(IQbservableProvider, Object, String)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.fromeventpattern(system.reactive.linq.iqbservableprovider%2csystem.object%2csystem.string)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an queryable observable sequence, using reflection to find an instance event.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern<TEventArgs>(IQbservableProvider, Type, String)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.fromeventpattern%60%601(system.reactive.linq.iqbservableprovider%2csystem.type%2csystem.string)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to a queryable observable sequence, using reflection to find a static event.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern(IQbservableProvider, Type, String)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.fromeventpattern(system.reactive.linq.iqbservableprovider%2csystem.type%2csystem.string)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an queryable observable sequence, using reflection to find a static event.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern<TDelegate, TEventArgs>(IQbservableProvider, Expression<Func<EventHandler<TEventArgs>, TDelegate>>, Expression<Action<TDelegate>>, Expression<Action<TDelegate>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.fromeventpattern%60%602(system.reactive.linq.iqbservableprovider%2csystem.linq.expressions.expression%7bsystem.func%7bsystem.eventhandler%7b%60%601%7d%2c%60%600%7d%7d%2csystem.linq.expressions.expression%7bsystem.action%7b%60%600%7d%7d%2csystem.linq.expressions.expression%7bsystem.action%7b%60%600%7d%7d)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an queryable observable sequence with the specified conversion, add handler and remove handler.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern(IQbservableProvider, Expression\<Action\<EventHandler\>\>, Expression\<Action\<EventHandler\>\>)

Converts a .NET event, conforming to the standard .NET event pattern, to a queryable observable sequence with a specified add handler and remove handler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FromEventPattern ( _
    provider As IQbservableProvider, _
    addHandler As Expression(Of Action(Of EventHandler)), _
    removeHandler As Expression(Of Action(Of EventHandler)) _
) As IQbservable(Of EventPattern(Of EventArgs))
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim addHandler As Expression(Of Action(Of EventHandler))
Dim removeHandler As Expression(Of Action(Of EventHandler))
Dim returnValue As IQbservable(Of EventPattern(Of EventArgs))

returnValue = provider.FromEventPattern(addHandler, _
    removeHandler)
```

```csharp
public static IQbservable<EventPattern<EventArgs>> FromEventPattern(
    this IQbservableProvider provider,
    Expression<Action<EventHandler>> addHandler,
    Expression<Action<EventHandler>> removeHandler
)
```

```c++
[ExtensionAttribute]
public:
static IQbservable<EventPattern<EventArgs^>^>^ FromEventPattern(
    IQbservableProvider^ provider, 
    Expression<Action<EventHandler^>^>^ addHandler, 
    Expression<Action<EventHandler^>^>^ removeHandler
)
```

```fsharp
static member FromEventPattern : 
        provider:IQbservableProvider * 
        addHandler:Expression<Action<EventHandler>> * 
        removeHandler:Expression<Action<EventHandler>> -> IQbservable<EventPattern<EventArgs>> 
```

```jscript
public static function FromEventPattern(
    provider : IQbservableProvider, 
    addHandler : Expression<Action<EventHandler>>, 
    removeHandler : Expression<Action<EventHandler>>
) : IQbservable<EventPattern<EventArgs>>
```

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- addHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[EventHandler](https://msdn.microsoft.com/en-us/library/xhb70ccc)\>\>  
  The action that attaches the given event handler to the underlying .NET event.

- removeHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[EventHandler](https://msdn.microsoft.com/en-us/library/xhb70ccc)\>\>  
  The action that detaches the given event handler from the underlying .NET event.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<[EventArgs](https://msdn.microsoft.com/en-us/library/118wxtk3)\>\>  
The queryable observable sequence that contains data representations of invocations of the underlying .NET event.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern(IQbservableProvider, Type, String)

Converts a .NET event, conforming to the standard .NET event pattern, to an queryable observable sequence, using reflection to find a static event.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FromEventPattern ( _
    provider As IQbservableProvider, _
    type As Type, _
    eventName As String _
) As IQbservable(Of EventPattern(Of EventArgs))
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim type As Type
Dim eventName As String
Dim returnValue As IQbservable(Of EventPattern(Of EventArgs))

returnValue = provider.FromEventPattern(type, _
    eventName)
```

```csharp
public static IQbservable<EventPattern<EventArgs>> FromEventPattern(
    this IQbservableProvider provider,
    Type type,
    string eventName
)
```

```c++
[ExtensionAttribute]
public:
static IQbservable<EventPattern<EventArgs^>^>^ FromEventPattern(
    IQbservableProvider^ provider, 
    Type^ type, 
    String^ eventName
)
```

```fsharp
static member FromEventPattern : 
        provider:IQbservableProvider * 
        type:Type * 
        eventName:string -> IQbservable<EventPattern<EventArgs>> 
```

```jscript
public static function FromEventPattern(
    provider : IQbservableProvider, 
    type : Type, 
    eventName : String
) : IQbservable<EventPattern<EventArgs>>
```

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- type  
  Type: [System.Type](https://msdn.microsoft.com/en-us/library/42892f65)  
  The type that exposes the static event to convert.

- eventName  
  Type: [System.String](https://msdn.microsoft.com/en-us/library/s1wwdcbf)  
  The name of the event to convert.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<[EventArgs](https://msdn.microsoft.com/en-us/library/118wxtk3)\>\>  
The queryable observable sequence that contains data representations of invocations of the underlying .NET event.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern(IQbservableProvider, Object, String)

Converts a .NET event, conforming to the standard .NET event pattern, to an queryable observable sequence, using reflection to find an instance event.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FromEventPattern ( _
    provider As IQbservableProvider, _
    target As Object, _
    eventName As String _
) As IQbservable(Of EventPattern(Of EventArgs))
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim target As Object
Dim eventName As String
Dim returnValue As IQbservable(Of EventPattern(Of EventArgs))

returnValue = provider.FromEventPattern(target, _
    eventName)
```

```csharp
public static IQbservable<EventPattern<EventArgs>> FromEventPattern(
    this IQbservableProvider provider,
    Object target,
    string eventName
)
```

```c++
[ExtensionAttribute]
public:
static IQbservable<EventPattern<EventArgs^>^>^ FromEventPattern(
    IQbservableProvider^ provider, 
    Object^ target, 
    String^ eventName
)
```

```fsharp
static member FromEventPattern : 
        provider:IQbservableProvider * 
        target:Object * 
        eventName:string -> IQbservable<EventPattern<EventArgs>> 
```

```jscript
public static function FromEventPattern(
    provider : IQbservableProvider, 
    target : Object, 
    eventName : String
) : IQbservable<EventPattern<EventArgs>>
```

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- target  
  Type: [System.Object](https://msdn.microsoft.com/en-us/library/e5kfa45b)  
  The object instance that exposes the event to convert.

- eventName  
  Type: [System.String](https://msdn.microsoft.com/en-us/library/s1wwdcbf)  
  The name of the event to convert.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<[EventArgs](https://msdn.microsoft.com/en-us/library/118wxtk3)\>\>  
The queryable observable sequence that contains data representations of invocations of the underlying .NET event.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern\<TDelegate, TEventArgs\>(IQbservableProvider, Expression\<Func\<EventHandler\<TEventArgs\>, TDelegate\>\>, Expression\<Action\<TDelegate\>\>, Expression\<Action\<TDelegate\>\>)

Converts a .NET event, conforming to the standard .NET event pattern, to an queryable observable sequence with the specified conversion, add handler and remove handler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FromEventPattern(Of TDelegate, TEventArgs As EventArgs) ( _
    provider As IQbservableProvider, _
    conversion As Expression(Of Func(Of EventHandler(Of TEventArgs), TDelegate)), _
    addHandler As Expression(Of Action(Of TDelegate)), _
    removeHandler As Expression(Of Action(Of TDelegate)) _
) As IQbservable(Of EventPattern(Of TEventArgs))
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim conversion As Expression(Of Func(Of EventHandler(Of TEventArgs), TDelegate))
Dim addHandler As Expression(Of Action(Of TDelegate))
Dim removeHandler As Expression(Of Action(Of TDelegate))
Dim returnValue As IQbservable(Of EventPattern(Of TEventArgs))

returnValue = provider.FromEventPattern(conversion, _
    addHandler, removeHandler)
```

```csharp
public static IQbservable<EventPattern<TEventArgs>> FromEventPattern<TDelegate, TEventArgs>(
    this IQbservableProvider provider,
    Expression<Func<EventHandler<TEventArgs>, TDelegate>> conversion,
    Expression<Action<TDelegate>> addHandler,
    Expression<Action<TDelegate>> removeHandler
)
where TEventArgs : EventArgs
```

```c++
[ExtensionAttribute]
public:
generic<typename TDelegate, typename TEventArgs>
where TEventArgs : EventArgs
static IQbservable<EventPattern<TEventArgs>^>^ FromEventPattern(
    IQbservableProvider^ provider, 
    Expression<Func<EventHandler<TEventArgs>^, TDelegate>^>^ conversion, 
    Expression<Action<TDelegate>^>^ addHandler, 
    Expression<Action<TDelegate>^>^ removeHandler
)
```

```fsharp
static member FromEventPattern : 
        provider:IQbservableProvider * 
        conversion:Expression<Func<EventHandler<'TEventArgs>, 'TDelegate>> * 
        addHandler:Expression<Action<'TDelegate>> * 
        removeHandler:Expression<Action<'TDelegate>> -> IQbservable<EventPattern<'TEventArgs>>  when 'TEventArgs : EventArgs
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TDelegate  
  The type of delegate.

- TEventArgs  
  The type for the event.

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- conversion  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[EventHandler](https://msdn.microsoft.com/en-us/library/db0etb8x)\<TEventArgs\>, TDelegate\>\>  
  A function used to convert the given event handler to a delegate compatible with the underlying .NET event.

- addHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TDelegate\>\>  
  The action that attaches the given event handler to the underlying .NET event.

- removeHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TDelegate\>\>  
  The action that detaches the given event handler from the underlying .NET event.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<TEventArgs\>\>  
The queryable observable sequence that contains data representations of invocations of the underlying .NET event.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern\<TDelegate, TEventArgs\>(IQbservableProvider, Expression\<Action\<TDelegate\>\>, Expression\<Action\<TDelegate\>\>)

Converts a .NET event, conforming to the standard .NET event pattern, to an queryable observable sequence with the specified add handler and remove handler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FromEventPattern(Of TDelegate, TEventArgs As EventArgs) ( _
    provider As IQbservableProvider, _
    addHandler As Expression(Of Action(Of TDelegate)), _
    removeHandler As Expression(Of Action(Of TDelegate)) _
) As IQbservable(Of EventPattern(Of TEventArgs))
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim addHandler As Expression(Of Action(Of TDelegate))
Dim removeHandler As Expression(Of Action(Of TDelegate))
Dim returnValue As IQbservable(Of EventPattern(Of TEventArgs))

returnValue = provider.FromEventPattern(addHandler, _
    removeHandler)
```

```csharp
public static IQbservable<EventPattern<TEventArgs>> FromEventPattern<TDelegate, TEventArgs>(
    this IQbservableProvider provider,
    Expression<Action<TDelegate>> addHandler,
    Expression<Action<TDelegate>> removeHandler
)
where TEventArgs : EventArgs
```

```c++
[ExtensionAttribute]
public:
generic<typename TDelegate, typename TEventArgs>
where TEventArgs : EventArgs
static IQbservable<EventPattern<TEventArgs>^>^ FromEventPattern(
    IQbservableProvider^ provider, 
    Expression<Action<TDelegate>^>^ addHandler, 
    Expression<Action<TDelegate>^>^ removeHandler
)
```

```fsharp
static member FromEventPattern : 
        provider:IQbservableProvider * 
        addHandler:Expression<Action<'TDelegate>> * 
        removeHandler:Expression<Action<'TDelegate>> -> IQbservable<EventPattern<'TEventArgs>>  when 'TEventArgs : EventArgs
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TDelegate  
  The type of delegate.

- TEventArgs  
  The type for the event.

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- addHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TDelegate\>\>  
  The action that attaches the given event handler to the underlying .NET event.

- removeHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TDelegate\>\>  
  The action that detaches the given event handler from the underlying .NET event.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<TEventArgs\>\>  
The queryable observable sequence that contains data representations of invocations of the underlying .NET event.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern\<TEventArgs\>(IQbservableProvider, Expression\<Action\<EventHandler\<TEventArgs\>\>\>, Expression\<Action\<EventHandler\<TEventArgs\>\>\>)

Converts a .NET event, conforming to the standard .NET event pattern, to an queryable observable sequence with the specified add handler and remove handler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FromEventPattern(Of TEventArgs As EventArgs) ( _
    provider As IQbservableProvider, _
    addHandler As Expression(Of Action(Of EventHandler(Of TEventArgs))), _
    removeHandler As Expression(Of Action(Of EventHandler(Of TEventArgs))) _
) As IQbservable(Of EventPattern(Of TEventArgs))
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim addHandler As Expression(Of Action(Of EventHandler(Of TEventArgs)))
Dim removeHandler As Expression(Of Action(Of EventHandler(Of TEventArgs)))
Dim returnValue As IQbservable(Of EventPattern(Of TEventArgs))

returnValue = provider.FromEventPattern(addHandler, _
    removeHandler)
```

```csharp
public static IQbservable<EventPattern<TEventArgs>> FromEventPattern<TEventArgs>(
    this IQbservableProvider provider,
    Expression<Action<EventHandler<TEventArgs>>> addHandler,
    Expression<Action<EventHandler<TEventArgs>>> removeHandler
)
where TEventArgs : EventArgs
```

```c++
[ExtensionAttribute]
public:
generic<typename TEventArgs>
where TEventArgs : EventArgs
static IQbservable<EventPattern<TEventArgs>^>^ FromEventPattern(
    IQbservableProvider^ provider, 
    Expression<Action<EventHandler<TEventArgs>^>^>^ addHandler, 
    Expression<Action<EventHandler<TEventArgs>^>^>^ removeHandler
)
```

```fsharp
static member FromEventPattern : 
        provider:IQbservableProvider * 
        addHandler:Expression<Action<EventHandler<'TEventArgs>>> * 
        removeHandler:Expression<Action<EventHandler<'TEventArgs>>> -> IQbservable<EventPattern<'TEventArgs>>  when 'TEventArgs : EventArgs
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TEventArgs  
  The type for the event.

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- addHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[EventHandler](https://msdn.microsoft.com/en-us/library/db0etb8x)\<TEventArgs\>\>\>  
  The action that attaches the given event handler to the underlying .NET event.

- removeHandler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[EventHandler](https://msdn.microsoft.com/en-us/library/db0etb8x)\<TEventArgs\>\>\>  
  The action that detaches the given event handler from the underlying .NET event.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<TEventArgs\>\>  
The queryable observable sequence that contains data representations of invocations of the underlying .NET event.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern\<TEventArgs\>(IQbservableProvider, Type, String)

Converts a .NET event, conforming to the standard .NET event pattern, to a queryable observable sequence, using reflection to find a static event.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FromEventPattern(Of TEventArgs As EventArgs) ( _
    provider As IQbservableProvider, _
    type As Type, _
    eventName As String _
) As IQbservable(Of EventPattern(Of TEventArgs))
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim type As Type
Dim eventName As String
Dim returnValue As IQbservable(Of EventPattern(Of TEventArgs))

returnValue = provider.FromEventPattern(type, _
    eventName)
```

```csharp
public static IQbservable<EventPattern<TEventArgs>> FromEventPattern<TEventArgs>(
    this IQbservableProvider provider,
    Type type,
    string eventName
)
where TEventArgs : EventArgs
```

```c++
[ExtensionAttribute]
public:
generic<typename TEventArgs>
where TEventArgs : EventArgs
static IQbservable<EventPattern<TEventArgs>^>^ FromEventPattern(
    IQbservableProvider^ provider, 
    Type^ type, 
    String^ eventName
)
```

```fsharp
static member FromEventPattern : 
        provider:IQbservableProvider * 
        type:Type * 
        eventName:string -> IQbservable<EventPattern<'TEventArgs>>  when 'TEventArgs : EventArgs
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TEventArgs  
  The type for the event.

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- type  
  Type: [System.Type](https://msdn.microsoft.com/en-us/library/42892f65)  
  The type that exposes the static event to convert.

- eventName  
  Type: [System.String](https://msdn.microsoft.com/en-us/library/s1wwdcbf)  
  The name of the event to convert.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<TEventArgs\>\>  
The queryable observable sequence that contains data representations of invocations of the underlying .NET event.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern\<TEventArgs\>(IQbservableProvider, Object, String)

Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence, using reflection to find an instance event.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FromEventPattern(Of TEventArgs As EventArgs) ( _
    provider As IQbservableProvider, _
    target As Object, _
    eventName As String _
) As IQbservable(Of EventPattern(Of TEventArgs))
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim target As Object
Dim eventName As String
Dim returnValue As IQbservable(Of EventPattern(Of TEventArgs))

returnValue = provider.FromEventPattern(target, _
    eventName)
```

```csharp
public static IQbservable<EventPattern<TEventArgs>> FromEventPattern<TEventArgs>(
    this IQbservableProvider provider,
    Object target,
    string eventName
)
where TEventArgs : EventArgs
```

```c++
[ExtensionAttribute]
public:
generic<typename TEventArgs>
where TEventArgs : EventArgs
static IQbservable<EventPattern<TEventArgs>^>^ FromEventPattern(
    IQbservableProvider^ provider, 
    Object^ target, 
    String^ eventName
)
```

```fsharp
static member FromEventPattern : 
        provider:IQbservableProvider * 
        target:Object * 
        eventName:string -> IQbservable<EventPattern<'TEventArgs>>  when 'TEventArgs : EventArgs
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TEventArgs  
  The type for the event.

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- target  
  Type: [System.Object](https://msdn.microsoft.com/en-us/library/e5kfa45b)  
  Th object instance that exposes the event to convert.

- eventName  
  Type: [System.String](https://msdn.microsoft.com/en-us/library/s1wwdcbf)  
  The name of the event to convert.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<TEventArgs\>\>  
The queryable observable sequence that contains data representations of invocations of the underlying .NET event.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
