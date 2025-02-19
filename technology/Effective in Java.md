1. foreword

2. preface

3. acknowledgement

4. Consist of 

5. **Convey** [kənˈveɪ]  传达，表达

6. capture

7. **Loosely** [ˈluːsli] 是副词，意思是“松散地”或“不严格地

8. **Intend** [ɪnˈtɛnd] 是动词，意思是“打算”或“意图”

9. The book is not intended to be read from cover to cover 

10. The items are heavily cross-referenced so you can easily plot your own course through the book.

    > **Cross-referenced** [krɔːs ˈrɛfərənstɪd] 是形容词，表示“交叉引用的”

11. **Coverage** [ˈkʌvərɪdʒ] 是名词，表示“覆盖范围”或“报道范围”

12. Most items are **illustrated with** program examples.

    > Illustrate 说明

13. **Favor** [ˈfeɪvər] 意为“偏爱”或“恩惠”

14. you may have to add one or more import **declarations**, or other such **boilerplate**

    > **Import declarations** [ˈɪmpɔːrt dɪˈkleɪʃənz]：导入声明
    >
    > **Boilerplate** [ˈbɔɪlərpleɪt]：模板代码

15. **Deserve** [dɪˈzɜːrv] 是动词，意思是“应得”或“值得

16. The language supports four kinds of types: interfaces (including annotations), classes (including enums), arrays, and primitives

    > **Primitives** [ˈprɪmɪtɪvz]：基本类型

17. this book uses inheritance as a synonym for subclassing

    > **Inheritance** [ɪnˈhɛrɪtəns]  继承
    >
    > **Synonym** [ˈsɪnəˌnɪm]：同义词

18. The term exported API, or simply API, **refers** to the classes, interfaces, constructors, members, and serialized forms by which a programmer accesses a class, interface, or package.

    > **Refers** to  [rɪˈfɜːrz] 指的是
    >
    > **Serialized forms** [ˈsɪriəlaɪzd fɔːrmz]：序列化形式

19. how to ensure they are destroyed in a timely manner, and how to manage any cleanup actions that must precede their destruction.

    > **Timely manner** [ˈtaɪmli ˈmænər]：及时的方式
    >
    > **Precede** [prɪˈsiːd]：在...之前
    >
    > **Destruction** [dɪˈstrʌkʃən]：销毁

20. Programmers have been known to **get around this restriction** by providing two constructors whose parameter lists differ only in the order of their parameter types.

    > **Get around this restriction** [ɡɛt əˈraʊnd ðɪs rɪˈstrɪkʃən]：绕过这个限制

21. This allows **immutable** classes  to use **preconstructed** instances, or to cache instances as they’re constructed, and **dispense** them repeatedly to avoid creating unnecessary duplicate objects.

    > **Immutable** [ɪˈmjuːtəbl]：不可变的
    >
    > **Preconstructed** [ˌpriːkənˈstrʌktɪd]：预构造的
    >
    > **Dispense** [dɪsˈpɛns]：提供，分发
    >
    > **Duplicate** [ˈduːplɪkət]：重复的

22. It can greatly improve performance if **equivalent** objects are requested often, especially if they are expensive to create.

    >**Equivalent** [ɪˈkwɪvələnt]：等效的

23. The ability of static factory methods to return the same object from repeated **invocations** allows classes to maintain strict control over what instances exist at any time.

    > Repeated invocation - 重复调用；

24. it allows an **immutable** value class to make the guarantee that no two equal instances exist: 

    > Immutable - 不可变的；

25. This gives you great **flexibility** in choosing the class of the returned object.

    > **Flexibility** [flɪkˈsɪbɪləti]：灵活性

26. **Prior to** Java 8, interfaces couldn’t have static methods.

    > **Prior to** [ˈpraɪər tu]：在...之前

27. By convention, static factory methods for an interface named Type were put in a noninstantiable companion class named Types.

    > **Convention** [kənˈvɛnʃən]：惯例
    >
    > **Noninstantiable** [ˌnɒnɪnˈstænʃəˌeɪbl]：不可实例化的
    >
    > **Companion class** [kəmˈpænjən klæs]：伴生类

28. For example, the Java Collections Framework has forty-five **utility** implementations of its interfaces, providing **unmodifiable** collections, synchronized collections, and the like. Nearly all of these implementations are exported via static factory methods in one noninstantiable class (java.util.Collections). The classes of the returned objects are all **nonpublic**.

    > **Utility** [juːˈtɪləti]：工具
    >
    > **Unmodifiable** [ˌʌnˈmɒdɪfaɪəbl]：
    >
    > **Nonpublic** [ˌnɒnˈpʌblɪk]：非公开的

29. It is not just the bulk of the API that is reduced but the **conceptual** weight:

    > Bulk of API  api 的数量
    >
    > **Conceptual** [kənˈsɛptʃuəl]：概念上的
    >
    > **Weight** [weɪt]：复杂度

30. The programmer knows that the returned object has **precisely** the API specified by its interface, so there is no need to read additional class documentation for the implementation class. **Furthermore**, using such a static factory method requires the client to **refer to** the returned object by interface rather than implementation class, which is generally good practice.

    > **Precisely** [prɪˈsaɪsli]：精确地
    >
    > **Refer to** [rɪˈfɜːr tu]：引用
    >
    > **Furthermore** [ˈfɜːðərmɔːr]：此外
    >
    > > good practice  好的实践

31. As of Java 8, the restriction that interfaces cannot contain static methods was **eliminated**, so there is typically  little reason to provide a noninstantiable **companion** **class** for an interface.

    > **Eliminated** [ɪˈlɪmɪˌneɪtɪd]：取消,被放弃
    >
    > **Companion class** [kəmˈpænjən klæs]：伴生类

32. they return an instance of one of two subclasses, depending on the size of the **underlying** enum type

    > **Underlying** [ˈʌndərˌlaɪɪŋ]：基础的
    >
    > **Enum type** [ˈiːnʌm taɪp]：枚举类型

33. In the **absence** of such criteria, the API returns an instance of a default implementation.

    > **Absence** [ˈæbsəns]：缺乏

34. so it can be difficult to figure out how to instantiate a class that provides static factory methods instead of constructors.

    > - **Figure out** [ˈfɪɡər aʊt]：弄清楚
    > - **Instantiate** [ɪnˈstænʃieɪt]：实例化

35. In the meantime 在这个期间

36. by adhering to common naming conventions

    > - **Adhering** [ədˈhɪrɪŋ]：遵守  adhere
    > - **Conventions** [kənˈvɛnʃənz]：约定

37. This list is far from exhaustive

    >**Exhaustive** [ɪɡˈzɔːstɪv]：详尽无遗的
    >
    >**Far from** [fɑːr frəm]：远非

38. A type-conversion method that takes a single parameter and returns a corresponding instance of this type.

    > **Type-conversion method** [taɪp kənˈvɜːrʒən ˈmɛθəd]
    >
    > **Corresponding instance** [kəˈrɪspɒndɪŋ ˈɪnstəns]：相应的实例

39. An aggregation method that takes multiple parameters and returns an instance of this type that incorporates them

    > **Aggregation method** [æɡˈrɪɡeɪʃən ˈmɛθəd]：聚合方法
    >
    > **Incorporates** [ɪnˈkɔːpəreɪts]：包含

40. A more verbose alternative to from and of

    > **Verbose** [vɜːrˈboʊs] - 冗长的，啰嗦的

41. it pays to understand their relative merits

    > **Merits** [ˈmɛrɪts] - 优点，价值

42. culminating in a constructor with all the optional parameters

    > **Culminating** [ˈkʌlməˌneɪtɪŋ] - 达到高潮，最终达到

43. For brevity’s sake, only four optional fields are shown

    > **Brevity** [ˈbrɛvɪti] - 简洁，简短
    >
    > **Sake** [seɪk] - 目的，缘故

44. Typically this **constructor invocation** will require many parameters

45. In short, the telescoping constructor pattern works, but it is hard to write client code when there are many parameters, and harder still to read it.

    > **Telescoping** [ˈtɛlɪskoʊpɪŋ] - 层叠的

46. Long sequences of identically typed parameters can cause subtle bugs.

    > **Subtle** [ˈsʌtl] - 微妙的，难以察觉的
    >
    > **Bugs** [bʌɡz] - 错误，缺陷

47. If the client accidentally reverses two such parameters, the compiler won’t complain, but the program will misbehave at runtime

    > **Accidentally** [ˌæksɪˈdɛntəli] - 意外地，偶然地
    >
    > **Reverses** [rɪˈvɜːrsɪz] - 反转，颠倒
    >
    > **Complain** [kəmˈpleɪn] - 抱怨，指出错误
    >
    > **Misbehave** [ˌmɪsˈbɪheɪv] - 行为不当，出现错误或异常

48. if a bit wordy wordy-冗长的

49. Because construction is split across multiple calls, a JavaBean may be in an inconsistent state partway through its construction

    > **Inconsistent** [ˌɪnkənˈsɪstənt] - 不一致的，指的是状态不符合预期或规则
    >
    > **Partway through** [ˈpɑːrtweɪ θruː] - 在...过程中

50. Attempting to use an object when it’s in an inconsistent state may cause failures that are far removed from the code containing the bug and hence difficult to debug

    > **Far removed from** [fɑːr rɪˈmuːvd frəm] - 远离
    >
    > **Hence** [hɛns] - 因此，表示因果关系

51. A related disadvantage is that the JavaBeans pattern precludes the possibility of making a class immutable

    > **Precludes** [prɪˈkluːdz] - 排除
    >
    > **Immutable** [ɪˈmjuːtəbl] - 不可变的

52. but this variant is unwieldy and rarely used in practice

    > **Variant** [ˈvɛəriənt] - 变体
    >
    > **Unwieldy** [ʌnˈwiːldi] - 笨重的

53. Moreover, it can cause errors at runtime because the compiler cannot ensure that the programmer calls the freeze method on an object before using it.

    > **Moreover** [mɔːrˈoʊvər]：此外
    >
    > **Freeze method** [friːz ˈmɛθəd] - 冻结方法，指的是使对象的状态不可修改的方法

54. Instead of making the desired object directly, the client calls a constructor (or static factory) with all of the required parameters and gets a builder object.

    > **Desired** [dɪˈzaɪərd]：指的是想要的、期望的，描述某个目标或事物。

55. The builder’s setter methods return the builder itself so that invocations can be chained, resulting in a **fluent API**

    > **Fluent API** [ˈfluːənt ˈeɪpiːaɪ] - 流式 API

56. The Builder pattern simulates named optional parameters as found in Python and Scala.

    > **Simulates** [ˈsɪmjʊleɪts]：模拟

57. Validity checks were omitted for brevity. To detect invalid parameters as soon as possible, check parameter validity in the builder’s constructor and methods.

    > **Omitted** [oʊˈmɪtɪd]：省略
    >
    > **For brevity** [fɔːr ˈbrɛvɪti]：为了简洁
    >
    > **Detect** [dɪˈtɛkt]：检测

58. Check invariants involving multiple parameters in the constructor invoked by the build method

    > **Invariants** [ɪnˈveəriənts]：不变式，指在程序执行过程中始终保持不变的条件或规则

59. The Builder pattern is well suited to class hierarchies.

    > **Hierarchy** [ˈhaɪərɑːrki]：层次结构

60. Use a parallel hierarchy of builders, each nested in the corresponding class. Abstract classes have abstract builders; concrete classes have concrete builders. For example, consider an abstract class at the root of a hierarchy representing various kinds of pizza

    > **Parallel** [ˈpærəlɛl]：平行的
    >
    > **Nested** [ˈnɛstɪd]：嵌套的
    >
    > **Concrete classes** [ˈkɑːnkrɪt klæsɪz]：具体类，是可以实例化的类，通常实现了抽象类中定义的方法和属性。

61. This, along with the abstract self method, allows method chaining to work properly in subclasses, without the need for casts.

    > Casts 类型转换

62. This technique, wherein a subclass method is declared to return a subtype of the return type declared in the super-class, is known as covariant return typing. It allows clients to use these builders without the need for casting.

    > **Covariant return typing** [ˌkoʊveɪˈænt rɪˈtɜːrn ˈtaɪpɪŋ]：协变返回类型，指的是子类重写父类方法时，返回类型可以是父类返回类型的子类型。允许子类方法返回更加具体的类型，而父类方法返回更一般的类型。

63. A minor advantage of builders over constructors is that builders can have multiple **varargs** parameters because each parameter is specified in its own method

    > **Minor** [ˈmaɪnər]：小的
    >
    > Vararg [ˈvɑːrˌɑːrɡ]：可变参数

64. Alternatively, builders can aggregate the parameters passed into multiple calls to a method into a single field, as demonstrated in the addTopping method earlier.

    > **Alternatively** [ɔːlˈtɜːnətɪvli]：或者，表示一种选择或替代方案。
    >
    > **Aggregate** [ˈæɡrɪɡeɪt]：聚合

65. 

    