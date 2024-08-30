This package provides a template project for unit test, which contains dependencies for `NUnit` and `Moq`, with a target framework of `.net8.0` by default.

## Dependencies

|Package|Version|Description|
|:------|:------|:----------|
|coverlet.collector|6.0.2|Coverlet is a cross platform code coverage library for .NET, with support for line, branch and method coverage.|
|Microsoft.NET.Test.Sdk|17.11.0|The MSbuild targets and properties for building .NET test projects.|
|Moq|4.20.70|Moq is the most popular and friendly mocking framework for .NET.|
|NUnit|4.2.1|NUnit is a unit-testing framework for all .NET languages.NUnit can be used for a wide range of testing, from unit testing with TDD to full-fledged system and integration testing.|
|NUnit.Analyzers|4.3.0|This package includes analyzers and code fixes for test projects using NUnit 3+.The analyzers will mark wrong usages when writing tests, and the code fixes can be used to used to correct these usages.|

## Remarks

This template project does not reference `NUnit3TestAdapter`, which should be referenced if the IDE is Visual Studio 2017+.
Also, `NUnit.ConsoleRunner` is not referenced.