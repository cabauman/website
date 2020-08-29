title: Return
---
# Qbservable.Return Method

Returns a queryable observable sequence that contains a single element or value.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Return<TResult>(IQbservableProvider, TResult)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.return%60%601(system.reactive.linq.iqbservableprovider%2c%60%600)(v=VS.103))Returns a queryable observable sequence that contains a single element with a specified value.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Return<TResult>(IQbservableProvider, TResult, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.return%60%601(system.reactive.linq.iqbservableprovider%2c%60%600%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns a queryable observable sequence that contains a single value with a specified value and scheduler.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Return\<TResult\>(IQbservableProvider, TResult)

Returns a queryable observable sequence that contains a single element with a specified value.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Return(Of TResult) ( _
    provider As IQbservableProvider, _
    value As TResult _
) As IQbservable(Of TResult)
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim value As TResult
Dim returnValue As IQbservable(Of TResult)

returnValue = provider.Return(value)
```

```csharp
public static IQbservable<TResult> Return<TResult>(
    this IQbservableProvider provider,
    TResult value
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TResult>
static IQbservable<TResult>^ Return(
    IQbservableProvider^ provider, 
    TResult value
)
```

```fsharp
static member Return : 
        provider:IQbservableProvider * 
        value:'TResult -> IQbservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The type of result.

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- value  
  Type: TResult  
  The single element in the resulting queryable observable sequence.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TResult\>  
The queryable observable sequence containing the single specified element.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Return\<TResult\>(IQbservableProvider, TResult, IScheduler)

Returns a queryable observable sequence that contains a single value with a specified value and scheduler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Return(Of TResult) ( _
    provider As IQbservableProvider, _
    value As TResult, _
    scheduler As IScheduler _
) As IQbservable(Of TResult)
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim value As TResult
Dim scheduler As IScheduler
Dim returnValue As IQbservable(Of TResult)

returnValue = provider.Return(value, _
    scheduler)
```

```csharp
public static IQbservable<TResult> Return<TResult>(
    this IQbservableProvider provider,
    TResult value,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TResult>
static IQbservable<TResult>^ Return(
    IQbservableProvider^ provider, 
    TResult value, 
    IScheduler^ scheduler
)
```

```fsharp
static member Return : 
        provider:IQbservableProvider * 
        value:'TResult * 
        scheduler:IScheduler -> IQbservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The type of result.

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- value  
  Type: TResult  
  The single element in the resulting observable sequence.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to send the single element on.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TResult\>  
The queryable observable sequence containing the single specified element.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
