title: Constructors
---
# TimeInterval\<T\> Constructor

Constructs a timestamped value.

**Namespace:**  [System.Reactive](System.Reactive/System.Reactive)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    value As T, _
    interval As TimeSpan _
)
```

```vb
'Usage
Dim value As T
Dim interval As TimeSpan

Dim instance As New TimeInterval(value, interval)
```

```csharp
public TimeInterval(
    T value,
    TimeSpan interval
)
```

```c++
public:
TimeInterval(
    T value, 
    TimeSpan interval
)
```

```fsharp
new : 
        value:'T * 
        interval:TimeSpan -> TimeInterval
```

```jscript
public function TimeInterval(
    value : T, 
    interval : TimeSpan
)
```

#### Parameters

- value  
  Type: [T](TimeInterval/TimeInterval(T))  
  The value.

- interval  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The interval.

## See Also

#### Reference

[TimeInterval\<T\> Structure](TimeInterval/TimeInterval(T))

[System.Reactive Namespace](System.Reactive/System.Reactive)
