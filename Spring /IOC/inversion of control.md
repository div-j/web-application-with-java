# Spring IoC Overview

Spring IoC is a fundamental concept within the Spring Framework. IoC refers to the inversion of control, a design principle in software development. In traditional programming, the flow of control is determined by the program itself. However, in the case of IoC, the control flow is inverted – the framework or container is responsible for managing the flow.

## Key Points about Spring IoC

### Container

The core of Spring IoC is the container. The container manages the components of your application, known as beans. There are two types of containers in Spring: the `BeanFactory` and the more powerful `ApplicationContext`.

### Beans

In the Spring context, a bean is an object that is created, managed, and wired by the Spring IoC container. Beans are the building blocks of a Spring application.

### Configuration

Spring IoC relies heavily on configuration. Configuration in Spring can be done either through XML-based configuration, Java-based configuration, or a combination of both. The configuration defines how beans are created, wired, and managed.

### Dependency Injection (DI)

DI is a core concept in Spring IoC. It's a design pattern where the dependencies of an object are injected into it rather than the object creating its dependencies. This promotes loose coupling and easier unit testing.

### Annotations

Spring IoC supports annotations for configuration. Annotations like `@Component`, `@Service`, `@Repository`, and `@Autowired` are commonly used to mark classes as Spring components and to inject dependencies.

### Lifecycle Management

Spring IoC container manages the complete lifecycle of beans, from creation to destruction. It provides hooks for initializing and cleaning up resources.
