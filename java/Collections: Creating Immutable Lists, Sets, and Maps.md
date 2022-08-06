### Immutable List Static Factory Methods

The List.of static factory methods provide a convenient way to create immutable lists.

A list is an ordered collection, where duplicate elements are typically allowed. Null values are not allowed.

The syntax of these methods is:

```java
List.of()
List.of(e1)
List.of(e1, e2)         // fixed-argument form overloads up to 10 elements
List.of(elements...)   // varargs form supports an arbitrary number of elements or an array
```


#### JDK 8

```java
List<String> stringList = Arrays.asList("a", "b", "c");
stringList = Collections.unmodifiableList(stringList);
```
#### JDK 9

```java
List stringList = List.of("a", "b", "c");
```

See [Immutable List Static Factory Methods](https://docs.oracle.com/javase/9/docs/api/java/util/List.html#immutable).

