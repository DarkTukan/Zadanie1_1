---
name: Plain Java console scope
description: The project's explicitly requested Java-only console application scope.
---

Keep this project a dependency-free Java 21 console application. Do not add web frameworks, servers, frontends, or databases unless the user changes the scope.

**Why:** the user explicitly requested a minimal console application and excluded web infrastructure.

**How to apply:** keep changes centered on the Java entry point and console behavior; use Java 21 tooling.
