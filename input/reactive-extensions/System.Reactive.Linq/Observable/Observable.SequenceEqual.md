title: SequenceEqual
---
# Observable.SequenceEqual Method

Determines whether two sequences are equal.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[SequenceEqual<TSource>(IObservable<TSource>, IObservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.sequenceequal%60%601(system.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%600%7d)(v=VS.103))Determines whether two sequences are equal by comparing the elements pairwise.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[SequenceEqual<TSource>(IObservable<TSource>, IObservable<TSource>, IEqualityComparer<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.sequenceequal%60%601(system.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%600%7d%2csystem.collections.generic.iequalitycomparer%7b%60%600%7d)(v=VS.103))Determines whether two sequences are equal by comparing the elements pairwise using a specified equality comparer.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# SequenceEqual\<TSource\>(IObservable\<TSource\>, IObservable\<TSource\>)

Determines whether two sequences are equal by comparing the elements pairwise.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function SequenceEqual(Of TSource) ( _
    first As IObservable(Of TSource), _
    second As IObservable(Of TSource) _
) As IObservable(Of Boolean)
```

```vb
'Usage
Dim first As IObservable(Of TSource)
Dim second As IObservable(Of TSource)
Dim returnValue As IObservable(Of Boolean)

returnValue = first.SequenceEqual(second)
```

```csharp
public static IObservable<bool> SequenceEqual<TSource>(
    this IObservable<TSource> first,
    IObservable<TSource> second
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<bool>^ SequenceEqual(
    IObservable<TSource>^ first, 
    IObservable<TSource>^ second
)
```

```fsharp
static member SequenceEqual : 
        first:IObservable<'TSource> * 
        second:IObservable<'TSource> -> IObservable<bool> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- first  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  First observable sequence to compare.

- second  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  Second observable sequence to compare.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[Boolean](https://msdn.microsoft.com/en-us/library/a28wyd50)\>  
True if two sequences are equal by comparing the elements pairwise; otherwise, false.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# SequenceEqual\<TSource\>(IObservable\<TSource\>, IObservable\<TSource\>, IEqualityComparer\<TSource\>)

Determines whether two sequences are equal by comparing the elements pairwise using a specified equality comparer.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function SequenceEqual(Of TSource) ( _
    first As IObservable(Of TSource), _
    second As IObservable(Of TSource), _
    comparer As IEqualityComparer(Of TSource) _
) As IObservable(Of Boolean)
```

```vb
'Usage
Dim first As IObservable(Of TSource)
Dim second As IObservable(Of TSource)
Dim comparer As IEqualityComparer(Of TSource)
Dim returnValue As IObservable(Of Boolean)

returnValue = first.SequenceEqual(second, _
    comparer)
```

```csharp
public static IObservable<bool> SequenceEqual<TSource>(
    this IObservable<TSource> first,
    IObservable<TSource> second,
    IEqualityComparer<TSource> comparer
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<bool>^ SequenceEqual(
    IObservable<TSource>^ first, 
    IObservable<TSource>^ second, 
    IEqualityComparer<TSource>^ comparer
)
```

```fsharp
static member SequenceEqual : 
        first:IObservable<'TSource> * 
        second:IObservable<'TSource> * 
        comparer:IEqualityComparer<'TSource> -> IObservable<bool> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- first  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  First observable sequence to compare.

- second  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  Second observable sequence to compare.

- comparer  
  Type: [System.Collections.Generic.IEqualityComparer](https://msdn.microsoft.com/en-us/library/ms132151)\<TSource\>  
  A comparer used to compare elements of both sequences.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[Boolean](https://msdn.microsoft.com/en-us/library/a28wyd50)\>  
True if two sequences are equal by comparing the elements pairwise using a specified equality comparer; otherwise, false.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
