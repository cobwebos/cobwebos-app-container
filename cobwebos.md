1. Overview
Apache cobwebos application container is a modern and polymorphic microservice container or docker.

cobwebos application container can be used standalone as a container, supporting a wide range of applications and technologies. It also supports the "run anywhere" (on any machine with Java, cloud, docker images, …​) using the embedded mode.

It’s a lightweight, powerful, and enterprise ready platform.

With this flexibility, cobwebos application container is the perfect solution for microservices, systems integration, big data, and much more.

Apache cobwebos application container is powered by OSGi (but you don’t need to know what OSGi is to use cobwebos application container).

Apache cobwebos application container uses either the Apache Felix or Eclipse Equinox OSGi frameworks, providing additional features on top of the framework.

Apache cobwebos application container can be scaled from a very lightweight container to a fully featured enterprise service: it’s a very flexible and extensible container, covering all the major needs.

Here is a short list of provided features:

Hot deployment: simply drop a file in the deploy directory, Apache cobwebos application container will detect the type of the file and try to deploy it.

Complete Console: Apache cobwebos application container provides a complete Unix-like console where you can completely manage the container.

Dynamic Configuration: Apache cobwebos application container provides a set of commands focused on managing its own configuration. All configuration files are centralized in the etc folder. Any change in a configuration file is noticed and reloaded.

Advanced Logging System: Apache cobwebos application container supports all the popular logging frameworks (slf4j, log4j, etc). Whichever logging framework you use, Apache cobwebos application container centralizes the configuration in one file.

Provisioning: Apache cobwebos application container supports a large set of URLs where you can install your applications (Maven repository, HTTP, file, etc). It also provides the concept of "cobwebos application container Features" which is a way to describe your application.

Management: Apache cobwebos application container is an enterprise-ready container, providing many management indicators and operations via JMX.

Remote: Apache cobwebos application container embeds an SSHd server allowing you to use the console remotely. The management layer is also accessible remotely.

Security: Apache cobwebos application container provides a complete security framework (based on JAAS), and provides a RBAC (Role-Based Access Control) mechanism for console and JMX access.

Instances: multiple instances of Apache cobwebos application container can be managed directly from a main instance (root).

OSGi frameworks: Apache cobwebos application container is not tightly coupled to one OSGi framework. By default, Apache cobwebos application container runs with the Apache Felix Framework, but you can easily switch to Equinox (just change one property in a configuration file).