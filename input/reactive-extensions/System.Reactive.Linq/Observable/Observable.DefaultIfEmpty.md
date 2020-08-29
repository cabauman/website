title: DefaultIfEmpty
---
# Observable.DefaultIfEmpty Method

Returns the elements of the specified sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[DefaultIfEmpty<TSource>(IObservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.defaultifempty%60%601(system.iobservable%7b%60%600%7d)(v=VS.103))Returns the elements of the specified sequence or the type parameter's default value in a singleton sequence if the sequence is empty.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[DefaultIfEmpty<TSource>(IObservable<TSource>, TSource)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.defaultifempty%60%601(system.iobservable%7b%60%600%7d%2c%60%600)(v=VS.103))Returns the elements of the specified sequence or the type parameter's default value in a singleton sequence if the sequence is empty.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# DefaultIfEmpty\<TSource\>(IObservable\<TSource\>, TSource)

Returns the elements of the specified sequence or the type parameter's default value in a singleton sequence if the sequence is empty.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function DefaultIfEmpty(Of TSource) ( _
    source As IObservable(Of TSource), _
    defaultValue As TSource _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim defaultValue As TSource
Dim returnValue As IObservable(Of TSource)

returnValue = source.DefaultIfEmpty(defaultValue)
```

```csharp
public static IObservable<TSource> DefaultIfEmpty<TSource>(
    this IObservable<TSource> source,
    TSource defaultValue
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ DefaultIfEmpty(
    IObservable<TSource>^ source, 
    TSource defaultValue
)
```

```fsharp
static member DefaultIfEmpty : 
        source:IObservable<'TSource> * 
        defaultValue:'TSource -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The sequence to return the specified value for if it is empty.

- defaultValue  
  Type: TSource  
  The value to return if the sequence is empty.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
An observable sequence that contains the specified default value if the source is empty; otherwise, the elements of the source itself.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# DefaultIfEmpty\<TSource\>(IObservable\<TSource\>)

Returns the elements of the specified sequence or the type parameter's default value in a singleton sequence if the sequence is empty.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function DefaultIfEmpty(Of TSource) ( _
    source As IObservable(Of TSource) _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim returnValue As IObservable(Of TSource)

returnValue = source.DefaultIfEmpty()
```

```csharp
public static IObservable<TSource> DefaultIfEmpty<TSource>(
    this IObservable<TSource> source
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ DefaultIfEmpty(
    IObservable<TSource>^ source
)
```

```fsharp
static member DefaultIfEmpty : 
        source:IObservable<'TSource> -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The sequence to return a default value for if it is empty.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
An observable sequence that contains the default value for the TSource type if the source is empty; otherwise, the elements of the source itself.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
