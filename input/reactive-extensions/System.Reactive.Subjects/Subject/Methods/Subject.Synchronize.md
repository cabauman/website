title: Synchronize
---
# Subject.Synchronize Method

Synchronizes the messages on the subject.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Synchronize<TSource, TResult>(ISubject<TSource, TResult>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.subjects.subject.synchronize%60%602(system.reactive.subjects.isubject%7b%60%600%2c%60%601%7d)(v=VS.103))Synchronizes the messages on the subject.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Synchronize<TSource, TResult>(ISubject<TSource, TResult>, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.subjects.subject.synchronize%60%602(system.reactive.subjects.isubject%7b%60%600%2c%60%601%7d%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Synchronizes the messages on the subject and notifies observers on the specified scheduler.Top

## See Also

#### Reference

[Subject Class](Subject/Subject)

[System.Reactive.Subjects Namespace](System.Reactive.Subjects/System.Reactive.Subjects)



<br />

# Synchronize\<TSource, TResult\>(ISubject\<TSource, TResult\>)

Synchronizes the messages on the subject.

**Namespace:**  [System.Reactive.Subjects](System.Reactive.Subjects/System.Reactive.Subjects)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function Synchronize(Of TSource, TResult) ( _
    subject As ISubject(Of TSource, TResult) _
) As ISubject(Of TSource, TResult)
```

```vb
'Usage
Dim subject As ISubject(Of TSource, TResult)
Dim returnValue As ISubject(Of TSource, TResult)

returnValue = Subject.Synchronize(subject)
```

```csharp
public static ISubject<TSource, TResult> Synchronize<TSource, TResult>(
    ISubject<TSource, TResult> subject
)
```

```c++
public:
generic<typename TSource, typename TResult>
static ISubject<TSource, TResult>^ Synchronize(
    ISubject<TSource, TResult>^ subject
)
```

```fsharp
static member Synchronize : 
        subject:ISubject<'TSource, 'TResult> -> ISubject<'TSource, 'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

- TResult  
  The type of result.

#### Parameters

- subject  
  Type: [System.Reactive.Subjects.ISubject](ISubject/ISubject(TSource,)\<TSource, TResult\>  
  The subject to synchronize.

#### Return Value

Type: [System.Reactive.Subjects.ISubject](ISubject/ISubject(TSource,)\<TSource, TResult\>  
Subject whose messages are synchronized.

## See Also

#### Reference

[Subject Class](Subject/Subject)

[System.Reactive.Subjects Namespace](System.Reactive.Subjects/System.Reactive.Subjects)



<br />

# Synchronize\<TSource, TResult\>(ISubject\<TSource, TResult\>, IScheduler)

Synchronizes the messages on the subject and notifies observers on the specified scheduler.

**Namespace:**  [System.Reactive.Subjects](System.Reactive.Subjects/System.Reactive.Subjects)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function Synchronize(Of TSource, TResult) ( _
    subject As ISubject(Of TSource, TResult), _
    scheduler As IScheduler _
) As ISubject(Of TSource, TResult)
```

```vb
'Usage
Dim subject As ISubject(Of TSource, TResult)
Dim scheduler As IScheduler
Dim returnValue As ISubject(Of TSource, TResult)

returnValue = Subject.Synchronize(subject, _
    scheduler)
```

```csharp
public static ISubject<TSource, TResult> Synchronize<TSource, TResult>(
    ISubject<TSource, TResult> subject,
    IScheduler scheduler
)
```

```c++
public:
generic<typename TSource, typename TResult>
static ISubject<TSource, TResult>^ Synchronize(
    ISubject<TSource, TResult>^ subject, 
    IScheduler^ scheduler
)
```

```fsharp
static member Synchronize : 
        subject:ISubject<'TSource, 'TResult> * 
        scheduler:IScheduler -> ISubject<'TSource, 'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

- TResult  
  Type of result.

#### Parameters

- subject  
  Type: [System.Reactive.Subjects.ISubject](ISubject/ISubject(TSource,)\<TSource, TResult\>  
  The subject to synchronize.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  Scheduler to notify observers on.

#### Return Value

Type: [System.Reactive.Subjects.ISubject](ISubject/ISubject(TSource,)\<TSource, TResult\>  
Subject whose messages are synchronized and whose observers are notified on the given scheduler.

## See Also

#### Reference

[Subject Class](Subject/Subject)

[System.Reactive.Subjects Namespace](System.Reactive.Subjects/System.Reactive.Subjects)
