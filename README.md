# Mixed Data Input with Scanner

This repository contains a simple Java program that is an excellent example for learning a crucial aspect of the `Scanner` class: handling mixed data types. The program demonstrates how to read an **integer (`int`)** and then multiple **lines of text (`String`)** from the user.

A key learning point in this code is the use of `sc.nextLine()` after `sc.nextInt()`. This is a best practice to consume the leftover newline character from the integer input, preventing a common bug where the next line of text would be skipped.

---

## How to Run This Code

You can run this program on any machine with the **Java Development Kit (JDK)** installed.

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    ```

2.  **Navigate to the project folder:**
    ```sh
    cd seu-repositorio/
    ```

3.  **Compile the Java file:**
    ```sh
    javac EntradaDeDados2.java
    ```

4.  **Run the compiled class:**
    ```sh
    java EntradaDeDados2
    ```

The program will execute and wait for your input. The output will look similar to this example:
