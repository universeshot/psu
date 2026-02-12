# Linux = Windows = MacOS
They all have the same overall goal: enabling a user in interacting with physical hardware.

But I will also argue that Linux = Windows = MacOS.

## Freedom vs Utility vs Safety
Freedom can easily prove fatal.

Freedom to modify everything means freedom to brick your device, or worse. 

Freedom also enables creation of negatively useful tools and media. That is, some tools and media will undoubtedly waste your time in pursuit of your goals. That may be conscious or accidental. 

Linux focuses on freedom.

## Utility
Utility is provided when creativity yields something providing value in a format that makes the same functionality easier to access than it was before. 

Utilities may work in isolation, or may work alongside, in, or containing other utilities.

Utilities are recursive: a utility working in isolation may contain utilities working alongside each other. This would be the technical equivalent of a manager and a team that seldom communicate directly while working. 

Utilities are inherently useful but provide no implied safety. Many tools are inherently dangerous during early development largely owing to the heavy expenses in achieving and maintaining security across all attack vectors.

Windows focuses on best enabling utility, while balancing freedom and safety for the user. 

## Safety
Safety is the ability to use something without the risk of any side effects.

Side effects are adjacent changes made during execution. They may or may not be expected. This could be modifying an external value, creating an additional output, or even a spurious network call. These are all examples that imply the side effect originated within the program.

Side effects also include changes made resulting from externally originating requests. For most tools and programs concern is placed on malicious external requests. External requests can sometimes modify the program's internal state.

In rare cases, external requests can even take control of an entire system. This is close to a worst case scenario. Developing programs that threaten an entire system implies a threat to any network that system is attached to. 

MacOS places a core emphasis on safety. Freedom is still present but the bridge from i{whatever} to complete independence is designed to specifically endorse implied safety if you are able to access the independent functionality.

## Linux, Windows, and MacOS
The path from Linux to Windows to MacOS could be seen as a funnel.

All development can start on any of Linux, Windows, or MacOS. Development can use frameworks that are intentionally cross platform by enabling cross compilation (the same input is transpiled to native code, enabling pseudo-native development for all systems at once). 

### Assuming platform native targeted development
Linux developed utilities most easily port to Windows and MacOS - most enabled languages are available in all major operating systems.

Windows developed tools can often easily port to Linux but may prove harder porting to MacOS. Windows has tried to bridge most gaps that would originally prevent Windows-specific runtimes for Linux, but the gates around the MacOS ecosystem are harder to create general solutions for.

MacOS developed programs are often packaged in a way that is specific and unique for MacOS. Locking the program in like this makes it easy to enable the MacOS-specific safety and security features, preventing most out of bounds behaviour. Making the same program available for Linux or Windows often requires repackaging at the very least, and usually requires recreating the entire source. 

### Creation: Linux
Features and services start as the most experimental units on Linux. Unix is a popular base for Linux distributions.

This provides the most freedom but least safety. These programs can be developed inside "laboratories" to control and contain any unexpected behaviour or potential danger. 

Once complete they will launch on official Linux distributions to feed sentiment back from the public into development. It may or may not be used in future development.

If something dangerously creative succeeds on a Linux distribution, it may be adopted by Windows immediately. 

### Staging: Windows
Tools that are promoted to Windows are more stable, have more reach, receive more public feedback. 

This creates a narrower layer for development but a broader layer for feedback and structured improvement. 

Tools on Windows may develop new features here first to check for widespread support before then porting the same functionality back and forth to Linux and MacOS. 

Given tools on Windows garner the most publicity, this is also the most common place for competitors to seek ideas from. This creates a self-growth based ecosystem, where the same feature can be developed for a number of adjacent tools. 

Each tool should address slightly different use cases, but most feedback can be translated to apply generally and benefit all product owners.

Prodding towards the Apple ecosystem is usually reserved for products generating sufficient revenue that would warrant the additional development and maintenance costs. 

### Prodding: MacOS
Applications pushed into the Apple ecosystem require more stringent validation as well as increased licensing costs. 

Releases are slower because of the extra pre-production manual work required by Apple engineers. They can also cause more aggravation owing to failures that don't seem to have any real root cause. 

Sharing applications across devices is arguably easiest on MacOS thanks to the common packaging structure that is strictly enforced. 

Apple encourages interface designers with a brand focus on visual aesthetics. Some visual decisions are not well received but may still spread elsewhere in time.

The strictness in the Apple ecosystem means that changes are typically pushed slowly and carefully. Limiting the review volume helps reduce friction during Apple's inevitable white-box validation.

If a service, application, or other tool is intentionally created within the Apple ecosystem there is no guarantee that it will ever be ported out. This can be a conscious organizational choice, or it might be constraints on time and cash available for development.

## Funnel
Given the above described two-way promotion stages, there is a natural variance in variety vs quality between each system. 

Linux is assumed to have the broadest toolset, though many tools may never be known to the public. 

Windows is assumed to have the best balance between tool availability and reliability.

MacOS is assumed to have a great user experience with minimal self-awareness required for safety and security, though you might not always find the app you are looking for. 