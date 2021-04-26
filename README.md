# MVC Letter to Friend in C# and ASP.net Core Framework

### Authors _Shanen Cross and Tyler Sinks_
_originally built Sunday April 25, 2021_

## Description
* runs in a browser
* takes in sender name, recipient name via form
* populates inputs to letter to a friend
* written in C# using the .Net framework (v5.0.100)
* MVC and ASP.net Core

| form fields                  |
|------------------------------|
| sender                       |
| recipient                    |
| location                     |

## Setup and Installation
_the code depends on just a few built-in namespaces / using directories which will be brought into the picture by following these steps_

1. Use a termainl or console to navigate to the desired directory for this project
2. Clone the project to your machine:
> ` $ git clone https://github.com/sinkstyt/FriendLetter.Solution.git `
3. Change directory into the project's root folder:
> ` $ cd FriendLetter.Solution `
4. Restore the project's dependencies:
> ` $ dotnet restore FriendLetter `
5. To build the project:
> ` $ dotnet build `
6. To launch in the browser:
> ` $ cd FriendLetter `
> ` $ dotnet run `
7. Or, to examine the files in VS Code instead of step 6:
> ` $ code . `

#### For those completely new to C# and dotnet, please see these detailed instructions:
* [Installing C# and .NET](https://www.learnhowtoprogram.com/c-and-net-part-time-c-and-react-track/getting-started-with-c/installing-c-and-net)
* [MSTest Configuration and Setup](https://www.learnhowtoprogram.com/c-and-net/test-driven-development-with-c/mstest-configuration-and-setup)

### Specs
| Test                                                                    | Input                    | Output |
|-------------------------------------------------------------------------|--------------------------|--------|
| Bread constructor returns an instance whose type is Bread               | type of (new Bread)      | Bread  |
| Bread instance returns an integer at field LoavesInOrder                | Get(LoavesInOrder)       | 4      |
| Static method PriceOfBreads returns integer when LoavesInOrder is 1     | Bread.PriceOfBreads()    | 5      |
| PriceOfBreads returns accurate integer when LoavesInOrder is 5          | Bread.PriceOfBreads()    | 20     |
| Pastry constructor returns an instance whose type is Pastry             | type of (new Pastry)     | Pastry |
| Pastry instance returns integer from field PastriesInOrder              | Get(PastriesInOrder)     | 32     |
| Static method PriceOfPastries returns integer when PastriesInOrder is 1 | Pastry.PriceOfPastries() | 2      |
| PriceOfPastries returns accurate integer when PastriesInOrder is 17     | Pastry.PriceOfPastries() | 19     |

### Technologies Used
* _C# and .net5.0_
* _MS Test_
* `git` _and GitHub_
* [C# and .Net curriculum](https://www.learnhowtoprogram.com/c-and-net)
* _VS Code_

### License
* [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/saoud/csharp-TDD-template/blob/main/LICENSE)
* Copyright 2021 :copyright: Tyler Sinks

## Known Bugs
* no known bugs
* please feel free to reassess this claim
* changes &amp; suggestions are welcomed

### Contact
[email the author](mailto:tyler.sinks@gmail.com)