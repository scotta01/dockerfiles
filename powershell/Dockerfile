FROM ubuntu:latest
MAINTAINER Alan Scott
RUN apt-get update && apt-get -y install libunwind8 libicu55 wget libcurl3
<<<<<<< HEAD
RUN wget -q https://github.com/PowerShell/PowerShell/releases/download/v6.0.0-beta.2/powershell_6.0.0-beta.2-1ubuntu1.16.04.1_amd64.deb
RUN dpkg -i powershell_6.0.0-beta.2-1ubuntu1.16.04.1_amd64.deb && rm powershell_6.0.0-beta.2-1ubuntu1.16.04.1_amd64.deb
RUN echo "New-PSDrive -Name C -PSProvider FileSystem -Root /" >  /opt/microsoft/powershell/6.0.0-beta.2/profile.ps1 
=======
RUN wget -q https://github.com/PowerShell/PowerShell/releases/download/v6.0.0-alpha.18/powershell_6.0.0-alpha.18-1ubuntu1.16.04.1_amd64.deb
RUN dpkg -i powershell_6.0.0-alpha.18-1ubuntu1.16.04.1_amd64.deb && rm powershell_6.0.0-alpha.18-1ubuntu1.16.04.1_amd64.deb
RUN echo "New-PSDrive -Name C -PSProvider FileSystem -Root /" >  /opt/microsoft/powershell/6.0.0-alpha.18/profile.ps1 
>>>>>>> 3970d5eca3d5e2bc4d9fd16f0ff020863893d1f2
CMD powershell