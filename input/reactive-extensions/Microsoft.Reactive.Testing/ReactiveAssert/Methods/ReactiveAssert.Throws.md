title: Throws
---
# ReactiveAssert.Throws Method

Asserts that the given action throws an exception.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Throws<TException>(Action)](https://msdn.microsoft.com/en-us/library/m:microsoft.reactive.testing.reactiveassert.throws%60%601(system.action)(v=VS.103))Asserts that the given action throws an exception of the type specified in the generic parameter.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Throws<TException>(Action, String)](https://msdn.microsoft.com/en-us/library/m:microsoft.reactive.testing.reactiveassert.throws%60%601(system.action%2csystem.string)(v=VS.103))Asserts that the given action throws an exception of the type specified in the generic parameter.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Throws<TException>(TException, Action)](https://msdn.microsoft.com/en-us/library/m:microsoft.reactive.testing.reactiveassert.throws%60%601(%60%600%2csystem.action)(v=VS.103))![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Throws<TException>(TException, Action, String)](https://msdn.microsoft.com/en-us/library/m:microsoft.reactive.testing.reactiveassert.throws%60%601(%60%600%2csystem.action%2csystem.string)(v=VS.103))Top

## See Also

#### Reference

[ReactiveAssert Class](ReactiveAssert/ReactiveAssert)

[Microsoft.Reactive.Testing Namespace](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)



<br />

# Throws\<TException\>(TException, Action)

**Namespace:**  [Microsoft.Reactive.Testing](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)  
**Assembly:**  Microsoft.Reactive.Testing (in Microsoft.Reactive.Testing.dll)

## Syntax

```vb
'Declaration
Public Shared Sub Throws(Of TException As Exception) ( _
    exception As TException, _
    action As Action _
)
```

```vb
'Usage
Dim exception As TException
Dim action As Action

ReactiveAssert.Throws(exception, action)
```

```csharp
public static void Throws<TException>(
    TException exception,
    Action action
)
where TException : Exception
```

```c++
public:
generic<typename TException>
where TException : Exception
static void Throws(
    TException exception, 
    Action^ action
)
```

```fsharp
static member Throws : 
        exception:'TException * 
        action:Action -> unit  when 'TException : Exception
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TException

#### Parameters

- exception  
  Type: TException

- action  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/Bb534741)

## See Also

#### Reference

[ReactiveAssert Class](ReactiveAssert/ReactiveAssert)

[Microsoft.Reactive.Testing Namespace](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)



<br />

# Throws\<TException\>(TException, Action, String)

**Namespace:**  [Microsoft.Reactive.Testing](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)  
**Assembly:**  Microsoft.Reactive.Testing (in Microsoft.Reactive.Testing.dll)

## Syntax

```vb
'Declaration
Public Shared Sub Throws(Of TException As Exception) ( _
    exception As TException, _
    action As Action, _
    message As String _
)
```

```vb
'Usage
Dim exception As TException
Dim action As Action
Dim message As String

ReactiveAssert.Throws(exception, action, message)
```

```csharp
public static void Throws<TException>(
    TException exception,
    Action action,
    string message
)
where TException : Exception
```

```c++
public:
generic<typename TException>
where TException : Exception
static void Throws(
    TException exception, 
    Action^ action, 
    String^ message
)
```

```fsharp
static member Throws : 
        exception:'TException * 
        action:Action * 
        message:string -> unit  when 'TException : Exception
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TException

#### Parameters

- exception  
  Type: TException

- action  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/Bb534741)

- message  
  Type: [System.String](https://msdn.microsoft.com/en-us/library/s1wwdcbf)

## See Also

#### Reference

[ReactiveAssert Class](ReactiveAssert/ReactiveAssert)

[Microsoft.Reactive.Testing Namespace](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)



<br />

# Throws\<TException\>(Action)

Asserts that the given action throws an exception of the type specified in the generic parameter.

**Namespace:**  [Microsoft.Reactive.Testing](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)  
**Assembly:**  Microsoft.Reactive.Testing (in Microsoft.Reactive.Testing.dll)

## Syntax

```vb
'Declaration
Public Shared Sub Throws(Of TException As Exception) ( _
    action As Action _
)
```

```vb
'Usage
Dim action As Action

ReactiveAssert.Throws(action)
```

```csharp
public static void Throws<TException>(
    Action action
)
where TException : Exception
```

```c++
public:
generic<typename TException>
where TException : Exception
static void Throws(
    Action^ action
)
```

```fsharp
static member Throws : 
        action:Action -> unit  when 'TException : Exception
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TException  
  The type of the exception to check for.

#### Parameters

- action  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/Bb534741)  
  Action to run.

## See Also

#### Reference

[ReactiveAssert Class](ReactiveAssert/ReactiveAssert)

[Microsoft.Reactive.Testing Namespace](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)



<br />

# Throws\<TException\>(Action, String)

Asserts that the given action throws an exception of the type specified in the generic parameter.

**Namespace:**  [Microsoft.Reactive.Testing](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)  
**Assembly:**  Microsoft.Reactive.Testing (in Microsoft.Reactive.Testing.dll)

## Syntax

```vb
'Declaration
Public Shared Sub Throws(Of TException As Exception) ( _
    action As Action, _
    message As String _
)
```

```vb
'Usage
Dim action As Action
Dim message As String

ReactiveAssert.Throws(action, message)
```

```csharp
public static void Throws<TException>(
    Action action,
    string message
)
where TException : Exception
```

```c++
public:
generic<typename TException>
where TException : Exception
static void Throws(
    Action^ action, 
    String^ message
)
```

```fsharp
static member Throws : 
        action:Action * 
        message:string -> unit  when 'TException : Exception
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TException  
  The type of the exception to check for.

#### Parameters

- action  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/Bb534741)  
  Action to run.

- message  
  Type: [System.String](https://msdn.microsoft.com/en-us/library/s1wwdcbf)  
  The error message for assert failure.

## See Also

#### Reference

[ReactiveAssert Class](ReactiveAssert/ReactiveAssert)

[Microsoft.Reactive.Testing Namespace](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)
