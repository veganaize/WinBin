### Redistributable
* [**Visual C++ 2019 (v16.7) Redistributable**](https://github.com/veganaize/WinBin/releases/download/perl5/VC_redist.x86_2019.v16.7.exe) - _(**XP-compatible**) Install this only if you get an error when trying to run a utility._

### Portable Binary Packages

- [**GNU Make 4.4.1**](https://github.com/veganaize/WinBin/releases/download/make4/gnumake-4.4.1-windows-x86.zip)*

- [**Lua 5.4.6**](https://github.com/veganaize/WinBin/releases/download/lua5/lua-5.4.6-win32.zip)
  * <details><summary>Details</summary>
  
        REM --- tdm-gcc 10.3.0 (32-bit) ---
        mingw32-make PLAT=mingw
    
        mkdir lua\doc lua\bin lua\include
        copy doc\*.* lua\doc\
        copy src\*.exe lua\bin\
        copy src\*.dll lua\bin\
        copy src\luaconf.h lua\include
        copy src\lua.h lua\include
        copy src\lualib.h lua\include
        copy src\lua.hpp lua\include
    </details>

- [**OpenSSL 1.1.1t**](https://github.com/veganaize/WinBin/releases/download/openssl1/openssl-1.1.1t-windows-x86.zip)*

- [**Perl 5.36.0**](https://github.com/veganaize/WinBin/releases/download/perl5/perl-5.36.0-windows-x86.zip)*

- [**SeaMonkey 2.49.5**](https://archive.seamonkey-project.org/releases/2.49.5/win32/en-US/seamonkey-2.49.5.zip)* ([2.40; no SSE2](https://archive.seamonkey-project.org/releases/2.40/win32/en-US/seamonkey-2.40.zip))

_*Requires SSE2 capable processor._


---

### Resources

* [A-Z Index of Windows Commands](https://ss64.com/nt/) - ss64.com
* [Windows Batch Scripting](https://en.wikibooks.org/wiki/Windows_Batch_Scripting) - wikibooks.org
* [VBScript Programming](https://en.wikibooks.org/wiki/VBScript_Programming) - wikibooks.org
