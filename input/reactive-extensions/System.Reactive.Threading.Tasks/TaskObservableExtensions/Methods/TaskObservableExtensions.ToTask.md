title: ToTask
---
# TaskObservableExtensions.ToTask Method

Returns a task that contains the last value of the observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[ToTask<TResult>(IObservable<TResult>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.threading.tasks.taskobservableextensions.totask%60%601(system.iobservable%7b%60%600%7d)(v=VS.103))Returns a task that contains the last value of the observable sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[ToTask<TResult>(IObservable<TResult>, Object)](https://msdn.microsoft.com/en-us/library/m:system.reactive.threading.tasks.taskobservableextensions.totask%60%601(system.iobservable%7b%60%600%7d%2csystem.object)(v=VS.103))Returns a task that contains the last value of the observable sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[ToTask<TResult>(IObservable<TResult>, CancellationToken)](https://msdn.microsoft.com/en-us/library/m:system.reactive.threading.tasks.taskobservableextensions.totask%60%601(system.iobservable%7b%60%600%7d%2csystem.threading.cancellationtoken)(v=VS.103))Returns a task that contains the last value of the observable sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[ToTask<TResult>(IObservable<TResult>, CancellationToken, Object)](https://msdn.microsoft.com/en-us/library/m:system.reactive.threading.tasks.taskobservableextensions.totask%60%601(system.iobservable%7b%60%600%7d%2csystem.threading.cancellationtoken%2csystem.object)(v=VS.103))Returns a task that contains the last value of the observable sequence.Top

## See Also

#### Reference

[TaskObservableExtensions Class](TaskObservableExtensions/TaskObservableExtensions)

[System.Reactive.Threading.Tasks Namespace](System.Reactive.Threading.Tasks/System.Reactive.Threading.Tasks)



<br />

# ToTask\<TResult\>(IObservable\<TResult\>, CancellationToken)

Returns a task that contains the last value of the observable sequence.

**Namespace:**  [System.Reactive.Threading.Tasks](System.Reactive.Threading.Tasks/System.Reactive.Threading.Tasks)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ToTask(Of TResult) ( _
    observable As IObservable(Of TResult), _
    cancellationToken As CancellationToken _
) As Task(Of TResult)
```

```vb
'Usage
Dim observable As IObservable(Of TResult)
Dim cancellationToken As CancellationToken
Dim returnValue As Task(Of TResult)

returnValue = observable.ToTask(cancellationToken)
```

```csharp
public static Task<TResult> ToTask<TResult>(
    this IObservable<TResult> observable,
    CancellationToken cancellationToken
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TResult>
static Task<TResult>^ ToTask(
    IObservable<TResult>^ observable, 
    CancellationToken cancellationToken
)
```

```fsharp
static member ToTask : 
        observable:IObservable<'TResult> * 
        cancellationToken:CancellationToken -> Task<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The type of result.

#### Parameters

- observable  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
  The observable sequence to convert to a task.

- cancellationToken  
  Type: [System.Threading.CancellationToken](https://msdn.microsoft.com/en-us/library/Dd384802)  
  Cancellation token that can be used to cancel the task, causing unsubscription from the observable sequence.

#### Return Value

Type: [System.Threading.Tasks.Task](https://msdn.microsoft.com/en-us/library/Dd321424)\<TResult\>  
A task that contains the last value of the observable sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[TaskObservableExtensions Class](TaskObservableExtensions/TaskObservableExtensions)

[System.Reactive.Threading.Tasks Namespace](System.Reactive.Threading.Tasks/System.Reactive.Threading.Tasks)



<br />

# ToTask\<TResult\>(IObservable\<TResult\>)

Returns a task that contains the last value of the observable sequence.

**Namespace:**  [System.Reactive.Threading.Tasks](System.Reactive.Threading.Tasks/System.Reactive.Threading.Tasks)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ToTask(Of TResult) ( _
    observable As IObservable(Of TResult) _
) As Task(Of TResult)
```

```vb
'Usage
Dim observable As IObservable(Of TResult)
Dim returnValue As Task(Of TResult)

returnValue = observable.ToTask()
```

```csharp
public static Task<TResult> ToTask<TResult>(
    this IObservable<TResult> observable
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TResult>
static Task<TResult>^ ToTask(
    IObservable<TResult>^ observable
)
```

```fsharp
static member ToTask : 
        observable:IObservable<'TResult> -> Task<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The type of result.

#### Parameters

- observable  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
  The observable sequence to convert to a task.

#### Return Value

Type: [System.Threading.Tasks.Task](https://msdn.microsoft.com/en-us/library/Dd321424)\<TResult\>  
A task that contains the last value of the observable sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[TaskObservableExtensions Class](TaskObservableExtensions/TaskObservableExtensions)

[System.Reactive.Threading.Tasks Namespace](System.Reactive.Threading.Tasks/System.Reactive.Threading.Tasks)



<br />

# ToTask\<TResult\>(IObservable\<TResult\>, CancellationToken, Object)

Returns a task that contains the last value of the observable sequence.

**Namespace:**  [System.Reactive.Threading.Tasks](System.Reactive.Threading.Tasks/System.Reactive.Threading.Tasks)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ToTask(Of TResult) ( _
    observable As IObservable(Of TResult), _
    cancellationToken As CancellationToken, _
    state As Object _
) As Task(Of TResult)
```

```vb
'Usage
Dim observable As IObservable(Of TResult)
Dim cancellationToken As CancellationToken
Dim state As Object
Dim returnValue As Task(Of TResult)

returnValue = observable.ToTask(cancellationToken, _
    state)
```

```csharp
public static Task<TResult> ToTask<TResult>(
    this IObservable<TResult> observable,
    CancellationToken cancellationToken,
    Object state
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TResult>
static Task<TResult>^ ToTask(
    IObservable<TResult>^ observable, 
    CancellationToken cancellationToken, 
    Object^ state
)
```

```fsharp
static member ToTask : 
        observable:IObservable<'TResult> * 
        cancellationToken:CancellationToken * 
        state:Object -> Task<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The type of result.

#### Parameters

- observable  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
  The observable sequence to convert to a task.

- cancellationToken  
  Type: [System.Threading.CancellationToken](https://msdn.microsoft.com/en-us/library/Dd384802)  
  Cancellation token that can be used to cancel the task, causing unsubscription from the observable sequence.

- state  
  Type: [System.Object](https://msdn.microsoft.com/en-us/library/e5kfa45b)  
  The state to use as the underlying task's AsyncState.

#### Return Value

Type: [System.Threading.Tasks.Task](https://msdn.microsoft.com/en-us/library/Dd321424)\<TResult\>  
A task that contains the last value of the observable sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[TaskObservableExtensions Class](TaskObservableExtensions/TaskObservableExtensions)

[System.Reactive.Threading.Tasks Namespace](System.Reactive.Threading.Tasks/System.Reactive.Threading.Tasks)



<br />

# ToTask\<TResult\>(IObservable\<TResult\>, Object)

Returns a task that contains the last value of the observable sequence.

**Namespace:**  [System.Reactive.Threading.Tasks](System.Reactive.Threading.Tasks/System.Reactive.Threading.Tasks)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ToTask(Of TResult) ( _
    observable As IObservable(Of TResult), _
    state As Object _
) As Task(Of TResult)
```

```vb
'Usage
Dim observable As IObservable(Of TResult)
Dim state As Object
Dim returnValue As Task(Of TResult)

returnValue = observable.ToTask(state)
```

```csharp
public static Task<TResult> ToTask<TResult>(
    this IObservable<TResult> observable,
    Object state
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TResult>
static Task<TResult>^ ToTask(
    IObservable<TResult>^ observable, 
    Object^ state
)
```

```fsharp
static member ToTask : 
        observable:IObservable<'TResult> * 
        state:Object -> Task<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The type of result.

#### Parameters

- observable  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
  The observable sequence to convert to a task.

- state  
  Type: [System.Object](https://msdn.microsoft.com/en-us/library/e5kfa45b)  
  The state to use as the underlying task's AsyncState.

#### Return Value

Type: [System.Threading.Tasks.Task](https://msdn.microsoft.com/en-us/library/Dd321424)\<TResult\>  
A task that contains the last value of the observable sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[TaskObservableExtensions Class](TaskObservableExtensions/TaskObservableExtensions)

[System.Reactive.Threading.Tasks Namespace](System.Reactive.Threading.Tasks/System.Reactive.Threading.Tasks)
