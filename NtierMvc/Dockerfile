FROM microsoft/aspnet:latest

COPY . /inetpub/wwwroot/

#RUN sc config w3svc start=demand

RUN powershell -Command Set-Service -Name w3svc -StartupType 'Manual'

ENTRYPOINT ["servicemonitor.exe", "w3svc.exe"]
