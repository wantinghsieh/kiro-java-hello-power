---
name: "java-hello"
displayName: "Java Hello World"
description: "A simple power for writing Java Hello World programs"
keywords: ["java", "hello world"]
author: "wthsieh"
---

# Java Hello World Power

A minimal power with no MCP server, only instructions.

## When asked for a Java Hello World program

1. Create `Main.java`:

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

2. Compile it: `javac Main.java`
3. Run it: `java Main`
4. Expected output: `Hello, World!`
