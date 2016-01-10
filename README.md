# aspnet-configuration-02-cli

An example of using multiple configuration sources in ASP.NET 5, accompanying the [ASP.NET 5 Configuration – Using the Built-In Providers](https://jeffogata.com/asp-net-5-configuration-using-the-built-in-providers/) blog post.

Tested with the following:
* ASP.NET 5 RC1 Update1
* Windows 10
* Ubuntu 14.04

On Windows, run `setvars.ps1` to set the environment variables before running `dnx web`.

On Ubuntu, run the following commands before running `dnx web` (note the double underscores in place of `:`):

    export setting3='value 3 - ENV'
    export data__connectionStrings__default=bar
