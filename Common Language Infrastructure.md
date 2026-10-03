**Standard Comprehension**: The Common Language Infrastructure (CLI) is an open specification and technical standard originally developed by

$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ Microsoft and standardized by ISO/IEC (ISO/IEC 23271) and Ecma International (ECMA 335) that describes

$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ executable code and a runtime environment that allows multiple high-level languages to be used on different

$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ computer platforms without being rewritten for specific architectures. This implies it is platform agnostic. The .NET

$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ Framework, .NET and Mono are implementations of the CLI. The metadata format is also used to specify the API

$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ definitions exposed by the Windows Runtime.

**5 Aspects of the CLI Specification**

| Aspect names | Aspect descriptions |
| :------------: | :-------------------: |
| The Common Type System (CTS) | A set of data types and operations that are shared by all CTS-compliant programming languages. |
| The Metadata | Information about program structure is language-agnostic, so that it can be referenced between languages and tools, making it easy to work with code written in a language the developer is not using. |
| The Common Language Specification (CLS) | The CLS, a subset of the CTS, are rules to which components developed with/for the supported languages must adhere. They apply to consumers (developers who are programmatically accessing a component that is CLS-compliant), frameworks (developers who are using a language compiler to create CLS-compliant libraries), and extenders (developers who are creating a tool such as a language compiler or a code parser that creates CLS-compliant components). |
| The Virtual Execution System (VES) | The VES loads and executes CLI-compatible programs, using the metadata to combine separately generated pieces of code at runtime. All compatible languages compile to Common Intermediate Language (CIL), which is an intermediate language that is abstracted from the platform hardware. When the code is executed, the platform-specific VES will compile the CIL to the machine language according to the specific hardware and operating system. In the CLI standard initially developed by Microsoft, the VES is implemented by the Common Language Runtime (CLR). |
| The Standard Libraries | A set of libraries providing many common functions, such as file reading and writing. Their core is the Base Class Library (BCL). |

**Standard History**

| Time | Events |
| :----: | :-----: |
| August 2000 | Microsoft, Hewlett-Packard, Intel, and others worked to standardize CLI. |
| December 2001 | CLI was ratified by the Ecma. |
| April 2003 | CLI was with ISO/IEC standardization. |
| July 2009 | Microsoft added C# and CLI to the list of specifications that the Microsoft Community Promise applies to, so anyone can safely implement specified editions of the standards without fearing a patent lawsuit from Microsoft. To implement the CLI standard requires conformance to one of the supported and defined profiles of the standard, the minimum of which is the kernel profile. The kernel profile is actually a very small set of types to support in comparison to the well known core library of default .NET installations. However, the conformance clause of the CLI allows for extending the supported profile by adding new methods and types to classes, as well as deriving from new namespaces. But it does not allow for adding new members to interfaces. This means that the features of the CLI can be used and extended, as long as the conforming profile implementation does not change the behavior of a program intended to run on that profile, while allowing for unspecified behavior from programs written specifically for that implementation. |
| 2012 | Ecma and ISO/IEC published the new edition of the CLI standard. |

**CLI Implementations**

| Implementation names | Descriptions |
| :--------------------: | :------------: |
| .NET Framework | Microsoft's original commercial implementation of the CLI. It only supports Windows. It was superseded by .NET in November 2020. |
| .NET | Previously known as .NET Core, is the free and open-source multi-platform successor to .NET Framework, released under the MIT License |
| .NET Compact Framework | Microsoft's commercial implementation of the CLI for portable devices and Xbox 360. |
| .NET Micro Framework | an open source implementation of the CLI for resource-constrained devices. |
| Mono | an alternative open source implementation of CLI and accompanying technologies, mainly used for mobile and game development. |
| DotGNU | a decommissioned part of the GNU Project started in January 2001 that aimed to provide a free and open source software alternative to Microsoft's .NET Framework. |

**Useful Sources**

| Source names | Source URLs |
| :------------ | :----------- |
| Archived webpage for https://www.iso.org/standard/58046.html | https://web.archive.org/web/20230702003946/https://www.iso.org/standard/58046.html |
| ECMA-335 | https://ecma-international.org/publications-and-standards/standards/ecma-335/ |
| Archived webpage for https://www.ecma-international.org/publications-and-standards/standards/ecma-335/ | https://web.archive.org/web/20231016101943/https://www.ecma-international.org/publications-and-standards/standards/ecma-335/ |
| AdaCore First to Bring True .NET Integration to Ada | https://www.adacore.com/press/adacore-first-to-bring-true-net-integration-to-ada |

**Related Sources**

| Source names | Source URLs |
| :------------ | :----------- |
| Archived webpage for http://articleworld.org/A_Sharp_%28.NET%29 | https://web.archive.org/web/20081016062426/http://articleworld.org/A_Sharp_%28.NET%29 |
