title: Synchronize
---
# Qbservable.Synchronize Method

Synchronizes the queryable observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Synchronize<TSource>(IQbservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.synchronize%60%601(system.reactive.linq.iqbservable%7b%60%600%7d)(v=VS.103))Synchronizes the queryable observable sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Synchronize<TSource>(IQbservable<TSource>, Object)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.synchronize%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.object)(v=VS.103))Synchronizes the queryable observable sequence.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Synchronize\<TSource\>(IQbservable\<TSource\>, Object)

Synchronizes the queryable observable sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Synchronize(Of TSource) ( _
    source As IQbservable(Of TSource), _
    gate As Object _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim gate As Object
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Synchronize(gate)
```

```csharp
public static IQbservable<TSource> Synchronize<TSource>(
    this IQbservable<TSource> source,
    Object gate
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Synchronize(
    IQbservable<TSource>^ source, 
    Object^ gate
)
```

```fsharp
static member Synchronize : 
        source:IQbservable<'TSource> * 
        gate:Object -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  The source sequence.

- gate  
  Type: [System.Object](https://msdn.microsoft.com/en-us/library/e5kfa45b)  
  The gate object to synchronize each observer call on.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The source sequence whose outgoing calls to observers are synchronized on the given gate object.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Synchronize\<TSource\>(IQbservable\<TSource\>)

Synchronizes the queryable observable sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Synchronize(Of TSource) ( _
    source As IQbservable(Of TSource) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Synchronize()
```

```csharp
public static IQbservable<TSource> Synchronize<TSource>(
    this IQbservable<TSource> source
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Synchronize(
    IQbservable<TSource>^ source
)
```

```fsharp
static member Synchronize : 
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
  The source sequence.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The source sequence whose outgoing calls to observers are synchronized.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
