# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Java project (`lost-and-found`) set up with IntelliJ IDEA, targeting **JDK 22** (`openjdk-22`). Currently it contains a single entry point class. Source files live in `src/`, and compiled output goes to `out/`.

## Build & Run

**Compile from command line:**
```bash
javac -d out src/Main.java
```

**Run:**
```bash
java -cp out Main
```

**With IntelliJ IDEA:** Open the project and use the built-in run/build actions. The `.iml` and `.idea/` configuration files are already committed.
