# Java EE Exercises

This directory contains Maven-based Java web and database practice modules.

> Academic context: this directory contains course lab or coursework solutions.

## Modules

- `bean/`: JavaBean practice
- `jdbc/`: JDBC database access practice
- `trans/`: transaction handling practice

## Build

Build a module from its directory:

```powershell
cd jdbc
mvn clean package
```

Each module has its own `pom.xml`. Configure its database properties before running database-dependent examples.