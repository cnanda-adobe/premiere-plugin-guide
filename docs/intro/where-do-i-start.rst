.. _intro/where-do-i-start:

Where Do I Start
################################################################################

Read about the sample projects. Decide which one is closest to the functionality you want to provide. Build the plug-in into the shared plug-ins folder.

Launch Premiere Pro with the debugger attached, and set breakpoints at the plug-in's entry point to see all communication between Premiere Pro and the plug-in.

The documentation is intended as a reference with detailed explanation where appropriate, but studying the interaction between Premiere Pro and plug-ins is the best way to understand it.

Write plug-ins by modifying sample plug-in source code. This will greatly simplify your efforts, and make it easier for us to help you. Feel free to explore and experiment with the API on your own once you're familiar with it, but please, resist the temptation to start from scratch; you'll only force yourself to repeat other developers' mistakes, including our own.

If you run into behavior that seems wrong, see if you can reproduce the behavior using one of the unmodified sample projects. This can save you a lot of time, if you can determine whether the bug behavior was introduced by your modifications, or was already there to begin with.

