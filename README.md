# ConnectPro

## Summary
ConnectPro is a complete conference room system built in C#, for Crestron 3-series, 4-series, and any NetStandard platforms.  It is built on the *ICD Connect* (codenamed *Krang*) framework.

## Themes
The way ConnectPro itself behaves is specified by the theme, in [*ICD.Profound.ConnectPro*](https://github.com/ICDSystems/ICD.Profound.ConnectPRO/). The Theme contains all the specific logic for this implementation, including the user interface logic and business logic.

## Panel Files
The panel files are avalialbe [here](https://github.com/ICDSystems/ConnectProPanel).

## Documentation
There isn't really any documentation to speak of, yet. Eventually we put up some of our internal documentation on the framework, and sample configurations for several different types of systems.

## 3-Series Compatibility
This framework was started in early 2016, when Crestron hardware was only compatible with sandboxed .NET 3.5 compact framework. It still maintains compatability with 3-series, and is primarily deployed on 3-series hardware to this day. This limits the ability to use may modern features and packages in the framework.

## Warning
It's kind of complicated and abstracted, and super configuration driven, so, it's a lot if you're new to C#. Also, no guarantees we're doing everything the best way or even the right way.


