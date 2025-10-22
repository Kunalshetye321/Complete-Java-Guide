# 🏷️Difference between JVM, JRE & JDK

## 📂JVM
🔹 1. JVM stands for java virtual machine. <br>
🔹 2. JVM physicall does not exist hence virtual. <br>
🔹 3. JVM takes byte code as input and generates binary code as output. <br>
🔹 4. JVM consist of interpreter and JIT. <br>

<br>
⚡The Java compiler, javac, is platform-dependent. While Java bytecode (.class files) is platform-independent, allowing it to be run on any system with a compatible Java Virtual Machine (JVM).
<br>

🔹 5. Interpreter <br>
   📑 a. Interpreter checks and executes bytecode simultaneously.
   📑 b. Interpreter takes more time to execute.
<br>

🔹 6. JIT (Just-In-Time) <br>
   📑 a. JIT is used to increase the speed of execution. <br>
   📑 b. JIT identifies the set of programs which are having same functionality then compiles at once & gives to the interpreter. <br>

![JVM consist of interpreter & jit](../helper/assets/images/basics/JDK_JRE_JVM.jpg)

## 📂JRE (Java runtime environment)
🔹 1. JRE provides an environment to run a java program. <br>
🔹 2. JRE physically exist. <br>
🔹 3. JRE consist of inbuilt libraries and jvm. <br>

## 📂JDK (Java development kit)
🔹 1. JDK provides an environment to run & develop a java program. <br>
🔹 2. JDK physically exist. <br>
🔹 3. JDK consist of development tools and jre. <br>

