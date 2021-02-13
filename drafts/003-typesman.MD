# Typesman

- Submitted At: 2021-02-06
- Updated At: 2021-02-08
- Status: ~~In Progress~~ Rejected
- Repository: ~~_private_~~ _archived_

## Summary

Create a CLI tool to be used on TypeScript projects. The CLI tool is capable of:

1. Installing all required TypeScript `@types`.
2. Removing unused `@types`.
3. Removing stub `@types`.

## Motivation

[TypeScript](https://www.typescriptlang.org/) is a superset of JavaScript that enables static type checking to your JavaScript codes. TypeScript can help us reduce bugs early by enabling type-checking and enhance development experience by providing various hinting on several compatible IDEs. Unfortunately, the help TypeScript can provide is only limited to native JavaScript types and TypeScript-native typings. Anything beyond that must be provided explicitly by the user. This is inconvenient since we usually use more than one node modules on a single project.

Usually, is the module creator responsibility to provide correct typings for their package. However, custom typings can only be provided in a TypeScript-based modules. This is inconvenient since not all modules are created using TypeScript.

Fortunately, TypeScript provides solution for any JavaScript modules typing problem by using the `@types` system. By using the correct `@types`, TypeScript can also provide hinting and type-checking on any module. Anyone can contribute by creating a type-definition for a module and submitting them to [DefinitelyTyped](https://definitelytyped.org/).

Unfortunately, the `@types` system is not hassle-free solution since anyone must install and manage all of their required types.

## Stack

A good ol' plain JavaScript, on Node plus TypeScript.

## Current Progress

- [x] Study about how CLI-based app is executed on Node.
- [x] Determine required libraries.
- ~~[ ] Implement!~~

## Rejection Reason

[TypeSync](https://github.com/jeffijoe/typesync) provides the same capability. Re-invent the wheel is a bad idea.
