title: ScheduleAbsolute
---
# HistoricalScheduler.ScheduleAbsolute Method

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[ScheduleAbsolute<TState>(TState, DateTimeOffset, Func<IScheduler, TState, IDisposable>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.concurrency.historicalscheduler.scheduleabsolute%60%601(%60%600%2csystem.datetimeoffset%2csystem.func%7bsystem.reactive.concurrency.ischeduler%2c%60%600%2csystem.idisposable%7d)(v=VS.103))Schedules an action to be executed at dueTime. (Overrides [VirtualTimeSchedulerBase<TAbsolute, TRelative>.ScheduleAbsolute<TState>(TState, TAbsolute, Func<IScheduler, TState, IDisposable>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.concurrency.virtualtimeschedulerbase%602.scheduleabsolute%60%601(%60%600%2c%600%2csystem.func%7bsystem.reactive.concurrency.ischeduler%2c%60%600%2csystem.idisposable%7d)(v=VS.103)).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[ScheduleAbsolute<TState>(TState, TAbsolute, Func<IScheduler, TState, IDisposable>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.concurrency.virtualtimeschedulerbase%602.scheduleabsolute%60%601(%60%600%2c%600%2csystem.func%7bsystem.reactive.concurrency.ischeduler%2c%60%600%2csystem.idisposable%7d)(v=VS.103))Schedules an action to be executed at dueTime. (Inherited from [VirtualTimeSchedulerBase<TAbsolute, TRelative>](VirtualTimeSchedulerBase/VirtualTimeSchedulerBase(TAbsolute,).)Top

## See Also

#### Reference

[HistoricalScheduler Class](HistoricalScheduler/HistoricalScheduler)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)



<br />

# ScheduleAbsolute\<TState\>(TState, DateTimeOffset, Func\<IScheduler, TState, IDisposable\>)

Schedules an action to be executed at dueTime.

**Namespace:**  [System.Reactive.Concurrency](System.Reactive.Concurrency/System.Reactive.Concurrency)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Overrides Function ScheduleAbsolute(Of TState) ( _
    state As TState, _
    dueTime As DateTimeOffset, _
    action As Func(Of IScheduler, TState, IDisposable) _
) As IDisposable
```

```vb
'Usage
Dim instance As HistoricalScheduler
Dim state As TState
Dim dueTime As DateTimeOffset
Dim action As Func(Of IScheduler, TState, IDisposable)
Dim returnValue As IDisposable

returnValue = instance.ScheduleAbsolute(state, _
    dueTime, action)
```

```csharp
public override IDisposable ScheduleAbsolute<TState>(
    TState state,
    DateTimeOffset dueTime,
    Func<IScheduler, TState, IDisposable> action
)
```

```c++
public:
generic<typename TState>
virtual IDisposable^ ScheduleAbsolute(
    TState state, 
    DateTimeOffset dueTime, 
    Func<IScheduler^, TState, IDisposable^>^ action
) override
```

```fsharp
abstract ScheduleAbsolute : 
        state:'TState * 
        dueTime:DateTimeOffset * 
        action:Func<IScheduler, 'TState, IDisposable> -> IDisposable 
override ScheduleAbsolute : 
        state:'TState * 
        dueTime:DateTimeOffset * 
        action:Func<IScheduler, 'TState, IDisposable> -> IDisposable 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TState  
  The state argument type.

#### Parameters

- state  
  Type: TState  
  State passed to the action to be executed.

- dueTime  
  Type: [System.DateTimeOffset](https://msdn.microsoft.com/en-us/library/Bb341783)  
  Absolute time at which to execute the action.

- action  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb534647)\<[IScheduler](IScheduler/IScheduler), TState, [IDisposable](https://msdn.microsoft.com/en-us/library/aax125c9)\>  
  Action to be executed.

#### Return Value

Type: [System.IDisposable](https://msdn.microsoft.com/en-us/library/aax125c9)  
Disposable object used to cancel the scheduled action (best effort).

## See Also

#### Reference

[HistoricalScheduler Class](HistoricalScheduler/HistoricalScheduler)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)
