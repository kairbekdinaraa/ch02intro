# ch02intro
Introduction to OS, Chapter 02

Read [Introduction to OS](http://pages.cs.wisc.edu/~remzi/OSTEP/intro.pdf) and answer the following review questions.

1. **What is an operating system? What does it do?**  the low-level software that supports a computer's basic functions, such as scheduling tasks and controlling peripherals.
2. **What is virtualization?** Виртуализация - это технология, которая позволяет создавать полезные ИТ-услуги, используя ресурсы, которые традиционно привязаны к оборудовани.
3. **How does an OS provide access to its features?** in order to allow users to tell the OS what to do and thus
make use of the features of the virtual machine (such as running a pro-
gram, or allocating memory, or accessing a file), the OS also provides
some interfaces (APIs) that you can call. A typical OS, in fact, exports
a few hundred system calls that are available to applications. Because
the OS provides these calls to run programs, access memory and devices,
and other related actions, we also sometimes say that the OS provides a
standard library to applicatio
4. **What illusion does a virtualized CPU provide?**  It turns out that the operating system, with some help from the hard-
ware, is in charge of this illusion, i.e., the illusion that the system has a
very large number of virtual CPUs. Turning a single CPU (or small set of
them) into a seemingly infinite number of CPUs and thus allowing many
programs to seemingly run at once is what we call virtualizing the CPU,
the focus of the first major part of this book.
    - **How does this affect the user experience?**  Doing so runs a
job in the background in the tcsh shell, which means that the user is able to immediately issue
their next command, which in this case is another program to run. The semi-colon between
commands allows us to run multiple programs at the same time in tcsh. If you’re using a
different shell (e.g., bash), it works slightly differently; read documentation online for details
    - **How does this affect the developer experience?** your answer goes here 
    - **What if the CPU were not virtualized?** your answer goes here 
5. **What is a memory address?** Адрес памяти - это уникальный идентификатор, используемый устройством или процессором для отслеживания данных.
6. **What is memory virtualization?** Виртуализация памяти - система, которая выполняется в виртуальной машине, ожидает физическое адресное пространство на нулевом уровне, которое обеспечивается реальным оборудованием.
    - **Why would we want this?** занимает мало мест
8. **What happens if you write a C/C++ program that writes past the end of an array?**  если мы добавим в конце несколько байтов эти ничего не изменяет
      - **Can this affect other programs?**  если добавим достаточно много,то может случится странные вещи
9. **What is a thread?** thread is the smallest processing unit whose execution can be assigned by the operating system kernel.
10. **Why would we ever write a multi-threaded program?** here
11. **What is atomicity?** your answer goes h10 Многопоточность необходима, когда мы опираемся на производительность. Когда мы архивируем, кодируем видео - в любых ресурсоемких процессах. Эти вещи действительно должны использовать несколько потоков.
    - **Is a C/C++ statement atomic?** your answer goes here 
    - **Is a Java statement atomic?** your answer goes here 
    - **Is an assembler statement atomic?** your answer goes here 

13. **What does persistence mean?** persistence относится к объектам и характеристикам процесса, которые продолжают существовать даже после прекращения процесса, который его создал, или работающего на нем устройства отключается. Когда объект или состояние создается и должно быть постоянным, оно сохраняется в энергонезависимой памяти, например, на жестком диске, в зависимости от временного файла или оперативной памяти (RAM).

14. **How does OS hard drive virtualization differ from CPU & memory virtualization?** your answer goes here 
15. **How does running multiple programs at the same time increase CPU efficiency?** your answer goes here 
16. **What is multiprogramming?** Multiprogramming is a way of organizing the execution of several programs on one computer.
