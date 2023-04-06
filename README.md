# Tutorial-SB06-MD-Simulations-and-Analysis-for-Peptide-Based-Materials-Design
![image](https://user-images.githubusercontent.com/130017040/230253089-313bf329-6b32-4906-b016-77a360605fd9.png)

This page is to serve as the repository for trajectories, files and BASH scripts for the Tutorial SB-06 at the MRS Spring 2023 Meeting in San Francisco
_________________________________________________________________________________________________________________________________________________________________________
**Requirements**
Please install the following programs/software on your laptops prior to the Tutorial-
1. **VMD 1.9.3** - This can be installed on MacOS, Windows or Linux. (Newer MacOS users may need to install 1.9.4 alpha suitable to the the OS/CPU). https://www.ks.uiuc.edu/Development/Download/download.cgi?PackageName=VMD
![image](https://user-images.githubusercontent.com/130017040/230256427-bb38ff1e-71b0-4b67-872a-f7c4f793652d.png)
2. **GROMACS** version 2020.X or newer. The instructions for these are OS Dependant and detailed below

  **MacOS** Users
  The Package Manager Homebrew is the easiest way to have GROMACS installed on your laptop - https://brew.sh/
  Once brew in installed on your MacOS Terminal and is the package manager, simply use 
  
  brew install gromacs
  
  Brew will download the required dependencies and libraries and after installation, type gmx -version in the terminal and make sure there is an output.
  This should currently default to the 2023 Version of GROMACS - https://formulae.brew.sh/formula/gromacs
  
  **Windows** Users-
  Windows Subsystem for Linux provides an excellent platform to work in. To enable this simply follow the instructions on this page https://learn.microsoft.com/en-us/windows/wsl/install
  ![image](https://user-images.githubusercontent.com/130017040/230258348-7f5078ad-e683-46bb-ba56-cd9f9e271954.png)
A successful installation should install Ubuntu-22.04 and after setting up you should be at a screen like this -
![image](https://user-images.githubusercontent.com/130017040/230258755-5ee96abb-5fa4-4406-9ad9-2ad0b47865b6.png)
To then install a basic compilation of GROMACS, simply use - sudo apt install gromacs
![image](https://user-images.githubusercontent.com/130017040/230259678-4dde0d73-2c60-4283-9b5b-b5bf5d669450.png)
Check the output of gmx -version in the terminal
![image](https://user-images.githubusercontent.com/130017040/230259861-eb45445d-e0f6-448d-91c8-46fbfa0df59b.png)
**Linux** Users - You can also install GROMACS with your distro package manager or compile a version - https://manual.gromacs.org/documentation/2022.5/install-guide/index.html
_________________________________________________________________________________________________________________________________________________________________________
