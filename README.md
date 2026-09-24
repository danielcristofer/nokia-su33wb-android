# Nokia SU-33Wb Android Driver & Player (Reverse Engineering Project)

Este é um projeto experimental e educativo focado na engenharia reversa do protocolo de comunicação via Bluetooth entre o receptor de TV Digital Nokia SU-33Wb e o sistema operacional Android.

## 🎯 Objetivos do Projeto
- **Marco 1:** Captura e documentação do log de tráfego Bluetooth (HCI Snoop) a partir do aplicativo oficial rodando em um Nokia 701 (Symbian Belle / Delight 1.1).
- **Marco 2:** Mapeamento do protocolo de comandos (inicialização, busca de canais e troca de frequência).
- **Marco 3:** Criação de um aplicativo Android básico para estabelecer conexão SPP (RFCOMM) e enviar os comandos de controle.
- **Marco 4:** Integração do fluxo de vídeo ISDB-T 1-Seg (MPEG-TS) com player de mídia (ExoPlayer / FFmpeg) no Android.

## 📂 Estrutura do Repositório
- `/docs`: Documentação técnica do protocolo, especificações do hardware e comandos identificados.
- `/logs`: Arquivos de captura do Wireshark (.pcap / .log) coletados do dispositivo Symbian.
- `/src`: Código-fonte do aplicativo Android.
- `PROMPTS.md`: Contexto padrão e diretrizes para interação com IAs durante o desenvolvimento.

## 🛠️ Requisitos de Hardware para Testes
- Receptor de TV Nokia SU-33Wb (ISDB-T 1-Seg).
- Smartphone Nokia 701 (Delight 1.1) funcional com o aplicativo original instalado.
- Smartphone ou Emulador Android para testes do novo driver.
- Computador com Wireshark e Android Studio.