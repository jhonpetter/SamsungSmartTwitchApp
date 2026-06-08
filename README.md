# Samsung Smart TV Twitch App (Tizen OS Installer)

Language / Idioma:  
👉 **[Português (Brasil)](#-português-brasil)** | 👉 **[English](#-english)**

---

## 🇧🇷 Português (Brasil)

### 📌 Sobre a Ferramenta (Pronta para Uso)
Se o aplicativo oficial da Twitch sumiu do Smart Hub da sua Smart TV Samsung antiga, este projeto fornece a **ferramenta pronta** e o instalador configurado para trazer a Twitch de volta à sua TV. Você não precisa programar nada; basta baixar o programa e seguir o passo a passo de instalação via computador ou celular Android.

Compatível com sistemas **Samsung Tizen OS (Modelos 2016, 2017 e 2018)**.

---

### 📥 Downloads dos Instaladores
Selecione a versão pronta para o seu dispositivo:

* 🖥️ **Para instalar usando o Computador (Windows PC):** [Baixar Ferramenta PC v4.5](https://github.com/jhonpetter/SamsungSmartTwitchApp/releases/tag/4.5)
* 📱 **Para instalar usando o Celular (Android):** [Baixar Instalador APK Android](https://github.com/jhonpetter/SamsungSmartTwitchApp/releases/tag/android)

---

### 📺 Como Instalar a Twitch na TV Samsung (Passo a Passo)
Assista ao vídeo tutorial completo na prática mostrando o procedimento do início ao fim:  
▶️ [Assistir Vídeo Tutorial no YouTube](https://www.youtube.com/watch?v=2axycQsLPVo)

---

### ⚙️ Novas Funções Inclusas
* **Auto Login / Token:** Salva sua conta automaticamente para carregar seus canais seguidos de forma rápida.
* **Smart Hub Preview:** Integração visual direto no menu inicial da sua TV Samsung.
* **Smart View / SmartThings:** Suporte otimizado para controle e espelhamento através do ecossistema Samsung.

---

### 🛠️ Solução de Problemas (Se der erro na instalação)
Caso o instalador não encontre a sua TV automaticamente na rede local, faça a conexão manual usando a ferramenta de comando inclusa:

1. Abra a pasta do programa no seu computador.
2. Segure a tecla `SHIFT` no teclado e clique com o **botão direito do mouse** em qualquer espaço em branco dentro da pasta.
3. Escolha **"Abrir janela do PowerShell aqui"** ou **"Abrir prompt de comando aqui"**.
4. No terminal, digite o comando abaixo substituindo `IP_DA_TV` pelo IP real da sua televisão (Exemplo: `192.168.1.16:26101`):
```bash
   sdb.exe connect IP_DA_TV:26101

```

5. Para testar a comunicação, digite:

```bash
   sdb.exe capability

```

6. Se o erro persistir, abra uma notificação de erro colando o resultado obtido para receber ajuda: [Criar Relatório de Erro / Nova Issue](https://www.google.com/search?q=https://github.com/jhonpetter/SamsungSmartTwitchApp/issues/new%3Fassignees%3D%26labels%3D%26template%3Dapp-error-not-compatible-with-you-tv-.md%26title%3D)

*Aviso: Testado exclusivamente nos modelos Tizen de 2016 a 2018. Não garantimos compatibilidade com modelos mais recentes devido a bloqueios de firmware da própria fabricante.*

---

## 🇺🇸 English

### 📌 About this Tool (Ready-to-Use App)

If the official Twitch application has disappeared from the Smart Hub of your older Samsung Smart TV, this project provides a **ready-to-use tool** and installer to bring Twitch back to your television. No coding or development skills are required; simply download the program and follow the installation steps using your PC or Android smartphone.

Compatible with **Samsung Tizen OS (2016, 2017, and 2018 models)**.

---

### 📥 Installer Downloads

Select the ready-to-use package for your device:

* 🖥️ **To install using a Computer (Windows PC):** [Download PC Tool v4.5](https://www.google.com/url?sa=E&source=gmail&q=https://github.com/jhonpetter/SamsungSmartTwitchApp/releases/tag/4.5)
* 📱 **To install using a Mobile Phone (Android):** [Download Android APK Installer](https://www.google.com/url?sa=E&source=gmail&q=https://github.com/jhonpetter/SamsungSmartTwitchApp/releases/tag/android)

---

### 📺 How to Install Twitch on Samsung TV (Video Guide)

Watch the complete step-by-step video tutorial demonstrating the full installation process:

▶️ [Watch the Tutorial Video on YouTube](https://www.google.com/url?sa=E&source=gmail&q=https://www.youtube.com/watch?v=2axycQsLPVo)

---

### ⚙️ Included Features

* **Auto Login / Token:** Automatically saves your credentials to load your followed streamers instantly.
* **Smart Hub Preview:** Visual integration directly into your Samsung TV's home dashboard menu.
* **Smart View / SmartThings:** Enhanced support for remote control and casting via Samsung devices.

---

### 🛠️ Troubleshooting (Connection Errors)

If the automated installer fails to locate your television within your local network, establish a manual connection using the bundled command-line tool:

1. Open the application folder on your computer.
2. Hold the `SHIFT` key on your keyboard and **right-click** an empty space inside the folder.
3. Select **"Open PowerShell window here"** or **"Open Command Prompt here"**.
4. In the terminal window, type the following command, replacing `TV_IP` with your television's local network IP address (e.g., `192.168.1.16:26101`):

```bash
   sdb.exe connect TV_IP:26101

```

5. To verify the interface connection status, type:

```bash
   sdb.exe capability

```

6. If the application is still not compatible or encounters a fault, submit the result log here for assistance: [Open a Support Ticket / New Issue](https://www.google.com/search?q=https://github.com/jhonpetter/SamsungSmartTwitchApp/issues/new%3Fassignees%3D%26labels%3D%26template%3Dapp-error-not-compatible-with-you-tv-.md%26title%3D)

*Disclaimer: Exclusively tested on 2016-2018 Tizen models. Compatibility with newer TV sets is not guaranteed due to proprietary firmware restrictions implemented by the manufacturer.*

---

* **Português:** Twitch na TV Samsung antiga, como instalar Twitch na TV Samsung, baixar aplicativo Twitch Tizen download, app Twitch Smart Hub Samsung sumiu, ferramenta instalar Twitch TV pelo PC, sdb connect tizen smart tv twitch apk.
* **English:** How to get Twitch on Samsung TV, download Twitch app for Tizen OS, install Twitch via SDB command Samsung TV, custom Twitch client for older Samsung Smart TV, alternative Twitch app for Samsung Smart Hub.

#Twitch #SamsungSmartTV #TizenOS #SmartHub #TwitchApp #SDB #SmartTVApps #TizenDevelopment #TwitchTV
