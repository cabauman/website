title: Constructors
---
# VirtualTimeSchedulerBase\<TAbsolute, TRelative\> Constructors

Initializes a new instance of the [VirtualTimeSchedulerBase\<TAbsolute, TRelative\>](VirtualTimeSchedulerBase/VirtualTimeSchedulerBase(TAbsolute,) class.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Protected method](https://reactiveui.net/assets/img/Hh303103.protmethod(en-us,VS.103).gif "Protected method")[VirtualTimeSchedulerBase<TAbsolute, TRelative>()](VirtualTimeSchedulerBase/VirtualTimeSchedulerBase(TAbsolute,)Creates a new virtual time scheduler with the default value of TAbsolute for the initial clock value.![Protected method](https://reactiveui.net/assets/img/Hh303103.protmethod(en-us,VS.103).gif "Protected method")[VirtualTimeSchedulerBase<TAbsolute, TRelative>(TAbsolute, IComparer<TAbsolute>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.concurrency.virtualtimeschedulerbase%602.#ctor(%600%2csystem.collections.generic.icomparer%7b%600%7d)(v=VS.103))Creates a new virtual time scheduler.Top

## See Also

#### Reference

[VirtualTimeSchedulerBase\<TAbsolute, TRelative\> Class](VirtualTimeSchedulerBase/VirtualTimeSchedulerBase(TAbsolute,)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)



<br />

# VirtualTimeSchedulerBase\<TAbsolute, TRelative\>()

Creates a new virtual time scheduler with the default value of TAbsolute for the initial clock value.

**Namespace:**  [System.Reactive.Concurrency](System.Reactive.Concurrency/System.Reactive.Concurrency)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Protected Sub New
```

```vb
'Usage

Dim instance As New VirtualTimeSchedulerBase()
```

```csharp
protected VirtualTimeSchedulerBase()
```

```c++
protected:
VirtualTimeSchedulerBase()
```

```fsharp
new : unit -> VirtualTimeSchedulerBase
```

```jscript
protected function VirtualTimeSchedulerBase()
```

## See Also

#### Reference

[VirtualTimeSchedulerBase\<TAbsolute, TRelative\> Class](VirtualTimeSchedulerBase/VirtualTimeSchedulerBase(TAbsolute,)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)



<br />

# VirtualTimeSchedulerBase\<TAbsolute, TRelative\>(TAbsolute, IComparer\<TAbsolute\>)

Creates a new virtual time scheduler.

**Namespace:**  [System.Reactive.Concurrency](System.Reactive.Concurrency/System.Reactive.Concurrency)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Protected Sub New ( _
    initialClock As TAbsolute, _
    comparer As IComparer(Of TAbsolute) _
)
```

```vb
'Usage
Dim initialClock As TAbsolute
Dim comparer As IComparer(Of TAbsolute)

Dim instance As New VirtualTimeSchedulerBase(initialClock, _
    comparer)
```

```csharp
protected VirtualTimeSchedulerBase(
    TAbsolute initialClock,
    IComparer<TAbsolute> comparer
)
```

```c++
protected:
VirtualTimeSchedulerBase(
    TAbsolute initialClock, 
    IComparer<TAbsolute>^ comparer
)
```

```fsharp
new : 
        initialClock:'TAbsolute * 
        comparer:IComparer<'TAbsolute> -> VirtualTimeSchedulerBase
```

```jscript
protected function VirtualTimeSchedulerBase(
    initialClock : TAbsolute, 
    comparer : IComparer<TAbsolute>
)
```

#### Parameters

- initialClock  
  Type: [TAbsolute](VirtualTimeSchedulerBase/VirtualTimeSchedulerBase(TAbsolute,)  
  The initial value for the clock.

- comparer  
  Type: [System.Collections.Generic.IComparer](https://msdn.microsoft.com/en-us/library/8ehhxeaf)\<[TAbsolute](VirtualTimeSchedulerBase/VirtualTimeSchedulerBase(TAbsolute,)\>  
  The comparer to determine causality of events based on absolute time.

## See Also

#### Reference

[VirtualTimeSchedulerBase\<TAbsolute, TRelative\> Class](VirtualTimeSchedulerBase/VirtualTimeSchedulerBase(TAbsolute,)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)
