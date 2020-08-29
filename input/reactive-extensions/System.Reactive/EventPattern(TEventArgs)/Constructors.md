title: Constructors
---
# EventPattern\<TEventArgs\> Constructor

Initialize a new instance of the [EventPattern\<TEventArgs\>](EventPattern/EventPattern(TEventArgs)) type.

**Namespace:**  [System.Reactive](System.Reactive/System.Reactive)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    sender As Object, _
    e As TEventArgs _
)
```

```vb
'Usage
Dim sender As Object
Dim e As TEventArgs

Dim instance As New EventPattern(sender, _
    e)
```

```csharp
public EventPattern(
    Object sender,
    TEventArgs e
)
```

```c++
public:
EventPattern(
    Object^ sender, 
    TEventArgs e
)
```

```fsharp
new : 
        sender:Object * 
        e:'TEventArgs -> EventPattern
```

```jscript
public function EventPattern(
    sender : Object, 
    e : TEventArgs
)
```

#### Parameters

- sender  
  Type: [System.Object](https://msdn.microsoft.com/en-us/library/e5kfa45b)  
  The event sender information.

- e  
  Type: [TEventArgs](EventPattern/EventPattern(TEventArgs))  
  Event arguments.

## See Also

#### Reference

[EventPattern\<TEventArgs\> Class](EventPattern/EventPattern(TEventArgs))

[System.Reactive Namespace](System.Reactive/System.Reactive)
