---
description: Release Notes for Microsoft Edge DevTools Protocol Version 0.1
title: Microsoft Edge DevTools Protocol Version 0.1 Release Notes
author: erikadoyle
ms.author: edoyle
ms.date: 3/21/2018
ms.topic: reference
ms.prod: microsoft-edge
---

# DevTools Protocol Version 0.1 Release Notes

Version 0.1 of the Microsoft Edge **DevTools Protocol** provides an early preview for testing EdgeHTML instrumentation and basic remote debugging in the new standalone [Microsoft Edge DevTools Preview](https://www.microsoft.com/en-us/store/p/microsoft-edge-devtools-preview/9mzbfrmz0mnj?activetab=pivot%3aoverviewtab) app. As such, it requires you to be running a recent [Windows Insider Preview](https://insider.windows.com/en-us/getting-started/) build.

The goals behind the DevTools Protocol are three-fold:

 - Provide a public API for our DevTools app to attach to Microsoft Edge
 - Expand access of DevTools functionality to external tooling clients
 - Enable remote debugging across the range of Windows 10 devices running Micrsoft Edge 

This preliminary release provides core debugging functionality, such as setting breakpoints, stepping through code, and exploring stack traces. In the Edge DevTools UI, this translates to functionality available in the [**Debugger**](../../devtools-guide/debugger.md) panel, minus cache inspection (for Web storage, Service worker, Cache API, and IndexedDB). 

Further debugger functionality will be added in upcoming releases, followed by the instrumentation powering other [DevTools](../../devtools-guide.md) panels.