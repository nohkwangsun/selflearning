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
---
