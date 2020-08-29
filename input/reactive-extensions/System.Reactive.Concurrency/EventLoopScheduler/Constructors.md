title: Constructors
---
# EventLoopScheduler Constructors

Initializes a new instance of the [EventLoopScheduler](EventLoopScheduler/EventLoopScheduler) class.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[EventLoopScheduler()](EventLoopScheduler/EventLoopScheduler)Creates an object that schedules units of work on a designated thread.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[EventLoopScheduler(Func<ThreadStart, Thread>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.concurrency.eventloopscheduler.#ctor(system.func%7bsystem.threading.threadstart%2csystem.threading.thread%7d)(v=VS.103))Creates an object that schedules units of work on a designated thread.Top

## See Also

#### Reference

[EventLoopScheduler Class](EventLoopScheduler/EventLoopScheduler)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)



<br />

# EventLoopScheduler()

Creates an object that schedules units of work on a designated thread.

**Namespace:**  [System.Reactive.Concurrency](System.Reactive.Concurrency/System.Reactive.Concurrency)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New
```

```vb
'Usage

Dim instance As New EventLoopScheduler()
```

```csharp
public EventLoopScheduler()
```

```c++
public:
EventLoopScheduler()
```

```fsharp
new : unit -> EventLoopScheduler
```

```jscript
public function EventLoopScheduler()
```

## See Also

#### Reference

[EventLoopScheduler Class](EventLoopScheduler/EventLoopScheduler)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)



<br />

# EventLoopScheduler(Func\<ThreadStart, Thread\>)

Creates an object that schedules units of work on a designated thread.

**Namespace:**  [System.Reactive.Concurrency](System.Reactive.Concurrency/System.Reactive.Concurrency)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    threadFactory As Func(Of ThreadStart, Thread) _
)
```

```vb
'Usage
Dim threadFactory As Func(Of ThreadStart, Thread)

Dim instance As New EventLoopScheduler(threadFactory)
```

```csharp
public EventLoopScheduler(
    Func<ThreadStart, Thread> threadFactory
)
```

```c++
public:
EventLoopScheduler(
    Func<ThreadStart^, Thread^>^ threadFactory
)
```

```fsharp
new : 
        threadFactory:Func<ThreadStart, Thread> -> EventLoopScheduler
```

```jscript
public function EventLoopScheduler(
    threadFactory : Func<ThreadStart, Thread>
)
```

#### Parameters

- threadFactory  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[ThreadStart](https://msdn.microsoft.com/en-us/library/57s77029), [Thread](https://msdn.microsoft.com/en-us/library/bkb1k2x8)\>  
  The factory function for thread creation.

## See Also

#### Reference

[EventLoopScheduler Class](EventLoopScheduler/EventLoopScheduler)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)
