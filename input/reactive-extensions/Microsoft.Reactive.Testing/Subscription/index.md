title: Subscription
---
# Subscription Structure

Records the information about subscripts to and unsubscriptions from observable sequences.

**Namespace:**  [Microsoft.Reactive.Testing](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)  
**Assembly:**  Microsoft.Reactive.Testing (in Microsoft.Reactive.Testing.dll)

## Syntax

```vb
'Declaration
<SerializableAttribute> _
Public Structure Subscription _
    Implements IEquatable(Of Subscription)
```

```vb
'Usage
Dim instance As Subscription
```

```csharp
[SerializableAttribute]
public struct Subscription : IEquatable<Subscription>
```

```c++
[SerializableAttribute]
public value class Subscription : IEquatable<Subscription>
```

```fsharp
[<SealedAttribute>]
[<SerializableAttribute>]
type Subscription =  
    struct
        interface IEquatable<Subscription>
    end
```

```jscript
JScript suports the use of structures, but not the declaration of new ones.
```

The Subscription type exposes the following members.

## Constructors

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Subscription(Int64)](https://msdn.microsoft.com/en-us/library/m:microsoft.reactive.testing.subscription.#ctor(system.int64)(v=VS.103))Initializes a new instance of the Subscription class with the specified virtual time the subscription occurred.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Subscription(Int64, Int64)](https://msdn.microsoft.com/en-us/library/m:microsoft.reactive.testing.subscription.#ctor(system.int64%2csystem.int64)(v=VS.103))Initializes a new instance of the Subscription class with the specified virtual time the subscription and unsubscription occurred.

## Properties

NameDescription![Public property](https://reactiveui.net/assets/img/Hh211972.pubproperty(en-us,VS.103).gif "Public property")[Subscribe](Subscribe/Subscription.Subscribe)Gets the subscription virtual time.![Public property](https://reactiveui.net/assets/img/Hh211972.pubproperty(en-us,VS.103).gif "Public property")[Unsubscribe](Unsubscribe/Subscription.Unsubscribe)Gets the unsubscription virtual time.

## Methods

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Equals(Object)](https://msdn.microsoft.com/en-us/library/m:microsoft.reactive.testing.subscription.equals(system.object)(v=VS.103))Checks whether the given object is equal to the current instance. (Overrides [ValueType.Equals(Object)](https://msdn.microsoft.com/en-us/library/m:system.valuetype.equals(system.object)(v=VS.103)).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Equals(Subscription)](https://msdn.microsoft.com/en-us/library/m:microsoft.reactive.testing.subscription.equals(microsoft.reactive.testing.subscription)(v=VS.103))Checks whether the given subscription is equal to the current instance.![Protected method](https://reactiveui.net/assets/img/Hh303103.protmethod(en-us,VS.103).gif "Protected method")[Finalize](https://msdn.microsoft.com/en-us/library/4k87zsw7)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[GetHashCode](GetHashCode/Subscription.GetHashCode)Computes a hash code for the current instance. (Overrides [ValueType.GetHashCode()](https://msdn.microsoft.com/en-us/library/y3509fc2).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[GetType](https://msdn.microsoft.com/en-us/library/dfwy45w9)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Protected method](https://reactiveui.net/assets/img/Hh303103.protmethod(en-us,VS.103).gif "Protected method")[MemberwiseClone](https://msdn.microsoft.com/en-us/library/57ctke0a)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[ToString](ToString/Subscription.ToString)Returns a friendly string representation of the current instance. (Overrides [ValueType.ToString()](https://msdn.microsoft.com/en-us/library/wb77sz3h).)

## Operators

NameDescription![Public operator](https://reactiveui.net/assets/img/Hh229204.puboperator(en-us,VS.103).gif "Public operator")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Equality](https://msdn.microsoft.com/en-us/library/m:microsoft.reactive.testing.subscription.op_equality(microsoft.reactive.testing.subscription%2cmicrosoft.reactive.testing.subscription)(v=VS.103))Checks whether the two given subscription objects are equal.![Public operator](https://reactiveui.net/assets/img/Hh229204.puboperator(en-us,VS.103).gif "Public operator")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Inequality](https://msdn.microsoft.com/en-us/library/m:microsoft.reactive.testing.subscription.op_inequality(microsoft.reactive.testing.subscription%2cmicrosoft.reactive.testing.subscription)(v=VS.103))Checks whether the two given subscription objects are not equal.

## Fields

NameDescription![Public field](https://reactiveui.net/assets/img/Hh314728.pubfield(en-us,VS.103).gif "Public field")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Infinite](Infinite/Subscription.Infinite)Specifies the infinite virtual time value.

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Reactive.Testing Namespace](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)
