[![build](https://github.com/NewWorldComingSoon/llvm-msvc-build/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/NewWorldComingSoon/llvm-msvc-build/actions/workflows/build.yml)

# llvm-msvc-build
Build llvm-msvc

Current version : V1.3

## What's llvm-msvc?
A project that forked LLVM focused on MSVC Compatibility.

## Features:
- SEH support.
- Compatible with MSVC syntax as much as possible.
- Windows Driver support.(Now only X64)

## How to use llvm-msvc?
- Install Visual Studio 2015~2022(I suggest 2019) with WDK10.
- Install llvm-msvc in this repository (llvm-msvc_X86_64_installer.exe)
- Create your windows driver project and select "LLVM-MSVC_v142_KernelMode" as your platform toolset.
- Compile it.

If you have any questions about how to compile Windows Driver by llvm-msvc.

Please tell me.

We want to use llvm-msvc as comfortable as msvc.

Thank you

Here is an windows driver example: [[link]](https://github.com/gmh5225/LLVMWindowsDriverTest)

![image](https://github.com/NewWorldComingSoon/llvm-msvc-build/blob/main/LLVMDriverTest.png)

## Some discussions on UnknownCheats
https://www.unknowncheats.me/forum/general-programming-and-reversing/493547-using-llvm-msvc-compile-windows-driver.html

