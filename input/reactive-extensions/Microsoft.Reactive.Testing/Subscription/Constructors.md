title: Constructors
---
# Subscription Constructors

Initializes a new instance of the [Subscription](Subscription/Subscription) class with the default values.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Subscription(Int64)](https://msdn.microsoft.com/en-us/library/m:microsoft.reactive.testing.subscription.#ctor(system.int64)(v=VS.103))Initializes a new instance of the [Subscription](Subscription/Subscription) class with the specified virtual time the subscription occurred.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Subscription(Int64, Int64)](https://msdn.microsoft.com/en-us/library/m:microsoft.reactive.testing.subscription.#ctor(system.int64%2csystem.int64)(v=VS.103))Initializes a new instance of the [Subscription](Subscription/Subscription) class with the specified virtual time the subscription and unsubscription occurred.

## See Also

#### Reference

[Subscription Structure](Subscription/Subscription)

[Microsoft.Reactive.Testing Namespace](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)



<br />

# Subscription Constructor (Int64)

Initializes a new instance of the [Subscription](Subscription/Subscription) class with the specified virtual time the subscription occurred.

**Namespace:**  [Microsoft.Reactive.Testing](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)  
**Assembly:**  Microsoft.Reactive.Testing (in Microsoft.Reactive.Testing.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    subscribe As Long _
)
```

```vb
'Usage
Dim subscribe As Long

Dim instance As New Subscription(subscribe)
```

```csharp
public Subscription(
    long subscribe
)
```

```c++
public:
Subscription(
    long long subscribe
)
```

```fsharp
new : 
        subscribe:int64 -> Subscription
```

```jscript
public function Subscription(
    subscribe : long
)
```

#### Parameters

- subscribe  
  Type: [System.Int64](https://msdn.microsoft.com/en-us/library/6yy583ek)  
  The virtual time at which the subscription occurred.

## See Also

#### Reference

[Subscription Structure](Subscription/Subscription)

[Subscription Overload](Subscription/Subscription)

[Microsoft.Reactive.Testing Namespace](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)



<br />

# Subscription Constructor (Int64, Int64)

Initializes a new instance of the [Subscription](Subscription/Subscription) class with the specified virtual time the subscription and unsubscription occurred.

**Namespace:**  [Microsoft.Reactive.Testing](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)  
**Assembly:**  Microsoft.Reactive.Testing (in Microsoft.Reactive.Testing.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    subscribe As Long, _
    unsubscribe As Long _
)
```

```vb
'Usage
Dim subscribe As Long
Dim unsubscribe As Long

Dim instance As New Subscription(subscribe, _
    unsubscribe)
```

```csharp
public Subscription(
    long subscribe,
    long unsubscribe
)
```

```c++
public:
Subscription(
    long long subscribe, 
    long long unsubscribe
)
```

```fsharp
new : 
        subscribe:int64 * 
        unsubscribe:int64 -> Subscription
```

```jscript
public function Subscription(
    subscribe : long, 
    unsubscribe : long
)
```

#### Parameters

- subscribe  
  Type: [System.Int64](https://msdn.microsoft.com/en-us/library/6yy583ek)  
  The virtual time at which the subscription occurred.

- unsubscribe  
  Type: [System.Int64](https://msdn.microsoft.com/en-us/library/6yy583ek)  
  The virtual time at which the unsubscription occurred.

## See Also

#### Reference

[Subscription Structure](Subscription/Subscription)

[Subscription Overload](Subscription/Subscription)

[Microsoft.Reactive.Testing Namespace](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)
