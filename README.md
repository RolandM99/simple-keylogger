# simple-keylogger

## 1.	Brief definition:

A keylogger is software that is used to record every single keystroke made by the user on a system using his or her keyboard device. It helps to know which keys were pressed and are actively used today to actively monitor the user activity.

## 2.	Built with:

Major language: C++
Libraries: Windows.h, cstdio, fstream, iostream, time.h, map

## 3.	Getting Started

This keylogger project records your keystrokes and then saves them in a PDF file in your local computer. For this project you can set the window to visible or invisible.

- **Invisible makes the window of the logger disappear, and it also starts up hidden from view. Note that it is still visible in the task manager.**

- **Visible is visible, and the window does not close when typing. Great for testing it out.**

Once downloaded the source code in the zipped file in this folder, make sure that you disabled all your antivirus installed in your PC, then simply compile it into an .exe, and then run. I used Visual Studio as the IDE (Integrated Development Environment) for this project. Visual Studio is the good IDE for this because it provides us the Microsoft Visual C++ that contains almost all C++ packages to load and install C and C++ run-time libraries.

This basic keylogger saves the keystrokes to a PDF file when closed. All keystrokes are recorded except the mouse clicks which are ignored by this keylogger.
This keylogger use a hook mechanism to capture all keystrokes typed. A hook is functionality provided by software for users of that software to have their own code called under certain circumstances. That code can augment or replace the current code.

