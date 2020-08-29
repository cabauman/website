title: FromEventPattern
---
# Observable.FromEventPattern Method

Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern<TEventArgs>(Action<EventHandler<TEventArgs>>, Action<EventHandler<TEventArgs>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.fromeventpattern%60%601(system.action%7bsystem.eventhandler%7b%60%600%7d%7d%2csystem.action%7bsystem.eventhandler%7b%60%600%7d%7d)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence with the specified add handler and remove handler.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern(Action<EventHandler>, Action<EventHandler>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.fromeventpattern(system.action%7bsystem.eventhandler%7d%2csystem.action%7bsystem.eventhandler%7d)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence with a specified add handler and remove handler.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern<TDelegate, TEventArgs>(Action<TDelegate>, Action<TDelegate>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.fromeventpattern%60%602(system.action%7b%60%600%7d%2csystem.action%7b%60%600%7d)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence with the specified add handler and remove handler.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern(Object, String)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.fromeventpattern(system.object%2csystem.string)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence, using reflection to find an instance event.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern<TEventArgs>(Object, String)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.fromeventpattern%60%601(system.object%2csystem.string)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence, using reflection to find an instance event.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern(Type, String)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.fromeventpattern(system.type%2csystem.string)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence, using reflection to find a static event.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern<TEventArgs>(Type, String)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.fromeventpattern%60%601(system.type%2csystem.string)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence, using reflection to find a static event.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[FromEventPattern<TDelegate, TEventArgs>(Func<EventHandler<TEventArgs>, TDelegate>, Action<TDelegate>, Action<TDelegate>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.fromeventpattern%60%602(system.func%7bsystem.eventhandler%7b%60%601%7d%2c%60%600%7d%2csystem.action%7b%60%600%7d%2csystem.action%7b%60%600%7d)(v=VS.103))Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence with the specified conversion, add handler and remove handler.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern(Object, String)

Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence, using reflection to find an instance event.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function FromEventPattern ( _
    target As Object, _
    eventName As String _
) As IObservable(Of EventPattern(Of EventArgs))
```

```vb
'Usage
Dim target As Object
Dim eventName As String
Dim returnValue As IObservable(Of EventPattern(Of EventArgs))

returnValue = Observable.FromEventPattern(target, _
    eventName)
```

```csharp
public static IObservable<EventPattern<EventArgs>> FromEventPattern(
    Object target,
    string eventName
)
```

```c++
public:
static IObservable<EventPattern<EventArgs^>^>^ FromEventPattern(
    Object^ target, 
    String^ eventName
)
```

```fsharp
static member FromEventPattern : 
        target:Object * 
        eventName:string -> IObservable<EventPattern<EventArgs>> 
```

```jscript
public static function FromEventPattern(
    target : Object, 
    eventName : String
) : IObservable<EventPattern<EventArgs>>
```

#### Parameters

- target  
  Type: [System.Object](https://msdn.microsoft.com/en-us/library/e5kfa45b)  
  The object instance that exposes the event to convert.

- eventName  
  Type: [System.String](https://msdn.microsoft.com/en-us/library/s1wwdcbf)  
  The name of the event to convert.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<[EventArgs](https://msdn.microsoft.com/en-us/library/118wxtk3)\>\>  
The observable sequence that contains data representations of invocations of the underlying .NET event.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern(Type, String)

Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence, using reflection to find a static event.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function FromEventPattern ( _
    type As Type, _
    eventName As String _
) As IObservable(Of EventPattern(Of EventArgs))
```

```vb
'Usage
Dim type As Type
Dim eventName As String
Dim returnValue As IObservable(Of EventPattern(Of EventArgs))

returnValue = Observable.FromEventPattern(type, _
    eventName)
```

```csharp
public static IObservable<EventPattern<EventArgs>> FromEventPattern(
    Type type,
    string eventName
)
```

```c++
public:
static IObservable<EventPattern<EventArgs^>^>^ FromEventPattern(
    Type^ type, 
    String^ eventName
)
```

```fsharp
static member FromEventPattern : 
        type:Type * 
        eventName:string -> IObservable<EventPattern<EventArgs>> 
```

```jscript
public static function FromEventPattern(
    type : Type, 
    eventName : String
) : IObservable<EventPattern<EventArgs>>
```

#### Parameters

- type  
  Type: [System.Type](https://msdn.microsoft.com/en-us/library/42892f65)  
  The type that exposes the static event to convert.

- eventName  
  Type: [System.String](https://msdn.microsoft.com/en-us/library/s1wwdcbf)  
  The name of the event to convert.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<[EventArgs](https://msdn.microsoft.com/en-us/library/118wxtk3)\>\>  
The observable sequence that contains data representations of invocations of the underlying .NET event.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern(Action\<EventHandler\>, Action\<EventHandler\>)

Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence with a specified add handler and remove handler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function FromEventPattern ( _
    addHandler As Action(Of EventHandler), _
    removeHandler As Action(Of EventHandler) _
) As IObservable(Of EventPattern(Of EventArgs))
```

```vb
'Usage
Dim addHandler As Action(Of EventHandler)
Dim removeHandler As Action(Of EventHandler)
Dim returnValue As IObservable(Of EventPattern(Of EventArgs))

returnValue = Observable.FromEventPattern(addHandler, _
    removeHandler)
```

```csharp
public static IObservable<EventPattern<EventArgs>> FromEventPattern(
    Action<EventHandler> addHandler,
    Action<EventHandler> removeHandler
)
```

```c++
public:
static IObservable<EventPattern<EventArgs^>^>^ FromEventPattern(
    Action<EventHandler^>^ addHandler, 
    Action<EventHandler^>^ removeHandler
)
```

```fsharp
static member FromEventPattern : 
        addHandler:Action<EventHandler> * 
        removeHandler:Action<EventHandler> -> IObservable<EventPattern<EventArgs>> 
```

```jscript
public static function FromEventPattern(
    addHandler : Action<EventHandler>, 
    removeHandler : Action<EventHandler>
) : IObservable<EventPattern<EventArgs>>
```

#### Parameters

- addHandler  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[EventHandler](https://msdn.microsoft.com/en-us/library/xhb70ccc)\>  
  The action that attaches the given event handler to the underlying .NET event.

- removeHandler  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[EventHandler](https://msdn.microsoft.com/en-us/library/xhb70ccc)\>  
  The action that detaches the given event handler from the underlying .NET event.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<[EventArgs](https://msdn.microsoft.com/en-us/library/118wxtk3)\>\>  
The observable sequence that contains data representations of invocations of the underlying .NET event.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern\<TDelegate, TEventArgs\>(Func\<EventHandler\<TEventArgs\>, TDelegate\>, Action\<TDelegate\>, Action\<TDelegate\>)

Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence with the specified conversion, add handler and remove handler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function FromEventPattern(Of TDelegate, TEventArgs As EventArgs) ( _
    conversion As Func(Of EventHandler(Of TEventArgs), TDelegate), _
    addHandler As Action(Of TDelegate), _
    removeHandler As Action(Of TDelegate) _
) As IObservable(Of EventPattern(Of TEventArgs))
```

```vb
'Usage
Dim conversion As Func(Of EventHandler(Of TEventArgs), TDelegate)
Dim addHandler As Action(Of TDelegate)
Dim removeHandler As Action(Of TDelegate)
Dim returnValue As IObservable(Of EventPattern(Of TEventArgs))

returnValue = Observable.FromEventPattern(conversion, _
    addHandler, removeHandler)
```

```csharp
public static IObservable<EventPattern<TEventArgs>> FromEventPattern<TDelegate, TEventArgs>(
    Func<EventHandler<TEventArgs>, TDelegate> conversion,
    Action<TDelegate> addHandler,
    Action<TDelegate> removeHandler
)
where TEventArgs : EventArgs
```

```c++
public:
generic<typename TDelegate, typename TEventArgs>
where TEventArgs : EventArgs
static IObservable<EventPattern<TEventArgs>^>^ FromEventPattern(
    Func<EventHandler<TEventArgs>^, TDelegate>^ conversion, 
    Action<TDelegate>^ addHandler, 
    Action<TDelegate>^ removeHandler
)
```

```fsharp
static member FromEventPattern : 
        conversion:Func<EventHandler<'TEventArgs>, 'TDelegate> * 
        addHandler:Action<'TDelegate> * 
        removeHandler:Action<'TDelegate> -> IObservable<EventPattern<'TEventArgs>>  when 'TEventArgs : EventArgs
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

- conversion  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[EventHandler](https://msdn.microsoft.com/en-us/library/db0etb8x)\<TEventArgs\>, TDelegate\>  
  A function used to convert the given event handler to a delegate compatible with the underlying .NET event.

- addHandler  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TDelegate\>  
  The action that attaches the given event handler to the underlying .NET event.

- removeHandler  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TDelegate\>  
  The action that detaches the given event handler from the underlying .NET event.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<TEventArgs\>\>  
The observable sequence that contains data representations of invocations of the underlying .NET event.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern\<TDelegate, TEventArgs\>(Action\<TDelegate\>, Action\<TDelegate\>)

Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence with the specified add handler and remove handler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function FromEventPattern(Of TDelegate, TEventArgs As EventArgs) ( _
    addHandler As Action(Of TDelegate), _
    removeHandler As Action(Of TDelegate) _
) As IObservable(Of EventPattern(Of TEventArgs))
```

```vb
'Usage
Dim addHandler As Action(Of TDelegate)
Dim removeHandler As Action(Of TDelegate)
Dim returnValue As IObservable(Of EventPattern(Of TEventArgs))

returnValue = Observable.FromEventPattern(addHandler, _
    removeHandler)
```

```csharp
public static IObservable<EventPattern<TEventArgs>> FromEventPattern<TDelegate, TEventArgs>(
    Action<TDelegate> addHandler,
    Action<TDelegate> removeHandler
)
where TEventArgs : EventArgs
```

```c++
public:
generic<typename TDelegate, typename TEventArgs>
where TEventArgs : EventArgs
static IObservable<EventPattern<TEventArgs>^>^ FromEventPattern(
    Action<TDelegate>^ addHandler, 
    Action<TDelegate>^ removeHandler
)
```

```fsharp
static member FromEventPattern : 
        addHandler:Action<'TDelegate> * 
        removeHandler:Action<'TDelegate> -> IObservable<EventPattern<'TEventArgs>>  when 'TEventArgs : EventArgs
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

- addHandler  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TDelegate\>  
  The action that attaches the given event handler to the underlying .NET event.

- removeHandler  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<TDelegate\>  
  The action that detaches the given event handler from the underlying .NET event.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<TEventArgs\>\>  
The observable sequence that contains data representations of invocations of the underlying .NET event.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern\<TEventArgs\>(Object, String)

Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence, using reflection to find an instance event.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function FromEventPattern(Of TEventArgs As EventArgs) ( _
    target As Object, _
    eventName As String _
) As IObservable(Of EventPattern(Of TEventArgs))
```

```vb
'Usage
Dim target As Object
Dim eventName As String
Dim returnValue As IObservable(Of EventPattern(Of TEventArgs))

returnValue = Observable.FromEventPattern(target, _
    eventName)
```

```csharp
public static IObservable<EventPattern<TEventArgs>> FromEventPattern<TEventArgs>(
    Object target,
    string eventName
)
where TEventArgs : EventArgs
```

```c++
public:
generic<typename TEventArgs>
where TEventArgs : EventArgs
static IObservable<EventPattern<TEventArgs>^>^ FromEventPattern(
    Object^ target, 
    String^ eventName
)
```

```fsharp
static member FromEventPattern : 
        target:Object * 
        eventName:string -> IObservable<EventPattern<'TEventArgs>>  when 'TEventArgs : EventArgs
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TEventArgs  
  The type of event.

#### Parameters

- target  
  Type: [System.Object](https://msdn.microsoft.com/en-us/library/e5kfa45b)  
  The object instance that exposes the event to convert.

- eventName  
  Type: [System.String](https://msdn.microsoft.com/en-us/library/s1wwdcbf)  
  The name of the event to convert.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<TEventArgs\>\>  
The return value is an observable sequence that contains data representations of invocations of the underlying .NET event.

## Remarks

The FromEventPattern operator converts a .Net event to a sequence of [EventPattern\<TEventArgs\>](EventPattern/EventPattern(TEventArgs)). Each EventPattern instance contains the event arguments and the object sending the event. The event arguments are provided in the EventArgs property of each EventPattern delivered in the sequence. The object sending the event is provided in the Sender property of the EventPattern instance. The desired event is specified by passing the object that exposes the event as the **target** parameter and by setting the **eventName** parameter to the name of the event. The **TEventArgs** type specifies the type of event arguments that will be delivered with each event.

## Examples

This example code demonstrates using the FromEventPattern operator to listen for Create, Rename, and Delete events on a System.IO.FileSystemWatcher. The example watches for changes in the C:\\Users\\Public folder and writes the events to the console window.

    using System;
    using System.Reactive.Linq;
    using System.Reactive;
    using System.IO;
    
    namespace Example
    {
      class Program
      {
        static void Main()
        {
          //*********************************************************************************************************************//
          //*** Create a FileSystemWatcher to watch the C:\Users\Public directory using the default NotifyFilter watching for ***//
          //*** changes to any type of file.                                                                                  ***//
          //*********************************************************************************************************************//
    
          FileSystemWatcher fsw = new FileSystemWatcher(@"C:\Users\Public", "*.*");
          fsw.EnableRaisingEvents = true;
    
    
          //***************************************************************************************//
          //*** Use the FromEventPattern operator to setup a subscription to the Created event. ***//
          //***************************************************************************************//
    
          IObservable<EventPattern<FileSystemEventArgs>> fswCreated = Observable.FromEventPattern<FileSystemEventArgs>(fsw, "Created");
          fswCreated.Subscribe(pattern => Console.WriteLine("{0} was created in {1}.", pattern.EventArgs.Name, ((FileSystemWatcher)pattern.Sender).Path));
    
    
          //***************************************************************************************//
          //*** Use the FromEventPattern operator to setup a subscription to the Renamed event. ***//
          //***************************************************************************************//
    
          IObservable<EventPattern<RenamedEventArgs>> fswRenamed = Observable.FromEventPattern<RenamedEventArgs>(fsw, "Renamed");
          fswRenamed.Subscribe(pattern => Console.WriteLine("{0} was renamed to {1} in {2}.", pattern.EventArgs.OldName, 
                                                            pattern.EventArgs.Name, ((FileSystemWatcher)pattern.Sender).Path));
    
    
          //***************************************************************************************//
          //*** Use the FromEventPattern operator to setup a subscription to the Deleted event. ***//
          //***************************************************************************************//
    
          IObservable<EventPattern<FileSystemEventArgs>> fswDeleted = Observable.FromEventPattern<FileSystemEventArgs>(fsw, "Deleted");
          fswDeleted.Subscribe(pattern => Console.WriteLine("{0} was deleted in {1}.", pattern.EventArgs.Name, ((FileSystemWatcher)pattern.Sender).Path));
    
    
          Console.WriteLine("Press ENTER to exit...\n");
          Console.ReadLine();
        }
      }
    }

The following output demonstrates running the example code to create a new text file in the C:\\Users\\Public directory. The file is renamed to ExFile.txt and then deleted.

    Press ENTER to exit...
    
    New Text Document.txt was created in C:\Users\Public.
    New Text Document.txt was renamed to ExFile.txt in C:\Users\Public.
    ExFile.txt was deleted in C:\Users\Public.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern\<TEventArgs\>(Action\<EventHandler\<TEventArgs\>\>, Action\<EventHandler\<TEventArgs\>\>)

Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence with the specified add handler and remove handler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function FromEventPattern(Of TEventArgs As EventArgs) ( _
    addHandler As Action(Of EventHandler(Of TEventArgs)), _
    removeHandler As Action(Of EventHandler(Of TEventArgs)) _
) As IObservable(Of EventPattern(Of TEventArgs))
```

```vb
'Usage
Dim addHandler As Action(Of EventHandler(Of TEventArgs))
Dim removeHandler As Action(Of EventHandler(Of TEventArgs))
Dim returnValue As IObservable(Of EventPattern(Of TEventArgs))

returnValue = Observable.FromEventPattern(addHandler, _
    removeHandler)
```

```csharp
public static IObservable<EventPattern<TEventArgs>> FromEventPattern<TEventArgs>(
    Action<EventHandler<TEventArgs>> addHandler,
    Action<EventHandler<TEventArgs>> removeHandler
)
where TEventArgs : EventArgs
```

```c++
public:
generic<typename TEventArgs>
where TEventArgs : EventArgs
static IObservable<EventPattern<TEventArgs>^>^ FromEventPattern(
    Action<EventHandler<TEventArgs>^>^ addHandler, 
    Action<EventHandler<TEventArgs>^>^ removeHandler
)
```

```fsharp
static member FromEventPattern : 
        addHandler:Action<EventHandler<'TEventArgs>> * 
        removeHandler:Action<EventHandler<'TEventArgs>> -> IObservable<EventPattern<'TEventArgs>>  when 'TEventArgs : EventArgs
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TEventArgs  
  The type of event.

#### Parameters

- addHandler  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[EventHandler](https://msdn.microsoft.com/en-us/library/db0etb8x)\<TEventArgs\>\>  
  The action that attaches the given event handler to the underlying .NET event.

- removeHandler  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[EventHandler](https://msdn.microsoft.com/en-us/library/db0etb8x)\<TEventArgs\>\>  
  The action that detaches the given event handler from the underlying .NET event.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<TEventArgs\>\>  
The observable sequence that contains data representations of invocations of the underlying .NET event.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# FromEventPattern\<TEventArgs\>(Type, String)

Converts a .NET event, conforming to the standard .NET event pattern, to an observable sequence, using reflection to find a static event.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function FromEventPattern(Of TEventArgs As EventArgs) ( _
    type As Type, _
    eventName As String _
) As IObservable(Of EventPattern(Of TEventArgs))
```

```vb
'Usage
Dim type As Type
Dim eventName As String
Dim returnValue As IObservable(Of EventPattern(Of TEventArgs))

returnValue = Observable.FromEventPattern(type, _
    eventName)
```

```csharp
public static IObservable<EventPattern<TEventArgs>> FromEventPattern<TEventArgs>(
    Type type,
    string eventName
)
where TEventArgs : EventArgs
```

```c++
public:
generic<typename TEventArgs>
where TEventArgs : EventArgs
static IObservable<EventPattern<TEventArgs>^>^ FromEventPattern(
    Type^ type, 
    String^ eventName
)
```

```fsharp
static member FromEventPattern : 
        type:Type * 
        eventName:string -> IObservable<EventPattern<'TEventArgs>>  when 'TEventArgs : EventArgs
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TEventArgs  
  The type of event.

#### Parameters

- type  
  Type: [System.Type](https://msdn.microsoft.com/en-us/library/42892f65)  
  The type that exposes the static event to convert.

- eventName  
  Type: [System.String](https://msdn.microsoft.com/en-us/library/s1wwdcbf)  
  The name of the event to convert.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[EventPattern](EventPattern/EventPattern(TEventArgs))\<TEventArgs\>\>  
The observable sequence that contains data representations of invocations of the underlying .NET event.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
