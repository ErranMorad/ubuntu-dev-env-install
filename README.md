Development environment 💻
All the environment set up instructions are given for Mac OS or Ubuntu 18.04.

VS Code
Visual Studio Code is the code editor you will fall in love with!

Download it from the website and install.

After installation open Extensions tab and install following extensions:

GitLens
ESLint
TSLint
Prettier
Flow



android-studio will launch Android Studio. The wizard will be started, exit it (when exiting choose to launch wizard next time).
Inside Android studio welcome window use Configure -> Create desktop entry and check Create the entry for all users to create an application launcher in system menu
Exit Android studio and launch it from system menu

Android SDK

Launch Android studio
If it is the first time of running Android Studio, you will see a setup wizard. Install everything it needs.
Open android folder inside this folder in Android Studio
Launch AVD Manager (icon with smartphone and android in right top corner)
Create a new virtual device for development using x86 image (in recommended tab)
Launch the virtual device
Android troubleshooting
KVM is required to run this AVD. /dev/kvm device: permission denied. Grant current user access to /dev/kvm:
sudo apt install qemu-kvm sudo adduser $(whoami) kvm
