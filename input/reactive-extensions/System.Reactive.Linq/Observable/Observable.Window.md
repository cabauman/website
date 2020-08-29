title: Window
---
# Observable.Window Method

Projects each element of an observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource, TWindowClosing>(IObservable<TSource>, Func<IObservable<TWindowClosing>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.window%60%602(system.iobservable%7b%60%600%7d%2csystem.func%7bsystem.iobservable%7b%60%601%7d%7d)(v=VS.103))Projects each element of an observable sequence into consecutive non-overlapping windows.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IObservable<TSource>, Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.window%60%601(system.iobservable%7b%60%600%7d%2csystem.int32)(v=VS.103))Projects each element of an observable sequence into consecutive non-overlapping windows which are produced based on element count information.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IObservable<TSource>, TimeSpan)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.window%60%601(system.iobservable%7b%60%600%7d%2csystem.timespan)(v=VS.103))Projects each element of an observable sequence into consecutive non-overlapping windows which are produced based on timing information.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IObservable<TSource>, Int32, Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.window%60%601(system.iobservable%7b%60%600%7d%2csystem.int32%2csystem.int32)(v=VS.103))Projects each element of an observable sequence into zero or more windows which are produced based on element count information.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource, TWindowOpening, TWindowClosing>(IObservable<TSource>, IObservable<TWindowOpening>, Func<TWindowOpening, IObservable<TWindowClosing>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.window%60%603(system.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%2csystem.func%7b%60%601%2csystem.iobservable%7b%60%602%7d%7d)(v=VS.103))Projects each element of an observable sequence into zero or more windows.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IObservable<TSource>, TimeSpan, Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.window%60%601(system.iobservable%7b%60%600%7d%2csystem.timespan%2csystem.int32)(v=VS.103))Projects each element of an observable sequence into a window that is completed when either it’s full or a given amount of time has elapsed.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IObservable<TSource>, TimeSpan, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.window%60%601(system.iobservable%7b%60%600%7d%2csystem.timespan%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Projects each element of an observable sequence into consecutive non-overlapping windows which are produced based on timing information.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IObservable<TSource>, TimeSpan, TimeSpan)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.window%60%601(system.iobservable%7b%60%600%7d%2csystem.timespan%2csystem.timespan)(v=VS.103))Projects each element of an observable sequence into zero or more windows which are produced based on timing information.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IObservable<TSource>, TimeSpan, Int32, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.window%60%601(system.iobservable%7b%60%600%7d%2csystem.timespan%2csystem.int32%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Projects each element of an observable sequence into a window that is completed when either it’s full or a given amount of time has elapsed.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IObservable<TSource>, TimeSpan, TimeSpan, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.window%60%601(system.iobservable%7b%60%600%7d%2csystem.timespan%2csystem.timespan%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Projects each element of an observable sequence into zero or more windows which are produced based on timing information.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Window\<TSource\>(IObservable\<TSource\>, TimeSpan, Int32, IScheduler)

Projects each element of an observable sequence into a window that is completed when either it’s full or a given amount of time has elapsed.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Window(Of TSource) ( _
    source As IObservable(Of TSource), _
    timeSpan As TimeSpan, _
    count As Integer, _
    scheduler As IScheduler _
) As IObservable(Of IObservable(Of TSource))
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim timeSpan As TimeSpan
Dim count As Integer
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of IObservable(Of TSource))

returnValue = source.Window(timeSpan, _
    count, scheduler)
```

```csharp
public static IObservable<IObservable<TSource>> Window<TSource>(
    this IObservable<TSource> source,
    TimeSpan timeSpan,
    int count,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<IObservable<TSource>^>^ Window(
    IObservable<TSource>^ source, 
    TimeSpan timeSpan, 
    int count, 
    IScheduler^ scheduler
)
```

```fsharp
static member Window : 
        source:IObservable<'TSource> * 
        timeSpan:TimeSpan * 
        count:int * 
        scheduler:IScheduler -> IObservable<IObservable<'TSource>> 
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
  The source sequence to produce windows over.

- timeSpan  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The maximum time length of a window.

- count  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The maximum element count of a window.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to run windowing timers on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>  
An observable sequence of windows.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Window\<TSource\>(IObservable\<TSource\>, TimeSpan, IScheduler)

Projects each element of an observable sequence into consecutive non-overlapping windows which are produced based on timing information.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Window(Of TSource) ( _
    source As IObservable(Of TSource), _
    timeSpan As TimeSpan, _
    scheduler As IScheduler _
) As IObservable(Of IObservable(Of TSource))
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim timeSpan As TimeSpan
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of IObservable(Of TSource))

returnValue = source.Window(timeSpan, _
    scheduler)
```

```csharp
public static IObservable<IObservable<TSource>> Window<TSource>(
    this IObservable<TSource> source,
    TimeSpan timeSpan,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<IObservable<TSource>^>^ Window(
    IObservable<TSource>^ source, 
    TimeSpan timeSpan, 
    IScheduler^ scheduler
)
```

```fsharp
static member Window : 
        source:IObservable<'TSource> * 
        timeSpan:TimeSpan * 
        scheduler:IScheduler -> IObservable<IObservable<'TSource>> 
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
  The source sequence to produce windows over.

- timeSpan  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The length of each window.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to run windowing timers on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>  
An observable sequence of windows.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Window\<TSource\>(IObservable\<TSource\>, Int32, Int32)

Projects each element of an observable sequence into zero or more windows which are produced based on element count information.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Window(Of TSource) ( _
    source As IObservable(Of TSource), _
    count As Integer, _
    skip As Integer _
) As IObservable(Of IObservable(Of TSource))
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim count As Integer
Dim skip As Integer
Dim returnValue As IObservable(Of IObservable(Of TSource))

returnValue = source.Window(count, _
    skip)
```

```csharp
public static IObservable<IObservable<TSource>> Window<TSource>(
    this IObservable<TSource> source,
    int count,
    int skip
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<IObservable<TSource>^>^ Window(
    IObservable<TSource>^ source, 
    int count, 
    int skip
)
```

```fsharp
static member Window : 
        source:IObservable<'TSource> * 
        count:int * 
        skip:int -> IObservable<IObservable<'TSource>> 
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
  The source sequence to produce windows over.

- count  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The length of each window.

- skip  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The number of elements to skip between creation of consecutive windows.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>  
An observable sequence of windows.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## Remarks

The Window operator can be used to break up a sequence into buffered subsets like a windowed view of the sequence. The count parameter controls how many items are placed in each window. The skip parameter controls when the next window starts by counting the items produced in the main sequence. When the specified number of items is skipped, a new window starts to buffer a subset of the sequence.

## Examples

This example produces a main sequence of integers using the Interval operator. A new integer is produced every second. The main sequence is broken up by the Window operator into subsets like a windowed view of the integer sequence. Each window will contain a count of three items from the sequence starting with the first item (0). Then five items are skipped so we achieve windows into the integer sequence that contain three integers. Each window starts with every 5th integer beginning at 0.

    using System;
    using System.Reactive.Linq;
    using System.Reactive.Concurrency;
    
    namespace Example
    {
      class Program
      {
        static void Main()
        {
          //***********************************************************************************************//
          //*** The mainSequence produces a new long integer from the Interval operator every second    ***//
          //*** but this sequence is broken up by the Window operator into subsets like a windowed      ***//
          //*** view of the sequence. The count parameter controls how many items are placed in each    ***//
          //*** window. The skip parameter controls when the next window starts by counting the items   ***//
          //*** produced in the main sequence. When the the specified number of items are skipped, a    ***//
          //*** new window starts.                                                                      ***//
          //***                                                                                         ***//
          //*** In this example each window will contain a count of 3 items from the sequence starting  ***//
          //*** with the first item (0). 5 items are "skipped" to determine when the next window opens. ***//
          //*** So the result is that the integer sequences in the windows start with every 5th integer ***//
          //*** beginning at 0 and include 3 integers.                                                  ***//
          //***********************************************************************************************//
    
          var mainSequence = Observable.Interval(TimeSpan.FromSeconds(1));
    
          int count = 3;
          int skip = 5;
          var seqWindowed = mainSequence.Window(count, skip);
    
    
          //*********************************************************************************************//
          //*** A subscription to seqWindowed will provide a new IObservable<long> for every 5th item ***//
          //*** in the main sequence starting with the first item.                                    ***//
          //***                                                                                       ***//
          //*** Create a subscription to each window into the main sequence and list the value.       ***//
          //*********************************************************************************************//
    
          Console.WriteLine("\nCreating the subscription. Press ENTER to exit...\n");
          seqWindowed.Subscribe(seqWindow =>
          {
            Console.WriteLine("\nA new window into the main sequence has been opened\n");
    
            seqWindow.Subscribe(x =>
            {
              Console.WriteLine("Integer : {0}", x);
            });
          });
    
          Console.ReadLine();
        }
      }
    }

The following output was generated with the example code.

    Creating the subscription. Press ENTER to exit...
    
    
    A new window into the main sequence has been opened
    
    Integer : 0
    Integer : 1
    Integer : 2
    
    A new window into the main sequence has been opened
    
    Integer : 5
    Integer : 6
    Integer : 7
    
    A new window into the main sequence has been opened
    
    Integer : 10
    Integer : 11
    Integer : 12
    
    A new window into the main sequence has been opened
    
    Integer : 15
    Integer : 16
    Integer : 17

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Window\<TSource\>(IObservable\<TSource\>, TimeSpan, TimeSpan)

Projects each element of an observable sequence into zero or more windows which are produced based on timing information.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Window(Of TSource) ( _
    source As IObservable(Of TSource), _
    timeSpan As TimeSpan, _
    timeShift As TimeSpan _
) As IObservable(Of IObservable(Of TSource))
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim timeSpan As TimeSpan
Dim timeShift As TimeSpan
Dim returnValue As IObservable(Of IObservable(Of TSource))

returnValue = source.Window(timeSpan, _
    timeShift)
```

```csharp
public static IObservable<IObservable<TSource>> Window<TSource>(
    this IObservable<TSource> source,
    TimeSpan timeSpan,
    TimeSpan timeShift
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<IObservable<TSource>^>^ Window(
    IObservable<TSource>^ source, 
    TimeSpan timeSpan, 
    TimeSpan timeShift
)
```

```fsharp
static member Window : 
        source:IObservable<'TSource> * 
        timeSpan:TimeSpan * 
        timeShift:TimeSpan -> IObservable<IObservable<'TSource>> 
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
  The source sequence to produce windows over.

- timeSpan  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The length of each window.

- timeShift  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The interval between creation of consecutive windows.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>  
An observable sequence of windows.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Window\<TSource\>(IObservable\<TSource\>, TimeSpan, Int32)

Projects each element of an observable sequence into a window that is completed when either it’s full or a given amount of time has elapsed.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Window(Of TSource) ( _
    source As IObservable(Of TSource), _
    timeSpan As TimeSpan, _
    count As Integer _
) As IObservable(Of IObservable(Of TSource))
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim timeSpan As TimeSpan
Dim count As Integer
Dim returnValue As IObservable(Of IObservable(Of TSource))

returnValue = source.Window(timeSpan, _
    count)
```

```csharp
public static IObservable<IObservable<TSource>> Window<TSource>(
    this IObservable<TSource> source,
    TimeSpan timeSpan,
    int count
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<IObservable<TSource>^>^ Window(
    IObservable<TSource>^ source, 
    TimeSpan timeSpan, 
    int count
)
```

```fsharp
static member Window : 
        source:IObservable<'TSource> * 
        timeSpan:TimeSpan * 
        count:int -> IObservable<IObservable<'TSource>> 
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
  The source sequence to produce windows over.

- timeSpan  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The maximum time length of a window.

- count  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The maximum element count of a window.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>  
An observable sequence of windows.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Window\<TSource\>(IObservable\<TSource\>, TimeSpan, TimeSpan, IScheduler)

Projects each element of an observable sequence into zero or more windows which are produced based on timing information.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Window(Of TSource) ( _
    source As IObservable(Of TSource), _
    timeSpan As TimeSpan, _
    timeShift As TimeSpan, _
    scheduler As IScheduler _
) As IObservable(Of IObservable(Of TSource))
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim timeSpan As TimeSpan
Dim timeShift As TimeSpan
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of IObservable(Of TSource))

returnValue = source.Window(timeSpan, _
    timeShift, scheduler)
```

```csharp
public static IObservable<IObservable<TSource>> Window<TSource>(
    this IObservable<TSource> source,
    TimeSpan timeSpan,
    TimeSpan timeShift,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<IObservable<TSource>^>^ Window(
    IObservable<TSource>^ source, 
    TimeSpan timeSpan, 
    TimeSpan timeShift, 
    IScheduler^ scheduler
)
```

```fsharp
static member Window : 
        source:IObservable<'TSource> * 
        timeSpan:TimeSpan * 
        timeShift:TimeSpan * 
        scheduler:IScheduler -> IObservable<IObservable<'TSource>> 
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
  The source sequence to produce windows over.

- timeSpan  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The length of each window.

- timeShift  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The interval between creation of consecutive windows.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to run windowing timers on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>  
An observable sequence of windows.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## Remarks

The Window operator breaks a source sequence into buffered subsets like a windowed view of the sequence. The timeSpan parameter controls how many items are placed in each window buffer by keeping the window open for the duration of that time span. The timeShift parameter indicates the time span, from the beginning of the previous window, which must complete before a new window opens. This shifts the view into the sequence based on the duration of that time span. The scheduler parameter controls where to run the timers associated with the timeSpan and timeShift parameters.

## Examples

In this example the Window operator is used to observe integer sequences from the Interval operator every second.. Each integer sequence is viewed through a window. Each window will be open for 2.5 seconds and then closed. The timeShift parameter is set to 5 seconds . This means a new window will open every 5 seconds from the time each previous window opened. The end result is we have a window open for 2.5 seconds and then closed for 2.5 seconds. So the sequences will include two integers starting from every 5th integer beginning with 0.

    using System;
    using System.Reactive.Linq;
    using System.Reactive.Concurrency;
    
    namespace Example
    {
      class Program
      {
        static void Main()
        {
          //**********************************************************************************************//
          //*** The mainSequence produces a new long integer from the Interval operator every sec but  ***//
          //*** this sequence is broken up by the Window operator into subsets like a windowed         ***//
          //*** view of the sequence.                                                                  ***//
          //***                                                                                        ***//
          //*** The timeSpan parameter controls how many items are placed in each window buffer by     ***//
          //*** keeping the window open for the duration of the time span.                             ***//
          //***                                                                                        ***//
          //*** The timeShift parameter indicates the time span which must complete before a new       ***//
          //*** window opens. This shifts the view into the sequence based on the duration of the time ***//
          //*** span.                                                                                  ***//
          //***                                                                                        ***//
          //*** The ThreadPool scheduler is used to run the timers on a .NET thread pool thread. This  ***//
          //*** prevents the main thread from being blocked so pressing enter can exit the example.    ***//
          //***                                                                                        ***//
          //*** In this example each window will be open for 2.5 seconds. This will allow each window  ***//
          //*** to hold some items from the sequence starting with the first item (0). Then the        ***//
          //*** timeShift parameter shifts the next window opening by 5 seconds from the beginning of  ***//
          //*** the previous window. The result is that a window is open for 2.5 seconds then closed   ***//
          //*** for 2.5 seconds.                                                                       ***//
          //**********************************************************************************************//
    
          var mainSequence = Observable.Interval(TimeSpan.FromSeconds(1));
    
          TimeSpan timeSpan = TimeSpan.FromSeconds(2.5);
          TimeSpan timeShift = TimeSpan.FromSeconds(5);
          var seqWindowed = mainSequence.Window(timeSpan, timeShift, Scheduler.ThreadPool);
    
    
          //*********************************************************************************************//
          //*** A subscription to seqWindowed will provide a new IObservable<long> for some items in  ***//
          //*** the main sequence starting with the first item. Then we will receive a new observable ***//
          //*** for every window.                                                                     ***//
          //***                                                                                       ***//
          //*** Create a subscription to each window into the main sequence and list the values.      ***//
          //*********************************************************************************************//
    
          Console.WriteLine("Creating the subscription. Press ENTER to exit...\n");
          seqWindowed.Subscribe(seqWindow =>
          {
            Console.WriteLine("\nA new window into the main sequence has been opened\n");
    
            seqWindow.Subscribe(x =>
            {
              Console.WriteLine("Integer : {0}", x);
            });
          });
    
          Console.ReadLine();
        }
      }
    }

The following output was generated by the example code.

    Creating the subscription. Press ENTER to exit...
    
    
    A new window into the main sequence has been opened
    
    Integer : 0
    Integer : 1
    
    A new window into the main sequence has been opened
    
    Integer : 5
    Integer : 6
    
    A new window into the main sequence has been opened
    
    Integer : 10
    Integer : 11
    
    A new window into the main sequence has been opened
    
    Integer : 15
    Integer : 16
    
    A new window into the main sequence has been opened
    
    Integer : 20
    Integer : 21

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Window\<TSource\>(IObservable\<TSource\>, TimeSpan)

Projects each element of an observable sequence into consecutive non-overlapping windows which are produced based on timing information.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Window(Of TSource) ( _
    source As IObservable(Of TSource), _
    timeSpan As TimeSpan _
) As IObservable(Of IObservable(Of TSource))
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim timeSpan As TimeSpan
Dim returnValue As IObservable(Of IObservable(Of TSource))

returnValue = source.Window(timeSpan)
```

```csharp
public static IObservable<IObservable<TSource>> Window<TSource>(
    this IObservable<TSource> source,
    TimeSpan timeSpan
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<IObservable<TSource>^>^ Window(
    IObservable<TSource>^ source, 
    TimeSpan timeSpan
)
```

```fsharp
static member Window : 
        source:IObservable<'TSource> * 
        timeSpan:TimeSpan -> IObservable<IObservable<'TSource>> 
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
  The source sequence to produce windows over.

- timeSpan  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The length of each window.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>  
The sequence of windows.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Window\<TSource\>(IObservable\<TSource\>, Int32)

Projects each element of an observable sequence into consecutive non-overlapping windows which are produced based on element count information.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Window(Of TSource) ( _
    source As IObservable(Of TSource), _
    count As Integer _
) As IObservable(Of IObservable(Of TSource))
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim count As Integer
Dim returnValue As IObservable(Of IObservable(Of TSource))

returnValue = source.Window(count)
```

```csharp
public static IObservable<IObservable<TSource>> Window<TSource>(
    this IObservable<TSource> source,
    int count
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<IObservable<TSource>^>^ Window(
    IObservable<TSource>^ source, 
    int count
)
```

```fsharp
static member Window : 
        source:IObservable<'TSource> * 
        count:int -> IObservable<IObservable<'TSource>> 
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
  The source sequence to produce windows over.

- count  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The length of each window.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>  
An observable sequence of windows.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Window\<TSource, TWindowClosing\>(IObservable\<TSource\>, Func\<IObservable\<TWindowClosing\>\>)

Projects each element of an observable sequence into consecutive non-overlapping windows.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Window(Of TSource, TWindowClosing) ( _
    source As IObservable(Of TSource), _
    windowClosingSelector As Func(Of IObservable(Of TWindowClosing)) _
) As IObservable(Of IObservable(Of TSource))
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim windowClosingSelector As Func(Of IObservable(Of TWindowClosing))
Dim returnValue As IObservable(Of IObservable(Of TSource))

returnValue = source.Window(windowClosingSelector)
```

```csharp
public static IObservable<IObservable<TSource>> Window<TSource, TWindowClosing>(
    this IObservable<TSource> source,
    Func<IObservable<TWindowClosing>> windowClosingSelector
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TWindowClosing>
static IObservable<IObservable<TSource>^>^ Window(
    IObservable<TSource>^ source, 
    Func<IObservable<TWindowClosing>^>^ windowClosingSelector
)
```

```fsharp
static member Window : 
        source:IObservable<'TSource> * 
        windowClosingSelector:Func<IObservable<'TWindowClosing>> -> IObservable<IObservable<'TSource>> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TWindowClosing  
  The type of window closing.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence to produce windows over.

- windowClosingSelector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb534960)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TWindowClosing\>\>  
  A function invoked to define the boundaries of the produced windows.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>  
An observable sequence of windows.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## Remarks

The Window operator breaks up an observable sequence into consecutive non-overlapping windows. The end of the current window and start of the next window is controlled by an observable sequence which is the result of the **windowClosingSelect** function which is passed as an input parameter to the operator. The operator could be used to group a set of events into a window. For example, states of a transaction could be the main sequence being observed. Those states could include: Preparing, Prepared, Active, and Committed/Aborted. The main sequence could include all of those states are they occur in that order. The windowClosingSelect function could return an observable sequence that only produces a value on the Committed or Abort states. This would close the window that represented transaction events for a particular transaction.

## Examples

The following simple example breaks up a sequence of integers into consecutive non-overlapping windows. The end of the current window and start of the next window is controlled by an observable sequence of integers produced by the Interval operator every six seconds. Since the main observable sequence is producing an item every seconds, each window will have six items in it. The example code writes each window of integers to the console window along with a timestamp that shows a new window is opened every six seconds.

    using System;
    using System.Reactive.Linq;
    
    namespace Example
    {
      class Program
      {
        static void Main()
        {
          //*********************************************************************************************//
          //*** The mainSequence produces a new long integer from the Interval operator every sec but ***//
          //*** this sequence is broken up by the Window operator into subsets like a windowed        ***//
          //*** view of the sequence. The time when each window stops and the next window starts is   ***//
          //*** controlled by the IObservable<TWindowClosing> named seqWindowControl. It is returned  ***//
          //*** by the lambda expression which is passed to the Window operator. In this case it      ***//
          //**  returns another IObservable<long> generated by the Interval operator. So whenever     ***//
          //*** seqWindowControl produces a item, the current window into the mainSequence stops and  ***//
          //*** a new window starts.                                                                  ***//
          //*********************************************************************************************//
    
          var mainSequence = Observable.Interval(TimeSpan.FromSeconds(1));
    
          var seqWindowed = mainSequence.Window(() => 
          {
            var seqWindowControl = Observable.Interval(TimeSpan.FromSeconds(6));
            return seqWindowControl;
          });
    
    
          //*********************************************************************************************//
          //*** A subscription to seqWindowed will provide a new IObservable<long> every 6 secs.      ***//
          //***                                                                                       ***//
          //*** Create a subscription to each window into the main sequence and list the values along ***//
          //*** with the time the window was opened and the previous window was closed.               ***//
          //*********************************************************************************************//
          
          seqWindowed.Subscribe(seqWindow => 
          {
            Console.WriteLine("\nA new window into the main sequence has opened: {0}\n",DateTime.Now.ToString());
            seqWindow.Subscribe(x =>
            {
              Console.WriteLine("Integer : {0}", x);
            });
          });
    
          Console.ReadLine();
        }
      }
    }

The following output was generated by the example code.

    A new window into the main sequence has opened: 6/1/2011 8:48:43 PM
    
    Integer : 0
    Integer : 1
    Integer : 2
    Integer : 3
    Integer : 4
    Integer : 5
    
    A new window into the main sequence has opened: 6/1/2011 8:48:49 PM
    
    Integer : 6
    Integer : 7
    Integer : 8
    Integer : 9
    Integer : 10
    Integer : 11
    
    A new window into the main sequence has opened: 6/1/2011 8:48:55 PM
    
    Integer : 12
    Integer : 13
    Integer : 14
    Integer : 15
    Integer : 16
    Integer : 17
    
    A new window into the main sequence has opened: 6/1/2011 8:49:02 PM
    
    Integer : 18
    Integer : 19
    Integer : 20
    Integer : 21
    Integer : 22
    Integer : 23

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Window\<TSource, TWindowOpening, TWindowClosing\>(IObservable\<TSource\>, IObservable\<TWindowOpening\>, Func\<TWindowOpening, IObservable\<TWindowClosing\>\>)

Projects each element of an observable sequence into zero or more windows.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Window(Of TSource, TWindowOpening, TWindowClosing) ( _
    source As IObservable(Of TSource), _
    windowOpenings As IObservable(Of TWindowOpening), _
    windowClosingSelector As Func(Of TWindowOpening, IObservable(Of TWindowClosing)) _
) As IObservable(Of IObservable(Of TSource))
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim windowOpenings As IObservable(Of TWindowOpening)
Dim windowClosingSelector As Func(Of TWindowOpening, IObservable(Of TWindowClosing))
Dim returnValue As IObservable(Of IObservable(Of TSource))

returnValue = source.Window(windowOpenings, _
    windowClosingSelector)
```

```csharp
public static IObservable<IObservable<TSource>> Window<TSource, TWindowOpening, TWindowClosing>(
    this IObservable<TSource> source,
    IObservable<TWindowOpening> windowOpenings,
    Func<TWindowOpening, IObservable<TWindowClosing>> windowClosingSelector
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TWindowOpening, typename TWindowClosing>
static IObservable<IObservable<TSource>^>^ Window(
    IObservable<TSource>^ source, 
    IObservable<TWindowOpening>^ windowOpenings, 
    Func<TWindowOpening, IObservable<TWindowClosing>^>^ windowClosingSelector
)
```

```fsharp
static member Window : 
        source:IObservable<'TSource> * 
        windowOpenings:IObservable<'TWindowOpening> * 
        windowClosingSelector:Func<'TWindowOpening, IObservable<'TWindowClosing>> -> IObservable<IObservable<'TSource>> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TWindowOpening  
  The type of window opening.

- TWindowClosing  
  The type of window closing.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence to produce windows over.

- windowOpenings  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TWindowOpening\>  
  The observable sequence whose elements denote the creation of new windows.

- windowClosingSelector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TWindowOpening, [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TWindowClosing\>\>  
  A function invoked to define the closing of each produced window.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>  
An observable sequence of windows.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
