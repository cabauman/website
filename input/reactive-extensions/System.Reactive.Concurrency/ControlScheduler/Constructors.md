title: Constructors
---
# ControlScheduler Constructor

Constructs a ControlScheduler that schedules units of work on the message loop associated with the specified Windows Forms control.

**Namespace:**  [System.Reactive.Concurrency](System.Reactive.Concurrency/System.Reactive.Concurrency)  
**Assembly:**  System.Reactive.Windows.Forms (in System.Reactive.Windows.Forms.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    control As Control _
)
```

```vb
'Usage
Dim control As Control

Dim instance As New ControlScheduler(control)
```

```csharp
public ControlScheduler(
    Control control
)
```

```c++
public:
ControlScheduler(
    Control^ control
)
```

```fsharp
new : 
        control:Control -> ControlScheduler
```

```jscript
public function ControlScheduler(
    control : Control
)
```

#### Parameters

- control  
  Type: [System.Windows.Forms.Control](https://msdn.microsoft.com/en-us/library/36cd312w)  
  The Windows Forms control to get the message loop from.

## See Also

#### Reference

[ControlScheduler Class](ControlScheduler/ControlScheduler)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)
