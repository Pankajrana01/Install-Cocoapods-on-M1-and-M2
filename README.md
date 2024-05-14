# Install CocoaPods on M1 & M2 MacBooks 

Install Cocoapods on M1 and M2 Macbook easily without Errors

Installing CocoaPods on Apple Silicon chip M1 and M2-based Macbooks has become a headache for many as it throws several errors during the installation process.

Additionally, Cocoapods have compatibility issues with silicon chip Macbooks M1 and M2, so Cocoapods can't be directly installed.

Here is a step-by-step guide to install Cocoapods on M1 and M2 chip-based Macbooks without errors.

Step 1: Go to the [HomeBrew](https://brew.sh/?trk=article-ssr-frontend-pulse_little-text-block) website and copy the command to install HomeBrew using Terminal as we need HomeBrew to install Cocoapods on Macbook M1 and M2. 

![1699539564459](https://github.com/Pankajrana01/Install-Cocoapods-on-M1-and-M2/assets/30138583/1d3cf872-e404-458c-9dbd-a5eae07e4ce3)

Step 2: Paste the copied bash command in a macOS Terminal and hit enter.  
Copy and Paste :  **/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
**

During installation, it will ask for the Password of your device and will ask you to press Enter to continue.


As soon as HomeBrew is installed, the terminal might show a warning like this, asking you to follow the “Next Steps”, which are displayed in the terminal itself as “Next steps”.

<img width="690" alt="Screenshot 2024-05-14 at 9 39 33 PM" src="https://github.com/Pankajrana01/Install-Cocoapods-on-M1-and-M2/assets/30138583/684c8fb8-c32a-4f43-9f6e-db4e465b334b">




In the Next Steps instruction, there are two bash commands

<img width="928" alt="Screenshot 2024-05-14 at 9 40 35 PM" src="https://github.com/Pankajrana01/Install-Cocoapods-on-M1-and-M2/assets/30138583/a3c74cb4-073f-4632-b1b2-d5e35c849361">



Step 3: Copy and Paste the first command fully into your terminal and run it. your terminal which includes the local path in your device to the .zprofile. 

**echo 'eval $(/opt/homebrew/bin/brew shellenv)' >> $HOME/.zprofile 
**

Step 4: Copy and Paste the Second command in the terminal and run it

**eval "$(/opt/homebrew/bin/brew shellenv)"
**

This will successfully install HomeBrew on your Macbook.

Note: To check if homebrew is properly installed, run the command: ** brew help **

<img width="761" alt="Screenshot 2024-05-14 at 9 43 19 PM" src="https://github.com/Pankajrana01/Install-Cocoapods-on-M1-and-M2/assets/30138583/ab3a1cde-b987-4d8f-872a-31a6b3f68dde">


Step 5: After that type : ** brew install cocoapods** 

This will install Cocoapods in your M1 Macbook or M2 Macbook based on Apple Silicon chips.

<img width="744" alt="Screenshot 2024-05-14 at 9 43 51 PM" src="https://github.com/Pankajrana01/Install-Cocoapods-on-M1-and-M2/assets/30138583/4fdf8a96-b8f7-4a84-a71c-2ba31fb1958d">


Yeah!! This will successfully install Cocoapods on your Macbook. 


Step 6: After this check installed pod version. 

**pod --version **


Thank You !!


[LinkedIn - Pankaj Rana](https://www.linkedin.com/in/pankaj-rana-7b3b9212a)

[Medium - Pankaj Rana](https://medium.com/@pankajrana.rana01/install-cocoapods-on-m1-m2-macbooks-16282849cb23)

