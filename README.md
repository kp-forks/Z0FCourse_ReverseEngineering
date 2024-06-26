## Website Version

I will be mirroring this repository onto my website, <https://www.debugxp.com/posts/RECourse>. This repository will still be updated, however, I belive the website offers a better experience.

The website is a GitHub pages site hosted with CloudFlare. This is the link to the GitHub pages site repository: <https://github.com/0xZ0F/0xZ0F.github.io>

# Reverse Engineering Course

This course aims to take an individual from beginner to intermediate (advanced is really only achieved through experience) in reverse engineering. While this course focuses on Windows 64-bit, the technical knowledge applies to 32-bit Windows and the theory to any OS.

> The choice has been made for 64-bit Windows since it's modern and the most common OS and architecture. In addition, we only have to deal with one calling convention.

For a more interactive experience with the initial portion of the course (chapters 1 through 6), try out the course on [TryHackMe](https://tryhackme.com/):
1. [Windows x64 Assembly](https://tryhackme.com/room/win64assembly)
2. [Windows Reverse Engineering Intro](https://tryhackme.com/room/windowsreversingintro)

## PDF ZIP Password

There are some PDFs created and provided in ZIP files. They may not be up to date, so it's recommended to follow the normal markdown version of the course. The PDFs were provided due to a high number of requests for them.

The password for the ZIP files is "reverse" (without the quotes).

## [Before You Begin](@BeforeYouBegin.md)

* Please take a moment to read [BeforeYouBegin](@BeforeYouBegin.md).
* **Join the Discord server: [https://discord.gg/73tkPGv](https://discord.gg/73tkPGv)**
    * Use the Discord server to ask for help and stay updated with the course!

## What We'll Do/Learn:
This course is going to teach anyone how to reverse engineer x64 Windows. We will start by covering some basics of binaries, then reverse some small samples, reverse a DLL and implement it into our own program, reverse some malware, then look at some realistic situations.

The goal is not to teach you how to smash your head against assembly. Rather, I want to teach how to use tools to enhance your skills and capabilities. For example, we will cover how to log function calls for easier analysis using a debugger or writing our own code for more control.

#### [Table Of Contents](TableOfContents.md)

## Why I Made This Course
Reversing is made so much harder because of the lack of resources to learn it. Most content is outdated, overpriced, hard to follow, or low quality. Reversing is already considered by many to be a difficult field to get into. Something being difficult isn't an issue, but when it gets needlessly difficult there is an issue. After reading multiple books, countless blog posts, extensive documentation, following multiple YouTube "tutorials", and much more, I feel like it's time for someone to make a dedicated course. I don't think it should be that hard to learn one topic. I certainly don't want people to have to go through the mess I went through, so I decided to make this course. I love this field and I wanted to give back to the community. Here's my gift to you and the rest of the community. Hopefully there are a few people out there that this course can help.

<a name="contact"></a>

## Contact/Stay Updated:
Follow me on Twitter [@0xZ0F](https://twitter.com/0xZ0F)!  
Discord Server: [https://discord.gg/73tkPGv](https://discord.gg/73tkPGv)  

Please give me any and all **honest** feedback you have. Don't worry about hurting my feelings, I want to make this course as good as I can. I can't do that alone, that's why your feedback is so important.

The best way to stay up-to-date is to support me on Patreon which will give you access to the Patreon-only feed. The feed includes the latest updates, upcoming updates, and more.

# Table Of Contents:
* #### [License](License.md)
* #### [Contributing](Contributing.md)
* #### [Credit](Credit.md)
* #### [FAQ](FAQ.md)
* #### [Lingo](Lingo.md)
* #### [Readme](README.md)
* #### [@BeforeYouBegin](@BeforeYouBegin.md)
* #### [TableOfContents](TableOfContents.md)

* ### [Documentation](_DOC)
    * [DOC](_DOC/DOC.md)
    * [Plan](_DOC/Plan.md)
    * [TODO](_DOC/TODO.md)

* ### [Files Needed](FilesNeeded)
  * [Files Needed](FilesNeeded/FilesNeeded.md)
  * [Chapter 6 - DLL](FilesNeeded/Chapter%206%20-%20DLL)
  * [Chapter WIP - Malware](FilesNeeded/Chapter%20WIP-%20Windows)

* ### [Chapter 1 - Introduction](Chapter%201%20-%20Introduction)
    * [1.0 Introduction](Chapter%201%20-%20Introduction/1.0%20Introduction.md)
    * [1.1 HowTo](Chapter%201%20-%20Introduction/1.1%20HowTo.md)
    * [1.2 Setup](Chapter%201%20-%20Introduction/1.2%20Setup.md)

* ### [Chapter 2 - BinaryBasics](Chapter%202%20-%20BinaryBasics)
    * [2.0 BinaryBasics](Chapter%202%20-%20BinaryBasics/2.0%20BinaryBasics.md)
    * [2.1 NumberSystems](Chapter%202%20-%20BinaryBasics/2.1%20NumberSystems.md)
    * [2.2 ASCII](Chapter%202%20-%20BinaryBasics/2.2%20ASCII.md)
    * [2.3 BitsAndBytes](Chapter%202%20-%20BinaryBasics/2.3%20BitsAndBytes.md)
    * [2.4 ProgrammingLanguages](Chapter%202%20-%20BinaryBasics/2.4%20ProgrammingLanguages.md)
    * [2.5 Bitwise Operations](Chapter%202%20-%20BinaryBasics/2.5%20BitwiseOperations.md)
    * [2.6 Mindset](Chapter%202%20-%20BinaryBasics/2.6%20Mindset.md)

* ### [Chapter 3 - Assembly](Chapter%203%20-%20Assembly)
    * [3.0 Assembly](Chapter%203%20-%20Assembly/3.0%20Assembly.md)
    * [3.1 Registers](Chapter%203%20-%20Assembly/3.1%20Registers.md)
    * [3.2 MemoryLayout](Chapter%203%20-%20Assembly/3.2%20MemoryLayout.md)
    * [3.3 Instructions](Chapter%203%20-%20Assembly/3.3%20Instructions.md)
    * [3.4 Flags](Chapter%203%20-%20Assembly/3.4%20Flags.md)
    * [3.5 CallingConventions](Chapter%203%20-%20Assembly/3.5%20CallingConventions.md)
    * [3.6 FinalNotes](Chapter%203%20-%20Assembly/3.6%20FinalNotes.md)

* ### [Chapter 4 - Tools](Chapter%204%20-%20Tools)
    * [4.0 Tools](Chapter%204%20-%20Tools/4.0%20Tools.md)
    * [4.1 ToolTypes](Chapter%204%20-%20Tools/4.1%20ToolTypes.md)
    * [4.2 Debugging](Chapter%204%20-%20Tools/4.2%20Debugging.md)
    * [4.3 ToolGuides](Chapter%204%20-%20Tools/4.3%20ToolGuides.md)

* ### [Chapter 5 - Basic Reversing](Chapter%205%20-%20BasicReversing)
    * [5.0 BasicReversing](Chapter%205%20-%20BasicReversing/5.0%20BasicReversing.md)
    * [5.1 BeforeWeBegin](Chapter%205%20-%20BasicReversing/5.1%20BeforeWeBegin.md)
    * [5.2 FunctionCall](Chapter%205%20-%20BasicReversing/5.2%20FunctionCall.md)
    * [5.3 HelloWorld](Chapter%205%20-%20BasicReversing/5.3%20HelloWorld.md)
    * [5.4 Loops](Chapter%205%20-%20BasicReversing/5.4%20Loops.md)

* ### [Chapter 6 - DLL](Chapter%206%20-%20DLL)
    * [6.00 DLL](Chapter%206%20-%20DLL/6.00%20DLL.md)
    * [6.01 BeforeWeBegin](Chapter%206%20-%20DLL/6.01%20BeforeWeBegin.md)
    * [6.02 DLLBasics](Chapter%206%20-%20DLL/6.02%20DLLBasics.md)
    * [6.03 Exports](Chapter%206%20-%20DLL/6.03%20Exports.md)
    * [6.04 SayHello](Chapter%206%20-%20DLL/6.04%20SayHello.md)
    * [6.05 PrintArray](Chapter%206%20-%20DLL/6.05%20PrintArray.md)
    * [6.06 InitializePlayer](Chapter%206%20-%20DLL/6.06%20InitializePlayer.md)
    * [6.07 PrintPlayerStats](Chapter%206%20-%20DLL/6.07%20PrintPlayerStats.md)
    * [6.08 MysteryFunc](Chapter%206%20-%20DLL/6.08%20MysteryFunc.md)
    * [6.09 ImplementingPlayer](Chapter%206%20-%20DLL/6.09%20ImplementingPlayer.md)
    * [6.10 FinalNotes](Chapter%206%20-%20DLL/6.10%20FinalNotes.md)

* ### [Chapter 7 - Windows](Chapter%207%20-%20Windows) - WIP
    * [7.0 Windows](Chapter%207%20-%20Windows/7.0%20Windows.md)
    * [7.1 Virtual Memory](Chapter%207%20-%20Windows/7.1%20VirtualMemory.md)
    * [7.2 Privileges](Chapter%207%20-%20Windows/7.2%20Privileges.md)
    * [7.3 Architecture](Chapter%207%20-%20Windows/7.3%20Architecture.md) - WIP

* ### [Chapter 8 - Generic Table](Chapter%208%20-%20Generic%20Table) - WIP
    * [8.00 Generic Table](Chapter%208%20-%20Generic%20Table/8.00%20GenericTable.md)
    * [8.01 InitializeTable](Chapter%208%20-%20Generic%20Table/8.01%20InitializeTable.md)
    * [8.02 NumberGenericTableElements.md](Chapter%208%20-%20Generic%20Table/8.02%20NumberGenericTableElements.md)
    * [8.03 IsGenericTableEmpty.md](Chapter%208%20-%20Generic%20Table/8.03%20IsGenericTableEmpty.md)
    * [8.04 GetElement](Chapter%208%20-%20Generic%20Table/8.04%20GetElement.md)
