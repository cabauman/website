title: Constructors
---
# Recorded\<T\> Constructor

Initializes a new instance of the [Recorded\<T\>](Recorded/Recorded(T)) class with the specified value at the given virtual time.

**Namespace:**  [Microsoft.Reactive.Testing](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)  
**Assembly:**  Microsoft.Reactive.Testing (in Microsoft.Reactive.Testing.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    time As Long, _
    value As T _
)
```

```vb
'Usage
Dim time As Long
Dim value As T

Dim instance As New Recorded(time, value)
```

```csharp
public Recorded(
    long time,
    T value
)
```

```c++
public:
Recorded(
    long long time, 
    T value
)
```

```fsharp
new : 
        time:int64 * 
        value:'T -> Recorded
```

```jscript
public function Recorded(
    time : long, 
    value : T
)
```

#### Parameters

- time  
  Type: [System.Int64](https://msdn.microsoft.com/en-us/library/6yy583ek)  
  Virtual time the value was produced on.

- value  
  Type: [T](Recorded/Recorded(T))  
  Value that was produced.

## See Also

#### Reference

[Recorded\<T\> Structure](Recorded/Recorded(T))

[Microsoft.Reactive.Testing Namespace](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)
