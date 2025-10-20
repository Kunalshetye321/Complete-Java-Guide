# 🏷️Introduction to Java

## 📂Programming language
🔹 Programming language is used to communicate with machines.

```mermaid
flowchart TD
    A[Programming language] --> B[Low-level language]
    A --> C[High Level Language]
```

## 📂Low-level language
🔹 A language which is easily readable & understandable by maching is known as low-level language or machine language. <br>
⚡ Binary language

## 📂High-level language
🔹 A language which is easily readable, understandable & instructable by human or programmer is known as high level language. <br>
⚡ Java, C++, python, etc


## 📂Platform dependent
🔹If we write a program using one platform an it is executable in same platform is known as platform dependent language. <br>
⚡Eg. C language
```mermaid
flowchart TD
    A[Windows] --> |Executable|B[Windows]
    A --> |Not Executable|C[MacOS]
    A --> |Not Executable|D[Linux]
```

## 📂Platform independent
🔹If we write a program in one platform it is executable in any other platform is known as platform independent language. <br>
⚡Eg. Java <br>
🔸Java is executable in windows, macOS and even Linux
```mermaid
flowchart TD
    A[Windows] --> |Executable|B[Windows]
    A --> |Executable|C[MacOS]
    A --> |Executable|D[Linux]
```