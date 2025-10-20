# 🔐 Projeto Santander Cibersegurança 2025 - DIO

## 📋 Descrição

Relatório prático sobre simulação de malwares em ambiente controlado utilizando Python, incluindo um Ransomware simulado para criptografia de arquivos e um Keylogger para captura de teclas e envio por e-mail.

## 🎯 Objetivos

Implementar um ransomware simulado que criptografa e descriptografa arquivos, gerando mensagem de resgate
Desenvolver um keylogger que captura teclas, salva logs e envia automaticamente por e-mail
Documentar procedimentos e resultados dos testes
Propor medidas de mitigação contra malwares como ransomware e keyloggers

## 🛠️ Tecnologias Utilizadas

Python - Linguagem principal para scripts
Bibliotecas Python - cryptography (para criptografia Fernet), pynput (para captura de teclas), smtplib (para envio de e-mails)
VS Code - Editor de código e ambiente de desenvolvimento
Gmail - Serviço para teste de envio de e-mails (com app password)
Ambiente Local - Pastas isoladas para arquivos de teste (sem impacto real no sistema)

## 📊 Resultados

✅ Arquivos de teste criptografados e restaurados com sucesso

✅ Teclas capturadas e salvas em logs locais

✅ Logs enviados periodicamente por e-mail, simulando exfiltração

✅ Demonstração da simplicidade e periculosidade de malwares em Python

✅ Chave de criptografia gerada e mensagem de resgate criada

## 🛡️ Medidas de Mitigação

🔒 Utilizar antivírus com detecção comportamental (ex: Windows Defender)

⚠️ Habilitar firewalls e sandboxing para isolar execuções suspeitas

🔐 Realizar backups regulares em mídias offline

📊 Monitorar processos e logs do sistema

🌐 Promover conscientização: Evitar anexos desconhecidos e usar MFA

## ⚡ Comandos Principais

# Instalar bibliotecas necessárias (uma vez)
pip install cryptography pynput

# Executar ransomware para criptografar arquivos
python ransomware.py

# Executar descriptografador para restaurar arquivos
python descriptografar.py

# Executar keylogger básico para captura local
python keylogger.py

# Executar keylogger com envio por e-mail
python keylogger_email.py
