# Net Configuturation Demo

A frequent question among developers is how does an ASP.NET Core application
running in K8s handle configuration chages. Does it automatically reload
configuration when a ConfigMap or Secret is updated?

This demo repository showcases the IOption pattern in ASP .NET Core for
different app configuration scenarios, and how to handle configuration changes
when running in a Kubernetes environment.

## Naming Conventions

This demo uses naming conventions as you would expect:

Kebab-case:

- repository name

PascalCase for:

- C# classes, interfaces, properties, methods, namespaces, enums, and public
  members
- Project names
- Solution names
