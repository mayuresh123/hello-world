## Windows Server 2016 Project Build Support
This tool will be used to upgrade the older solution with the Visual Studio 2015 compatible solution.

### Batch Script (build.bat)
This script will compile the projects with the Target OS version as "Windows 10"

**Script Input Details: -**
```
  1. Solution directory path
  2. Output directory path
  3. Configuration
  4. Windows Kit path
  5. Windows kit version
  6. Verbose [Optional]
```

**Example: -**
```
build.bat C:\Rubrik-FFD\src C:\output [Configuration] "C:\Windows Kits\10" 10.0.15063.0 -V

*[Configuration] : Debug or Release*
```
