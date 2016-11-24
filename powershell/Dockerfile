FROM ubuntu:latest
MAINTAINER Alan Scott
RUN apt-get update && apt-get -y install libunwind8 libicu55 wget libcurl3
RUN wget -q https://github.com/PowerShell/PowerShell/releases/download/v6.0.0-alpha.13/powershell_6.0.0-alpha.13-1ubuntu1.16.04.1_amd64.deb
RUN dpkg -i powershell_6.0.0-alpha.13-1ubuntu1.16.04.1_amd64.deb && rm powershell_6.0.0-alpha.13-1ubuntu1.16.04.1_amd64.deb
RUN echo "New-PSDrive -Name C -PSProvider FileSystem -Root /" >  /opt/microsoft/powershell/6.0.0-alpha.13/profile.ps1 
CMD powershell