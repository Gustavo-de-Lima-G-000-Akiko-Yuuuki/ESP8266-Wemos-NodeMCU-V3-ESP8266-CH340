![NodeMCU V3 ESP8266 CH340](https://github.com/Gustavo-de-Lima-G-000-Akiko-Yuuuki/ESP8266-Wemos-NodeMCU-V3-ESP8266-CH340/blob/main/NodeMCU-V3-340G-Lua-WIFI-Module-Integration-Of-ESP8266-Extra-Memory-32M-Flash-1175347-descriptionImage0-1000x1000.webp?raw=true)
![NodeMCU V3 ESP8266 CH340](https://github.com/Gustavo-de-Lima-G-000-Akiko-Yuuuki/ESP8266-Wemos-NodeMCU-V3-ESP8266-CH340/blob/main/Schematic_NodeMCU_ESP8266_32MB.webp?raw=true)
![NodeMCU V3 ESP8266 CH340](https://github.com/Gustavo-de-Lima-G-000-Akiko-Yuuuki/ESP8266-Wemos-NodeMCU-V3-ESP8266-CH340/blob/main/PINOUT_WIFI-NodeM-ESP8266-CH340G.webp?raw=true)

# ESP8266 – Wemos NodeMCU V3 (CH340 / CH341)

Este repositório documenta uma **solução prática** para problemas recorrentes com placas **NodeMCU V3 ESP8266** de fabricação chinesa que utilizam os conversores USB-TTL **CH340 ou CH341**.

Esses modelos são amplamente vendidos como “Wemos NodeMCU V3”, porém **os drivers mais recentes distribuídos oficialmente costumam apresentar falhas**, impedindo o reconhecimento correto da placa no Windows.  
A solução apresentada aqui foi obtida diretamente de **fontes chinesas confiáveis** e funciona de forma estável.

---

## 📌 Visão geral do hardware

O **Wemos NodeMCU V3 ESP8266 CH340G** é baseado no popular **ESP8266 SoC da Espressif**, com um diferencial importante:

- 🔹 **Memória Flash ampliada para 32 MB**, ideal para projetos maiores
- 🔹 Conversor USB-TTL **CH340G integrado**
- 🔹 Conector **Micro-USB**
- 🔹 Compatível com **Arduino IDE** e **Lua (NodeMCU)**

---

## ⚙️ Especificações técnicas

- **Chip principal:** ESP8266 (Espressif)
- **Memória Flash:** 32 MB (extra)
- **Conversor USB:** CH340G / CH341
- **Alimentação:**  
  - 4,9 a 9 V DC via pino **VIN**
- **GPIOs:**  
  - 9 pinos digitais (D0 – D8)  
  - PWM, I²C, SPI, 1-Wire  
  - 1 entrada analógica (**A0**)
- **Wi-Fi:**  
  - Modo Station  
  - Access Point  
  - Web Server
- **Dimensões:**  
  - 49 × 26 × 5 mm (sem headers)
- **Espaçamento dos pinos:**  
  - 2,54 mm (0,1”)  
  - 15 pinos × 2 linhas  
  - Compatível com protoboard (sem solda)

---

## 🧠 Recursos e capacidades

- API **orientada a eventos** para aplicações de rede
- Pode atuar como:
  - Cliente Wi-Fi
  - Ponto de acesso
  - Servidor web
- Programação via:
  - **Arduino IDE**
  - **Lua (NodeMCU Firmware)**
- Ideal para projetos de:
  - IoT
  - Automação
  - Monitoramento remoto
  - Prototipagem rápida

---

## 🚨 Problema comum (e solução)

Muitas placas vendidas como *NodeMCU V3* utilizam **CH340/CH341** com variações de firmware e **drivers incompatíveis com versões recentes do Windows**.

📌 **Sintoma comum**
- A placa não aparece na porta COM
- Erros de driver ou reconhecimento intermitente

📌 **Solução**
- Utilizar o **driver específico** indicado neste repositório  
- Evitar drivers genéricos mais recentes que causam conflito

---

## 🛠️ Aplicações recomendadas

- Projetos IoT de médio e grande porte
- Aplicações com bibliotecas extensas
- Protótipos conectados à internet
- Ambientes educacionais e makers

---

## 📂 Categorias

- Placas de desenvolvimento IoT  
- Conselhos de desenvolvimento  
- Makers / Projetos experimentais  

---

## 📎 Observação final

Apesar de ser comercializado como *Wemos*, este modelo **não é fabricado pela Wemos oficial**, e sim por terceiros. Ainda assim, com o driver correto, o funcionamento é **estável e confiável**.

Se este material te ajudou, sinta-se à vontade para contribuir ou compartilhar a solução.
