FROM ubuntu:latest
MAINTAINER Alan Scott
RUN apt-get update && apt-get -y install libunwind8 libicu55 wget
RUN wget -q https://github.com/PowerShell/PowerShell/releases/download/v6.0.0-alpha.9/powershell_6.0.0-alpha.9-1ubuntu1.16.04.1_amd64.deb
RUN dpkg -i powershell_6.0.0-alpha.9-1ubuntu1.16.04.1_amd64.deb && rm powershell_6.0.0-alpha.9-1ubuntu1.16.04.1_amd64.deb
CMD powershell