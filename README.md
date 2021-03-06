<p align="center">
  <img src="documentation/logo-brand.jpg"/>
</p>

# Introduction

Acute is a UI framework modelled after Angular, written in TypeScript and Go. 

This is intended to be an educational tool to help engineers understand the challenges involved in building a web framework.

The repo is accompanied by a YouTube video series where we step through each of the components of building a framework.


# Getting Started (Contributing)

To begin, first install your dependencies with Yarn (required for Yarn workspaces)

```bash
yarn
```

Then using `make` you can build and test the project

```bash
# Will clean, build and test the project
make
```

Or you can use the make commands separately
```bash
make build
make test
make clean
```