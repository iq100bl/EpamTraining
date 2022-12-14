# Insertion Sort Algorithm

An intermediate level task for practicing insertion sort algorithm.

The task is to implement insertion sort algorithm using loops and recursion.

Read more on [insertion sort topic](https://www.google.com/search?q=insertion+sort):

* [Insertion Sort](https://en.wikipedia.org/wiki/Insertion_sort)
* [Сортировка вставками](https://habr.com/ru/company/otus/blog/510244/)
* [Visualgo](https://visualgo.net/)


## Get the Project

* [Open a project from your remote repository](https://docs.microsoft.com/en-us/visualstudio/get-started/tutorial-open-project-from-repo) or [get your local copy](https://docs.microsoft.com/en-us/azure/devops/repos/git/clone#clone-from-another-git-provider) with Visual Studio.


## Complete the Task

Use loop statements and recursion calls only to solve the task. Methods "InsertionSort" and "RecursiveInsertionSort" are implemented as [extension methods](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/extension-methods). It's **not allowed** to use a static or instance methods of the [Array class](https://docs.microsoft.com/en-us/dotnet/api/system.array) or any extension method from [System.Linq namespace](https://docs.microsoft.com/en-us/dotnet/api/system.linq).

1. Implement "InsertionSort" method in the [Sorter.cs](InsertionSort/Sorter.cs) file. The method should be implemented using a loop statement and use a insertion sort algorithm to sort array items.
2. Implement "RecursiveInsertionSort" method in the [Sorter.cs](InsertionSort/Sorter.cs) file. The method should be implemented using a recursive insertion sort algorithm. You can add new [static methods](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/static-classes-and-static-class-members) or use [local functions](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/local-functions).


## Fix Compiler Issues

Additional style and code checks are enabled for the projects in this solution to help you maintaining consistency of the project source code and avoiding silly mistakes. [Review the Error List](https://docs.microsoft.com/en-us/visualstudio/ide/find-and-fix-code-errors#review-the-error-list) in Visual Studio to see all compiler warnings and errors.

If a compiler error or warning message is not clear, [review errors details](https://docs.microsoft.com/en-us/visualstudio/ide/find-and-fix-code-errors#review-errors-in-detail) or google the error or warning code to get more information about the issue.


## Save Your Work

* [Rebuild your solution](https://docs.microsoft.com/en-us/visualstudio/ide/building-and-cleaning-projects-and-solutions-in-visual-studio) in Visual Studio.
* Check out the [Error List window](https://docs.microsoft.com/en-us/visualstudio/ide/reference/error-list-window) for compiler errors and warnings. If you have any of those issues, **fix issues** and rebuild the solution again.
* [Run all unit tests with Test Explorer](https://docs.microsoft.com/en-us/visualstudio/test/run-unit-tests-with-test-explorer) and make sure there are **no failed unit tests**. Fix your code to [make all your unit tests GREEN](https://stackoverflow.com/questions/276813/what-is-red-green-testing).
* Review all your changes **before** saving your work.
    * Open "Changes" view in [Team Explorer](https://docs.microsoft.com/en-us/visualstudio/ide/reference/team-explorer-reference).
    * Click with your right mouse button on a modified file.
    * Click on "Compare with Unmodified" menu item to open a comparison window.
* [Stage your changes](https://docs.microsoft.com/en-us/azure/devops/repos/git/commits#stage-your-changes) and [create a commit](https://docs.microsoft.com/en-us/azure/devops/repos/git/commits#create-a-commit).
* Share your changes by [pushing them to remote repository](https://docs.microsoft.com/en-us/azure/devops/repos/git/pushing).


## See also

* C# Reference
  * [for statement](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/for)
  * [while statement](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/while)
  * [static](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/static)
* C# Programming Guide
  * [Static Classes and Static Class Members](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/static-classes-and-static-class-members)
  * [Extension Methods](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/extension-methods)
  * [Local functions](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/local-functions)
* .NET API
  * [Array.Length Property](https://docs.microsoft.com/en-us/dotnet/api/system.array.length)
  * [Array.IList.Item[Int32] Property](https://docs.microsoft.com/en-us/dotnet/api/system.array.system-collections-ilist-item)
