# FSharpCliApp

- How to compile a single file binary (for windows)

```sh
dotnet publish -r win-x64 -c Release /p:PublishSingleFile=true
```

NOTE: If you wish to compile for other platforms, simply replace the `win-x64` in above command.
https://docs.microsoft.com/en-us/dotnet/core/rid-catalog#windows-rids
- `win-x64`
- `linux-x64`
- `osx-x64`

- How to run the CLI (on windows)

```
.\FSharpCliApp\bin\Release\netcoreapp3.1\win-x64\publish\FSharpCliApp.exe --help
```
