title: Constructors
---
# Timestamped\<T\> Constructor

Constructs a timestamped value.

**Namespace:**  [System.Reactive](System.Reactive/System.Reactive)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    value As T, _
    timestamp As DateTimeOffset _
)
```

```vb
'Usage
Dim value As T
Dim timestamp As DateTimeOffset

Dim instance As New Timestamped(value, timestamp)
```

```csharp
public Timestamped(
    T value,
    DateTimeOffset timestamp
)
```

```c++
public:
Timestamped(
    T value, 
    DateTimeOffset timestamp
)
```

```fsharp
new : 
        value:'T * 
        timestamp:DateTimeOffset -> Timestamped
```

```jscript
public function Timestamped(
    value : T, 
    timestamp : DateTimeOffset
)
```

#### Parameters

- value  
  Type: [T](Timestamped/Timestamped(T))  
  The value.

- timestamp  
  Type: [System.DateTimeOffset](https://msdn.microsoft.com/en-us/library/Bb341783)  
  The timestamp.

## See Also

#### Reference

[Timestamped\<T\> Structure](Timestamped/Timestamped(T))

[System.Reactive Namespace](System.Reactive/System.Reactive)
