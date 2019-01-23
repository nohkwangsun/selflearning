---
# SCALA
---

scala = scalable + langulage

multi paradigm : OOP + FP

---
# INSTALL
---

- JAVA
 1. DOWNLOAD JDK (https://jdk.java.net/8/)
 2. SET JAVA_HOME
 3. SET PATH

- Scala
 1. DOWNLOAD Scala (https://www.scala-lang.org/download)
 2. SET SCALA_HOME
 3. SET PATH

---
# Hello, World!
---

```
$ cat << EOF >> helloworld.scala
object HelloWorld {
  def main(args: Array[String] {
    println("Hello, World!")
  }
}
EOF

$ scalac helloworld.scala # Class명과 달라도 됨

$ scala helloworld
Hello, World!
```

---
```
$ cat << EOF >> helloworldapp.scala
object HelloWorld extends App {
  println("Hello, World!")
}
EOF

$ scalac helloworldapp.scala # Class명과 달라도 됨

$ scala helloworldapp
Hello, World!
```

---
# REPL
---

```
$ scala

scala>

scala> println("Hello, World!")
Hello, World!

scala> 1
res0: Int = 1

scala> println(res0)
1

```
---
# LINK
---

- [Scala Cheat Sheet](https://alvinalexander.com/scala/scala-cheat-sheet-reference-examples)
- [Case Class](https://alvinalexander.com/scala/fp-book/quick-review-of-scala-case-classes)
- [Implicit Class](https://alvinalexander.com/scala/scala-2.10-implicit-class-example)
- [Implicit Method Argument](https://alvinalexander.com/scala/scala-implicit-method-arguments-fields-example)

---
# END
