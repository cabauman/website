title: Retry
---
# Qbservable.Retry Method

Repeats the source queryable observable sequence until it successfully terminates.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Retry<TSource>(IQbservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.retry%60%601(system.reactive.linq.iqbservable%7b%60%600%7d)(v=VS.103))Repeats the source queryable observable sequence until it successfully terminates.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Retry<TSource>(IQbservable<TSource>, Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.retry%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.int32)(v=VS.103))Repeats the source queryable observable sequence until it successfully terminates.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Retry\<TSource\>(IQbservable\<TSource\>)

Repeats the source queryable observable sequence until it successfully terminates.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Retry(Of TSource) ( _
    source As IQbservable(Of TSource) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Retry()
```

```csharp
public static IQbservable<TSource> Retry<TSource>(
    this IQbservable<TSource> source
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Retry(
    IQbservable<TSource>^ source
)
```

```fsharp
static member Retry : 
        source:IQbservable<'TSource> -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  The queryable observable sequence to repeat until it successfully terminates.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The queryable observable sequence producing the elements of the given sequence repeatedly until it terminates successfully.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Retry\<TSource\>(IQbservable\<TSource\>, Int32)

Repeats the source queryable observable sequence until it successfully terminates.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Retry(Of TSource) ( _
    source As IQbservable(Of TSource), _
    retryCount As Integer _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim retryCount As Integer
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Retry(retryCount)
```

```csharp
public static IQbservable<TSource> Retry<TSource>(
    this IQbservable<TSource> source,
    int retryCount
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Retry(
    IQbservable<TSource>^ source, 
    int retryCount
)
```

```fsharp
static member Retry : 
        source:IQbservable<'TSource> * 
        retryCount:int -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  Queryable observable sequence to repeat until it successfully terminates.

- retryCount  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  Number of times to repeat the sequence.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The queryable observable sequence producing the elements of the given sequence repeatedly until it terminates successfully.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
