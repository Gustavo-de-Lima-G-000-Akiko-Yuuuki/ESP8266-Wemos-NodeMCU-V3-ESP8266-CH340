<!-- ========================= -->
<!-- CAPA / VISÃO GERAL       -->
<!-- ========================= -->

<p align="center">
  <img src="https://github.com/Gustavo-de-Lima-G-000-Akiko-Yuuuki/ESP8266-Wemos-NodeMCU-V3-ESP8266-CH340/blob/main/NodeMCU-V3-340G-Lua-WIFI-Module-Integration-Of-ESP8266-Extra-Memory-32M-Flash-1175347-descriptionImage0-1000x1000.webp?raw=true" width="420">
</p>

# ESP8266 – Wemos NodeMCU V3 (CH340 / CH341)

Este repositório documenta **de forma organizada e prática** a utilização do **NodeMCU V3 ESP8266** com conversor **CH340 / CH341**, amplamente comercializado por fabricantes chineses.

O foco principal é **resolver problemas de driver no Windows**, muito comuns nesses modelos, além de centralizar **informações técnicas, pinout e esquemático** para facilitar o desenvolvimento.

---

## ❗ Contexto do problema

Apesar de serem vendidos como **“Wemos NodeMCU V3”**, muitos desses módulos:

- ❌ **Não utilizam componentes originais Wemos**
- ❌ Vêm com **CH340 ou CH341** em variações pouco compatíveis
- ❌ **Drivers oficiais mais recentes falham no Windows**
- ❌ Não reconhecem porta COM ou apresentam erro intermitente

✅ A solução apresentada neste repositório foi obtida a partir de **fontes chinesas confiáveis** e funciona de forma **estável e consistente**.

---

## 📌 Visão geral do hardware

<p align="center">
  <img src="https://github.com/Gustavo-de-Lima-G-000-Akiko-Yuuuki/ESP8266-Wemos-NodeMCU-V3-ESP8266-CH340/blob/main/NodeMCU-V3-340G-Lua-WIFI-Module-Integration-Of-ESP8266-Extra-Memory-32M-Flash-1175347-descriptionImage0-1000x1000.webp?raw=true" width="420">
</p>

O **NodeMCU V3 ESP8266 CH340G** é baseado no popular **ESP8266 SoC da Espressif**, com um diferencial relevante:

- 🔹 **Memória Flash ampliada para 32 MB**
- 🔹 Conversor USB-TTL **CH340G / CH341**
- 🔹 Conector **Micro-USB**
- 🔹 Compatível com **Arduino IDE** e **NodeMCU (Lua)**

Essa memória extra torna a placa ideal para projetos maiores e uso de bibliotecas extensas.

---

## ⚙️ Especificações técnicas

- **SoC:** ESP8266 (Espressif)
- **Memória Flash:** 32 MB
- **USB-TTL:** CH340G / CH341
- **Alimentação:**
  - 4,9 a 9 V DC via pino **VIN**
- **GPIOs:**
  - D0 a D8 (PWM, I²C, SPI, 1-Wire)
  - ADC **A0**
- **Wi-Fi:**
  - Station
  - Access Point
  - Web Server
- **Dimensões:**
  - 49 × 26 × 5 mm (sem headers)
- **Passo dos pinos:**
  - 2,54 mm (0,1”)
  - 15 pinos × 2 linhas
  - Compatível com protoboard

---

## 🧩 Pinout da placa

<p align="center">
  <img src="https://github.com/Gustavo-de-Lima-G-000-Akiko-Yuuuki/ESP8266-Wemos-NodeMCU-V3-ESP8266-CH340/blob/main/PINOUT_WIFI-NodeM-ESP8266-CH340G.webp?raw=true" width="520">
</p>

O pinout segue o padrão NodeMCU V3, facilitando a reutilização de projetos existentes e bibliotecas já consolidadas.

---

## 🧠 Esquemático elétrico

<p align="center">
  <img src="https://github.com/Gustavo-de-Lima-G-000-Akiko-Yuuuki/ESP8266-Wemos-NodeMCU-V3-ESP8266-CH340/blob/main/Schematic_NodeMCU_ESP8266_32MB.webp?raw=true" width="520">
</p>

O esquemático confirma:
- Uso de **Flash de 32 MB**
- Conversor **CH340G**
- Reguladores e conexões padrão do ESP8266

Útil para:
- Diagnóstico de hardware  
- Projetos customizados  
- Estudo elétrico da placa  

---

## 🧠 Recursos e capacidades

- API **orientada a eventos** para aplicações de rede
- Pode atuar como:
  - Cliente Wi-Fi
  - Access Point
  - Servidor Web
- Programável via:
  - **Arduino IDE**
  - **Lua (NodeMCU Firmware)**
- Ideal para:
  - IoT
  - Automação
  - Monitoramento remoto
  - Prototipagem rápida

---

## 🚨 Problema comum (drivers)

### Sintomas mais frequentes
- Porta COM não aparece
- Erro de driver no Gerenciador de Dispositivos
- Reconhecimento intermitente
- Upload falhando na Arduino IDE

### Solução
- Utilizar **drivers específicos para CH340/CH341**, conforme indicado neste repositório
- Evitar drivers genéricos mais recentes que causam conflito

---

## 🛠️ Aplicações recomendadas

- Projetos IoT de médio e grande porte
- Aplicações com uso intenso de bibliotecas
- Protótipos conectados à internet
- Ambientes educacionais e makers
- Testes de firmware e automação residencial

---

## 📂 Classificação

- Placas de desenvolvimento IoT  
- ESP8266 / NodeMCU  
- Makers & Embedded  
- Automação e Wi-Fi  

---

## 📎 Observação final

Apesar de ser comercializado como **Wemos NodeMCU**, este modelo **não é fabricado pela Wemos oficial**.  
Ainda assim, com o **driver correto**, o funcionamento é **estável, confiável e plenamente utilizável em produção e estudos**.

Contribuições, correções e melhorias são bem-vindas.
