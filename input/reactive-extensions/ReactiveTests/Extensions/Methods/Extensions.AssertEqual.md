title: AssertEqual
---
# Extensions.AssertEqual Method

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[AssertEqual<T>(IEnumerable<T>, IEnumerable<T>)](https://msdn.microsoft.com/en-us/library/m:reactivetests.extensions.assertequal%60%601(system.collections.generic.ienumerable%7b%60%600%7d%2csystem.collections.generic.ienumerable%7b%60%600%7d)(v=VS.103))![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[AssertEqual<T>(IEnumerable<T>, array<T[])](https://msdn.microsoft.com/en-us/library/m:reactivetests.extensions.assertequal%60%601(system.collections.generic.ienumerable%7b%60%600%7d%2c%60%600%5b%5d)(v=VS.103))![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[AssertEqual<T>(IObservable<T>, IObservable<T>)](https://msdn.microsoft.com/en-us/library/m:reactivetests.extensions.assertequal%60%601(system.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%600%7d)(v=VS.103))Top

## See Also

#### Reference

[Extensions Class](Extensions/Extensions)

[ReactiveTests Namespace](ReactiveTests/ReactiveTests)



<br />

# AssertEqual\<T\>(IEnumerable\<T\>, array\<T\[\])

**Namespace:**  [ReactiveTests](ReactiveTests/ReactiveTests)  
**Assembly:**  Tests.System.Reactive (in Tests.System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub AssertEqual(Of T) ( _
    actual As IEnumerable(Of T), _
    ParamArray expected As T() _
)
```

```vb
'Usage
Dim actual As IEnumerable(Of T)
Dim expected As T()

actual.AssertEqual(expected)
```

```csharp
public static void AssertEqual<T>(
    this IEnumerable<T> actual,
    params T[] expected
)
```

```c++
[ExtensionAttribute]
public:
generic<typename T>
static void AssertEqual(
    IEnumerable<T>^ actual, 
    ... array<T>^ expected
)
```

```fsharp
static member AssertEqual : 
        actual:IEnumerable<'T> * 
        expected:'T[] -> unit 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T

#### Parameters

- actual  
  Type: [System.Collections.Generic.IEnumerable](https://msdn.microsoft.com/en-us/library/9eekhta0)\<T\>

- expected  
  Type: array\<T\[\]

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IEnumerable](https://msdn.microsoft.com/en-us/library/9eekhta0)\<T\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Extensions Class](Extensions/Extensions)

[ReactiveTests Namespace](ReactiveTests/ReactiveTests)



<br />

# AssertEqual\<T\>(IEnumerable\<T\>, IEnumerable\<T\>)

**Namespace:**  [ReactiveTests](ReactiveTests/ReactiveTests)  
**Assembly:**  Tests.System.Reactive (in Tests.System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub AssertEqual(Of T) ( _
    actual As IEnumerable(Of T), _
    expected As IEnumerable(Of T) _
)
```

```vb
'Usage
Dim actual As IEnumerable(Of T)
Dim expected As IEnumerable(Of T)

actual.AssertEqual(expected)
```

```csharp
public static void AssertEqual<T>(
    this IEnumerable<T> actual,
    IEnumerable<T> expected
)
```

```c++
[ExtensionAttribute]
public:
generic<typename T>
static void AssertEqual(
    IEnumerable<T>^ actual, 
    IEnumerable<T>^ expected
)
```

```fsharp
static member AssertEqual : 
        actual:IEnumerable<'T> * 
        expected:IEnumerable<'T> -> unit 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T

#### Parameters

- actual  
  Type: [System.Collections.Generic.IEnumerable](https://msdn.microsoft.com/en-us/library/9eekhta0)\<T\>

- expected  
  Type: [System.Collections.Generic.IEnumerable](https://msdn.microsoft.com/en-us/library/9eekhta0)\<T\>

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IEnumerable](https://msdn.microsoft.com/en-us/library/9eekhta0)\<T\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Extensions Class](Extensions/Extensions)

[ReactiveTests Namespace](ReactiveTests/ReactiveTests)



<br />

# AssertEqual\<T\>(IObservable\<T\>, IObservable\<T\>)

**Namespace:**  [ReactiveTests](ReactiveTests/ReactiveTests)  
**Assembly:**  Tests.System.Reactive (in Tests.System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub AssertEqual(Of T) ( _
    actual As IObservable(Of T), _
    expected As IObservable(Of T) _
)
```

```vb
'Usage
Dim actual As IObservable(Of T)
Dim expected As IObservable(Of T)

actual.AssertEqual(expected)
```

```csharp
public static void AssertEqual<T>(
    this IObservable<T> actual,
    IObservable<T> expected
)
```

```c++
[ExtensionAttribute]
public:
generic<typename T>
static void AssertEqual(
    IObservable<T>^ actual, 
    IObservable<T>^ expected
)
```

```fsharp
static member AssertEqual : 
        actual:IObservable<'T> * 
        expected:IObservable<'T> -> unit 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T

#### Parameters

- actual  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T\>

- expected  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T\>

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<T\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Extensions Class](Extensions/Extensions)

[ReactiveTests Namespace](ReactiveTests/ReactiveTests)
