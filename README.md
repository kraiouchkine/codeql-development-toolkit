<table style="border: none" cellspacing="0" cellpadding="0">
<tr>
<td><img src="assets/qlt-logo.png"></td>
<td><h1 style="border: none">The CodeQL Development Toolkit (QLT)</h1></td>
</tr>
</table>

*Please Note: This project is an Open Source Tool maintained by [@advanced-security/es-advanced-security](https://github.com/orgs/advanced-security/teams/es-advanced-security). It is not an officially supported product of Github, Inc and is provided 
"as is", without warranty of any kind, express or implied, including but not limited to
the warranties of merchantability, fitness ofr a particular purpose and noninfringement.*

The CodeQL Development toolkit is a tool for making common CodeQL development workflows easier. Some of its key features include:

- Creation and management of new CodeQL queries and query packs.
- Creation and management of new CodeQL unit tests and unit test packs. 
- Integration with common automation systems such as GitHub Actions which adds support for:
    - Automated query testing 
    - The ability to test your queries on sets of example databases
    - The ability to do performance testing
    - The ability to do regression testing (false positives / false negatives)

Below is a guide showing you how to perform the most common tasks with the CodeQL Development Toolkit

# Installation

You can install QLT by grabbing a release on the releases page. We currently ship builds for Linux x86_64. There are no dependencies to install. Just unpack the bundle and run the binary `qlt` in the unpacked directory. 

# General Command Structure 

QLT is organized groups of functionality called "Features." Within those features, the functionality of that feature is split into 4 verbs that describe the functionality provided:


Which In the following sections you will find documentation of those features as well as examples of their most common usages. 

## Usage 

```
Description: QLT: The CodeQL Development Toolkit

Usage:
  CodeQLToolkit.Core [command] [options]

Options:
  --base <base>                           The base path to find the query repository. [default: C:\Projects\codeql-development-lifecycle-toolkit]
  --automation-type <actions> (REQUIRED)  The base path to find the query repository. [default: actions]
  --version                               Show version information
  -?, -h, --help                          Show help and usage information

Commands:
  version     Get the current tool version.
  query       Use the features related to query creation and execution.
  codeql      Use the features related to managing the version of CodeQL used by this repository.
  test        Features related to the running and processing of CodeQL Unit Tests.
  pack        Features CodeQL pack management and publication.
  validation  Features related to the validation of CodeQL Development Repositories.
```

# Contributing


# License 

This project is release under the MIT OSS License. Please see our [LICENSE](LICENSE) for more information. 
