# windbg-info

The project intends to be a repository for links related to windbg that I found useful, interesting or have used and wish to keep in an easelly accessible list. 

## WinDbg Preview
I have not used the new version but it looks promessing.

- [Windbg data model](https://doar-e.github.io/blog/2017/12/01/debugger-data-model/)
- [JavaScript Debugging Walkthrough](https://blogs.msdn.microsoft.com/windbg/2017/06/30/script-debugging-walkthrough/)
- [WinDbg, Debugger Objects, and JavaScript! Oh, My!](https://www.osr.com/blog/2017/05/18/windbg-debugger-objects-javascript-oh/)

## WinDbg

#### General links
- [http://www.windbg.org/](http://www.windbg.org/)

- [A good collection of reverse engineering links, including several for windbg](https://github.com/rmusser01/Infosec_Reference/blob/master/Draft/Reverse%20Engineering.md)

- [lowleveldesign - debugging-using-windbg](https://github.com/lowleveldesign/debug-recipes/tree/master/debugging-using-windbg)

- [Using .shell command](https://stackoverflow.com/questions/42153409/filter-output-of-windbg)

- [Windbg versions comparison disctuion thread](http://www.osronline.com/showThread.cfm?link=108907)

- [MEX is Your Friend: Analyzing 32-bit Processes in a 64-bit Kernel Dump](https://needleinathreadstack.wordpress.com/2017/05/15/mex-is-your-friend-analyzing-32-bit-processes-in-a-64-bit-kernel-dump/)

- [Old but interesting - Sample Windbg extension to recurse, filter and pipe commands](https://blogs.msdn.microsoft.com/nicd/2008/12/17/sample-windbg-extension-to-recurse-filter-and-pipe-commands/)

#### Analyzing .net using windbg
- [SOS Extension - Unraveling .NET with the Help of WinDBG](https://blog.talosintelligence.com/2017/07/unravelling-net-with-help-of-windbg.html)
- old but interesting
    - [ASP.NET Memory Leak Case Study: Sessions Sessions Sessions…](https://blogs.msdn.microsoft.com/tess/2006/02/02/asp-net-memory-leak-case-study-sessions-sessions-sessions/)
	

#### Analyzing JavaScript using windbg
- [Windbg Tricks - JavaScript Windbg Instrumentation](http://d0cs4vage.blogspot.com/2013/06/windbg-tricks-javascript-windbg.html)

- coreland helpful links
     - [Exploit writing tutorial part 11 : Heap Spraying Demystified](https://www.corelan.be/index.php/2011/12/31/exploit-writing-tutorial-part-11-heap-spraying-demystified/)
     - [DEPS – Precise Heap Spray on Firefox and IE10](https://www.corelan.be/index.php/2013/02/19/deps-precise-heap-spray-on-firefox-and-ie10/)
- [WinDBG and JavaScript Analysis](https://blog.talosintelligence.com/2017/08/windbg-and-javascript-analysis.html)

#### Cheat-sheets
- http://windbg.info/doc/1-common-cmds.html
- https://sites.google.com/site/jozsefbekes/Home/windows-programming/windbg

### Scripting
- [Windbg Python scripting wrapper - pykd](https://githomelab.ru/pykd/pykd)

- [Set of python scripts for WinDBG over pykd](https://githomelab.ru/pykd/windbg-pack)

- [Windbglib, a wrapper around pykd.pyd (for Windbg)](https://github.com/corelan/windbglib)

- [Anti-Antidebugging WinDbg Scripts](https://www.vallejo.cc/2017/07/anti-antidebugging-windbg-scripts.html)

- [modified file\_activity script from "Practical Reverse Engineering"](https://github.com/Prevenity/windbg-scripts/blob/master/file_activity.wds)

### Plugins, extensions and enhancements

[lynnux/windbg\_hilight github link](https://github.com/lynnux/windbg_hilight) - [tuts4you link](https://tuts4you.com/e107_plugins/download/download.php?view.3473)

- A windbg plugin to highlight text in Disassembly and Command windows. Support x86 and x64. 
- I have used it. It slows the view down a bit when stepping through, but it's worth the wait

[bigLasagne](http://kdext.com/)
- Contains several UI enhancements and an extension

- Assembly syntax highlighting
- Command output window multi-color highlighting
- kdfiles extension

[MEX Debugging Extension for WinDbg](https://blogs.msdn.microsoft.com/luisdem/2016/07/19/mex-debugging-extension-for-windbg-2/)

[Windbg grep extension](https://github.com/long123king/grep)

[WinDBG Anti-RootKit Extension](https://github.com/swwwolf/wdbgark)

[Intel’s Debug Extensions for WinDbg](https://firmwaresecurity.com/2015/12/06/intels-debug-extensions-for-windbg/)

[Application Verifier](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/application-verifier)

- [windbg application verifier extension](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/-avrf)
	- [interesting related link - tracking-handle-misuse-using-application-verifier-and-windbg ](https://blogs.msdn.microsoft.com/mattn/2009/09/08/tracking-handle-misuse-using-application-verifier-and-windbg/)
	- [possible prerequisite - enable-application-verifier](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/enable-application-verifier)

- [Exploring Heap-Based Buffer Overflows with the Application Verifier](https://blogs.cisco.com/security/exploring\_heap-based\_buffer\_overflows_with_the_application\_verifier)
