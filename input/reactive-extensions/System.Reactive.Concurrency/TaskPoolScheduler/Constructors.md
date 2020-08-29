title: Constructors
---
# TaskPoolScheduler Constructor

Creates an object that schedules units of work using the provided TaskFactory.

**Namespace:**  [System.Reactive.Concurrency](System.Reactive.Concurrency/System.Reactive.Concurrency)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    taskFactory As TaskFactory _
)
```

```vb
'Usage
Dim taskFactory As TaskFactory

Dim instance As New TaskPoolScheduler(taskFactory)
```

```csharp
public TaskPoolScheduler(
    TaskFactory taskFactory
)
```

```c++
public:
TaskPoolScheduler(
    TaskFactory^ taskFactory
)
```

```fsharp
new : 
        taskFactory:TaskFactory -> TaskPoolScheduler
```

```jscript
public function TaskPoolScheduler(
    taskFactory : TaskFactory
)
```

#### Parameters

- taskFactory  
  Type: [System.Threading.Tasks.TaskFactory](https://msdn.microsoft.com/en-us/library/Dd321401)  
  The task factory used to create tasks to run units of work.

## See Also

#### Reference

[TaskPoolScheduler Class](TaskPoolScheduler/TaskPoolScheduler)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)
