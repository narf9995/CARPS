# Coding Analogy
Generally speaking applications/programs, frameworks, & libraries are all code written by someone else that helps you perform some common tasks without having to "reinvent the wheel" & code it all by yourself.

Framework/libraries provide reusable services that encapsulate lower-level functionalities by providing an higher abstraction to the inner complexities of certain features.

Typically libraries stay static within the development of an application, at least besides occasional upgrades: application code utilises the functionality provided by the modules to create a specific behaviour for the logical interaction between users and a domain of data in a generally tighter-defined environment.

So, while the application code is constantly changing as the application evolves and develops, framework and libraries provides fundamental building blocks behind the structure of the product.

> ”In programming, it always comes down to one thing: choosing the right tool for the job. Programmers are faced with many tools. Too many. Have you heard the expression “paradox of choice”? That sums up the IT world. The “shall we build our application with a library or a framework?” is just one of many decisions facing us, but it can be an important one. A team with many junior developers may be better off with a framework, enforcing structure and standards, telling them how to build the app; an application that’s not run-of-the-mill and has niche functionality might work better if a library is used, to allow greater flexibility and control.” — Dave Clayton

- An *application/program* is computer software designed to help a user perform specific tasks.
- A computing platform includes a hardware architecture and a software framework that allow application software to run—for example, the operating system and programming languages.
- A software framework helps facilitate software development by providing generic capabilities that can be changed or configured to create a specific software application.

- 

## Details
- The technical difference between a framework and library lies in a term called **Inversion of Control**.
- When you use a library, you are in charge of the flow of the application.
- You are choosing when and where to use the library in your code, but you provide the overall structure of the code.
- When you use a framework, the framework is in charge of the flow.
- It provides some places for you to plug in your code, but it calls the code you plugged in as needed.

## Conclusion
- A framework inverts the control of the program, it tells the developer what they need.
- A library doesn’t, the programmer calls the library where and when they need it.
