# How to contribute to ImageSharp

#### **Did you find a bug?**

- Please **ensure the bug was not already reported** by searching on GitHub under [Issues](https://github.com/SixLabors/ImageSharp/issues).

- If you're unable to find an open issue addressing the problem, please [open a new one](https://github.com/SixLabors/ImageSharp/issues/new). Be sure to include a **title, the applicable version, a clear description**, as much relevant information as possible, and a **code sample** or an **executable test case** demonstrating the expected behavior that is not occurring. Please do not hijack existing issues.

#### **Did you write a patch that fixes a bug?**

* Open a new GitHub pull request with the patch.

* Ensure the PR description clearly describes the problem and solution. Include the relevant issue number if applicable.

* Before submitting, please ensure that your code matches the existing coding patterns and practise as demonstrated in the repository. These follow strict Stylecop rules :cop:.

#### **Do you intend to add a new feature or change an existing one?**

* Suggest your change in the [ImageSharp Gitter Chat Room](https://gitter.im/ImageSharp/General) and start writing code.

* Do not open an issue on GitHub until you have collected positive feedback about the change. GitHub issues are primarily intended for bug reports and fixes.

#### **Running tests and Debugging**

* Expected test output is pulled in as a submodule from the [ImageSharp.Tests.Images repository](https://github.com/SixLabors/Imagesharp.Tests.Images/tree/master/ReferenceOutput). To succesfully run tests, make sure that you have updated the submodules!
* Debugging (running tests in Debug mode) is only supported on .NET Core 2.1, because of JIT Code Generation bugs like [dotnet/coreclr#16443](https://github.com/dotnet/coreclr/issues/16443) or [dotnet/coreclr#20657](https://github.com/dotnet/coreclr/issues/20657)

#### **Do you have questions about consuming the library or the source code?**

* Ask any question about how to use ImageSharp in the [ImageSharp Gitter Chat Room](https://gitter.im/ImageSharp/General).

And please remember. ImageSharp is the work of a very, very, small number of developers who struggle balancing time to contribute to the project with family time and work commitments. We encourage you to pitch in and help make our vision of simple accessible imageprocessing available to all. Open Source can only exist with your help.

Thanks for reading!

James Jackson-South :heart:
