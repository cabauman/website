title: Constructors
---
# NewThreadScheduler Constructors

Initializes a new instance of the [NewThreadScheduler](NewThreadScheduler/NewThreadScheduler) class.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[NewThreadScheduler()](NewThreadScheduler/NewThreadScheduler)Creates an object that schedules each unit of work on a separate thread.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[NewThreadScheduler(Func<ThreadStart, Thread>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.concurrency.newthreadscheduler.#ctor(system.func%7bsystem.threading.threadstart%2csystem.threading.thread%7d)(v=VS.103))Creates an object that schedules each unit of work on a separate thread.Top

## See Also

#### Reference

[NewThreadScheduler Class](NewThreadScheduler/NewThreadScheduler)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)



<br />

# NewThreadScheduler()

Creates an object that schedules each unit of work on a separate thread.

**Namespace:**  [System.Reactive.Concurrency](System.Reactive.Concurrency/System.Reactive.Concurrency)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New
```

```vb
'Usage

Dim instance As New NewThreadScheduler()
```

```csharp
public NewThreadScheduler()
```

```c++
public:
NewThreadScheduler()
```

```fsharp
new : unit -> NewThreadScheduler
```

```jscript
public function NewThreadScheduler()
```

## See Also

#### Reference

[NewThreadScheduler Class](NewThreadScheduler/NewThreadScheduler)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)



<br />

# NewThreadScheduler(Func\<ThreadStart, Thread\>)

Creates an object that schedules each unit of work on a separate thread.

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

Dim instance As New NewThreadScheduler(threadFactory)
```

```csharp
public NewThreadScheduler(
    Func<ThreadStart, Thread> threadFactory
)
```

```c++
public:
NewThreadScheduler(
    Func<ThreadStart^, Thread^>^ threadFactory
)
```

```fsharp
new : 
        threadFactory:Func<ThreadStart, Thread> -> NewThreadScheduler
```

```jscript
public function NewThreadScheduler(
    threadFactory : Func<ThreadStart, Thread>
)
```

#### Parameters

- threadFactory  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[ThreadStart](https://msdn.microsoft.com/en-us/library/57s77029), [Thread](https://msdn.microsoft.com/en-us/library/bkb1k2x8)\>  
  The factory function for thread creation.

## See Also

#### Reference

[NewThreadScheduler Class](NewThreadScheduler/NewThreadScheduler)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)
