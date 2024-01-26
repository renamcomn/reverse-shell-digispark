<p align="center">
<img src="https://private-user-images.githubusercontent.com/74038190/271839856-3b4607a1-1cc6-41f1-926f-892ae880e7a5.gif?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDYzMDc1NzYsIm5iZiI6MTcwNjMwNzI3NiwicGF0aCI6Ii83NDAzODE5MC8yNzE4Mzk4NTYtM2I0NjA3YTEtMWNjNi00MWYxLTkyNmYtODkyYWU4ODBlN2E1LmdpZj9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMjYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTI2VDIyMTQzNlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWE2NjE5MjY0ODk1MDUzOTdjZjlhMWNiODY1MWRlMDI1MWY5YWMwZTAwYTYyM2MxYTk0MGQzNWMxZGQ3NGEzNDgmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.rAUI7UrvG_OPnVfrGyOC-1rpDreaYko-tfudGgxPKjU" width="400"/>
</p>
# Conexão Reversa Windows-Linux com Netcat e PowerShell

Este script permite estabelecer uma conexão reversa de um computador Windows para um host Linux usando o Netcat. Certifique-se de seguir as instruções cuidadosamente.

## Passo 1: Preparando o Computador Host Linux

No seu computador host Linux, abra um terminal e inicie um ouvinte Netcat na porta 4444 (ou a porta de sua escolha). Execute o seguinte comando:

```bash
nc -lp 4444
```
## Passo 2: Modificando o Script PowerShell

Agora você precisa fazer algumas alterações no script PowerShell chamado Invoke-PowerShellTcpOneLine.ps1. Abra o script e faça a seguinte alteraçao:

Altere "SEU_ENDEREÇO_IP" para o endereço IP do seu computador host Linux.

## Passo 3: Hospedando o Script PowerShell

Para que o computador Windows possa baixar o script PowerShell, você precisa hospedá-lo em um servidor da Web

## Passo 4: Editando o Script DigiSpark

Na linha com DigiKeyboard.print, substitua 'ENDERECO DO SEU ARQUIVO POWERSHELL'  pelo caminho completo do seu script PowerShell hospedado no servidor da Web (usando o endereço IP do host Linux).

Após a execução bem-sucedida do script DigiSpark, seu computador Windows estabelecerá uma conexão de shell reverso com o computador host Linux no Netcat.

Lembre-se de que esse tutorial é fornecido apenas para fins educacionais e éticos. O uso inadequado dessas técnicas pode ser ilegal e antiético. Certifique-se de ter permissão para realizar essas ações nos sistemas e redes que você controla.
