title: Pattern<T1,T2>
---
# Pattern\<T1, T2\> Class

Represents a join pattern.

## Inheritance Hierarchy

[System.Object](https://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [System.Reactive.Joins.Pattern](Pattern/Pattern)  
    System.Reactive.Joins.Pattern\<T1, T2\>

**Namespace:**  [System.Reactive.Joins](System.Reactive.Joins/System.Reactive.Joins)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Class Pattern(Of T1, T2) _
    Inherits Pattern
```

```vb
'Usage
Dim instance As Pattern(Of T1, T2)
```

```csharp
public class Pattern<T1, T2> : Pattern
```

```c++
generic<typename T1, typename T2>
public ref class Pattern : public Pattern
```

```fsharp
type Pattern<'T1, 'T2> =  
    class
        inherit Pattern
    end
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T1  
  The type of the first component of the pattern.

- T2  
  The type of the second component of the pattern.

The Pattern\<T1, T2\> type exposes the following members.

## Methods

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[And<T3>](https://msdn.microsoft.com/en-us/library/m:system.reactive.joins.pattern%602.and%60%601(system.iobservable%7b%60%600%7d)(v=VS.103))Matches when all observable sequences have an available value.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Equals](https://msdn.microsoft.com/en-us/library/m:system.object.equals(system.object)(v=VS.103))(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Protected method](https://reactiveui.net/assets/img/Hh303103.protmethod(en-us,VS.103).gif "Protected method")[Finalize](https://msdn.microsoft.com/en-us/library/4k87zsw7)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[GetHashCode](https://msdn.microsoft.com/en-us/library/zdee4b3y)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[GetType](https://msdn.microsoft.com/en-us/library/dfwy45w9)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Protected method](https://reactiveui.net/assets/img/Hh303103.protmethod(en-us,VS.103).gif "Protected method")[MemberwiseClone](https://msdn.microsoft.com/en-us/library/57ctke0a)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Then<TResult>](https://msdn.microsoft.com/en-us/library/m:system.reactive.joins.pattern%602.then%60%601(system.func%7b%600%2c%601%2c%60%600%7d)(v=VS.103))Matches when all observable sequences have an available value and projects the values.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[ToString](https://msdn.microsoft.com/en-us/library/7bxwbwt2)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)Top

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)



<br />

# Pattern\<T1, T2\> Methods

The [Pattern\<T1, T2\>](Pattern/Pattern(T1,) type exposes the following members.

## Methods

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[And<T3>](https://msdn.microsoft.com/en-us/library/m:system.reactive.joins.pattern%602.and%60%601(system.iobservable%7b%60%600%7d)(v=VS.103))Matches when all observable sequences have an available value.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Equals](https://msdn.microsoft.com/en-us/library/m:system.object.equals(system.object)(v=VS.103))(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Protected method](https://reactiveui.net/assets/img/Hh303103.protmethod(en-us,VS.103).gif "Protected method")[Finalize](https://msdn.microsoft.com/en-us/library/4k87zsw7)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[GetHashCode](https://msdn.microsoft.com/en-us/library/zdee4b3y)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[GetType](https://msdn.microsoft.com/en-us/library/dfwy45w9)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Protected method](https://reactiveui.net/assets/img/Hh303103.protmethod(en-us,VS.103).gif "Protected method")[MemberwiseClone](https://msdn.microsoft.com/en-us/library/57ctke0a)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Then<TResult>](https://msdn.microsoft.com/en-us/library/m:system.reactive.joins.pattern%602.then%60%601(system.func%7b%600%2c%601%2c%60%600%7d)(v=VS.103))Matches when all observable sequences have an available value and projects the values.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[ToString](https://msdn.microsoft.com/en-us/library/7bxwbwt2)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)Top

## See Also

#### Reference

[Pattern\<T1, T2\> Class](Pattern/Pattern(T1,)

[System.Reactive.Joins Namespace](System.Reactive.Joins/System.Reactive.Joins)
