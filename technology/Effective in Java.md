1. forword

2. preface

3. acknowledgement

4. Consist of 

5. convey

6. capture

7. loosely

8. intend

9. The book is not intended to be read from cover to cover 

10. Cross-referenced

11. The items are heavily cross-referenced so you can easily plot your own course through the book.

12. coverage

13. Most items are **illustrated with** program examples.

    > Illustrate 说明

14. favor

15. you may have to add one or more import **declarations**, or other such **boilerplate**

16. deserve

17. The language supports four kinds of types: interfaces (including annotations), classes (including enums), arrays, and **primitives**(基本类型)

18. inheritance(继承)

19. this book uses inheritance as a synonym for subclassing

20. The term exported API, or simply API, **refers** to the classes, interfaces, constructors, members, and serialized forms by which a programmer accesses a class, interface, or package.

21. how to ensure they are destroyed in a timely manner, and how to manage any cleanup actions that must precede their destruction.

22. Programmers have been known to **get around this restriction** by providing two constructors whose parameter lists differ only in the order of their parameter types.

23. This allows **immutable** classes (Item 17) to use **preconstructed** instances, or to cache instances as they’re constructed, and **dispense** them repeatedly to avoid creating unnecessary duplicate objects.

    > immutable classes - 不可变的类
    >
    > Dispendse- 分配

24. It can greatly improve performance if **equivalent** objects are requested often, especially if they are expensive to create.

    >equivalent-相同的；等价物

25. The ability of static factory methods to return the same object from repeated **invocations** allows classes to maintain strict control over what instances exist at any time.

    > Repeated invocation - 重复调用；

26. it allows an **immutable** value class to make the guarantee that no two equal instances exist: 

    > Immutable - 不可变的；

27. This gives you great **flexibility** in choosing the class of the returned object.

    > flexibility- 灵活性

28. **Prior to** Java 8, interfaces couldn’t have static methods.

    > Prior to - 在...之前

29. By convention, static factory methods for an interface named Type were put in a noninstantiable companion class (Item 4) named Types.

    > by convention- 按照惯例

30. For example, the Java Collections Framework has forty-five **utility** implementations of its interfaces, providing **unmodifiable** collections, synchronized collections, and the like. Nearly all of these implementations are exported via static factory methods in one noninstantiable class (java.util.Collections). The classes of the returned objects are all **nonpublic**.

    > utility implementations - 工具类实现
    >
    > Unmodifitable collections 不可变的集合
    >
    > Nonpublic classes 非公共类

31. It is not just the bulk of the API that is reduced but the **conceptual** weight:

    > Bulk of API  api 的数量
    >
    > Conceptual weight  概念上的负担

32. The programmer knows that the returned object has **precisely** the API specified by its interface, so there is no need to read additional class documentation for the implementation class. **Furthermore**, using such a static factory method requires the client to **refer to** the returned object by interface rather than implementation class, which is generally good practice.

    > Precisely  恰好
    >
    > refer to by interface 通过借口引用
    >
    > Futhermore 此外
    >> good practice  好的实践

33. As of Java 8, the restriction that interfaces cannot contain static methods was **eliminated**, so there is typically  little reason to provide a noninstantiable **companion** **class** for an interface.

    > Eliminated 被移除
    >
    > Companion class 伴生类

34. they return an instance of one of two subclasses, depending on the size of the **underlying** enum type

    > Underlying enum type 基本的枚举类型

35. 

    