# Angular

## Project Creation and Deployment in Local
**Q**. How to create a new Angular project?

**A**. To create an angular project we need following dependencies.
1. Node.js must be installed on the machine.
1. Angular cli should be installed on the machine. If not already installed then cli can be installed with the command.
    ```
    npm install -g @angular/cli
    ```
1. After this a new angular project can be created with the command.
    ```
    ng new <project_name>
    ```
    This will create a new angular project and will setup all the required dependencies.


**Q**. What are the options available to customize the project setup?

**A**. Creating the project using Angular cli gives us the following options to customize the project setup.
1. Option to add Angular routing.
1. Stylesheet format.


**Q**. How to run Angular project in local?

**A**. To run Angular project in local, go to project root directory on terminal and use the command `ng serve`. It will start a development server on port 4200.


**Q**. How to run Angular project on a different port than 4200?

**A**. To run angular on a different port, run the command `ng serve --port=<port>`.


**Q**. I am not able to access my Angular application on a different machine connected in the same local network. What to do?

**A**. By default, the server started by `ng serve` command will only listen to the host machine. To access the application from other machines connected to same local network run the command `ng serve --host=0.0.0.0`.


## Angular Concepts
**Q.** How an Angular project is structured?

**A.** An Angular project is structured in components and modules. There are some other important structures like services, pipes, directives etc to work with component and modules.


**Q.** What is interpolation?

**A.** Interpolation is the way to use values of JavaScript objects in HTML templates. Interpolations have one way binding. Meaning, when the value in the object changes, the new value automatically reflects in the HTML.


**Q.** What is a pipe in Angular?

**A.** A pipe is a handy way to transform values being shown in the HTML using interpolation. Below is an example of a pipe.

    ```
    {{ name | uppercase }}
    ```

This will show the name always in uppercase.

Pipes can accept parameters to transform the values. Also, pipes can be chained.

### Routing
**Q.** How to routing in Angular works?

**A.** Angular provides a rich routing features.


**Q.** How to pass static data to a route?

**A.**


**Q.** How to pass parameters to a route?

**A.**


**Q.** How to pass request parameters to a route?

**A.**


**Q.** What is the difference between `RouterModule.forRoot()` and `RouterModule.forChild()`?

**A.**



```
**Q.**

**A.**

```
#### Guard

### Directive

### Component

### Module

### Interceptor

### Provider

### Service

```
**Q.**
**A.**
```
