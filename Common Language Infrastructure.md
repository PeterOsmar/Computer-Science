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

**Standard History**: In August 2000, Microsoft, Hewlett-Packard, Intel, and others worked to standardize CLI. By December 2001, it was ratified by the Ecma, with ISO/IEC standardization following in April 2003.

**Useful Sources**

| Source names | Source URLs |
| :------------ | :----------- |
| The Special Interest Group on Ada | https://www.sigada.org/ |
| Ada compiler for the .NET Framework | https://asharp.martincarlisle.com/ |
| Archived webpage for http://www.adacore.com/2007/09/10/adacore-first-to-bring-true-net-integration-to-ada/ | https://web.archive.org/web/20071028102900/http://www.adacore.com/2007/09/10/adacore-first-to-bring-true-net-integration-to-ada/ |
| The Mysterious Existence of A# | https://seattlewebsitedevelopers.medium.com/the-mysterious-existence-of-a-325d870ee6a4 |
| AdaCore First to Bring True .NET Integration to Ada | https://www.adacore.com/press/adacore-first-to-bring-true-net-integration-to-ada |

**Related Sources**

| Source names | Source URLs |
| :------------ | :----------- |
| Archived webpage for http://articleworld.org/A_Sharp_%28.NET%29 | https://web.archive.org/web/20081016062426/http://articleworld.org/A_Sharp_%28.NET%29 |
