# GraalPy Demos and Guides

This directory contains demo applications and guides for [GraalPy](https://www.graalvm.org/python/).

*Tip: open this directory in IntellIJ IDEA. It should offer to load all Maven projects.*

## Demos

- [Minimal Java application that embeds GraalPy](graalpy-starter/README.md)
- [Minimal Java application that embeds `openai` Python package with GraalPy](graalpy-openai-starter/README.md)
- [Embed `qrcode` Python package with GraalPy in JBang](graalpy-jbang-qrcode/README.md)

## Guides

- Use GraalPy and GraalPy Maven plugin in a [Java SE application](graalpy-javase-guide/README.md)
- Use GraalPy with popular Java frameworks, such as [Spring Boot](graalpy-spring-boot-guide/README.md) or [Micronaut](graalpy-micronaut-guide/README.md)
- Use GraalPy Maven plugin to install and use Python packages that rely on [native code](graalpy-native-extensions-guide/README.md), e.g. for data science and machine learning
- Manually [install Python packages and files](graalpy-custom-venv-guide/README.md) if the Maven plugin gives not enough control
- [Freeze](graalpy-freeze-dependencies-guide/README.md) transitive Python dependencies for reproducible builds
- [Migrate from Jython](graalpy-jython-guide/README.md) to GraalPy
