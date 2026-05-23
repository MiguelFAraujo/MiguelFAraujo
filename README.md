<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0A0A0E,50:7C3AED,100:F59E0B&text=Miguel%20Ferreira%20de%20Araujo&fontColor=ffffff&fontSize=34&fontAlignY=32&desc=Backend%20%7C%20Maker%20%7C%20Infra%20Aut%C3%B4noma%20%7C%20Educa%C3%A7%C3%A3o&descAlignY=56&descSize=16" alt="Miguel Ferreira de Araujo" width="100%" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Miguel%20de%20Araujo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miguel-de-araujo)
[![GitHub](https://img.shields.io/badge/GitHub-MiguelFAraujo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MiguelFAraujo)
[![AMAJGI](https://img.shields.io/badge/Case%20em%20produ%C3%A7%C3%A3o-AMAJGI-174A9C?style=for-the-badge&logo=vercel&logoColor=white)](https://amajgi.vercel.app/)
[![Arduino na Veia](https://img.shields.io/badge/Arduino%20na%20Veia-7C3AED?style=for-the-badge&logo=arduino&logoColor=white)](https://github.com/MiguelFAraujo/arduino-na-veia)

**Desenvolvedor Backend, maker de hardware, infraestrutura self-hosted e educador.**
**Código aberto, eletrônica crua e sistemas que funcionam de verdade.**

</div>

> *"Open source me trouxe até aqui. Minha intenção é manter tudo aberto."*

---

## Quem Eu Sou

Não sou só programador. Sou alguém que resolve problemas com código, hardware e infraestrutura — e documenta cada passo.

Comecei com Arduino nos componentes mais crus (AVR puro), passei por ESP, Raspberry Pi, Orange Pi, Banana Pi, Mango Pi, e montei um ecossistema inteiro de servidores self-hosted com Docker, Gitea, Nextcloud, AdGuard, Jellyfin e automações que rodam 24/7 em casa.

Sou professor também. Ensino backend, Python, Django, lógica, eletrônica e automação para pessoas reais — em sala de aula e nos materiais que publico.

---

## Projetos em Destaque

<table>
  <tr>
    <td width="50%">
      <h3>🔧 Arduino na Veia</h3>
      <p><em>A Referência do Maker Brasileiro</em></p>
      <p>Site completo com tutoriais, componentes, projetos, glossário e ferramentas para Arduino e microcontroladores. Em constante expansão — de AVR puro a ESP32, Raspberry Pi Pico, STM32, PIC e muito mais.</p>
      <p>📦 <strong>Stack:</strong> Go (stdlib) · HTML/CSS · SQLite · Docker</p>
      <p>🔗 <a href="https://github.com/MiguelFAraujo/arduino-na-veia">Repositório</a> · <em>Link do site em breve</em> (domínio próprio em investigação)</p>
    </td>
    <td width="50%">
      <h3>🏢 AMAJGI</h3>
      <p><em>Portal Institucional da Associação de Moradores</em></p>
      <p>Plataforma com cadastro comunitário, painel administrativo, RBAC, LGPD, autenticação Google, exportação XLSX e documentação completa de segurança.</p>
      <p>📦 <strong>Stack:</strong> Next.js · React · Supabase · Vercel</p>
      <p>🔗 <a href="https://amajgi.vercel.app/">Acessar site</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🤖 RoboTutor</h3>
      <p>Robô educacional open-source com Arduino, sensor ultrassônico e LEDs. Projeto didático para ensino de eletrônica e programação.</p>
      <p>📦 <strong>Stack:</strong> Arduino · C++ · Eletrônica</p>
      <p>🔗 <a href="https://github.com/MiguelFAraujo/RoboTutor">Repositório</a></p>
    </td>
    <td width="50%">
      <h3>🛡️ Sentinela</h3>
      <p>Sistema EDR caseiro usando Nmap, Python e Ollama (Phi-3). Monitoramento de rede local com detecção baseada em IA.</p>
      <p>📦 <strong>Stack:</strong> Python · Ollama · Nmap · Docker</p>
      <p>🔗 <a href="https://github.com/MiguelFAraujo/Sentinela">Repositório</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🌱 GreenOpsMonitor</h3>
      <p>Monitoramento local de hardware com MCP e IA acessível. Sensor DHT22, consumo, temperatura e alertas inteligentes.</p>
      <p>📦 <strong>Stack:</strong> Python · MCP · IA Local (Ollama)</p>
      <p>🔗 <a href="https://github.com/MiguelFAraujo/GreenOpsMonitor">Repositório</a></p>
    </td>
    <td width="50%">
      <h3>📱 Bot Arduino na Veia</h3>
      <p>Telegram Bot interativo com formulário de contato, upload de arquivos e painel de feedback. Conecta comunidade maker ao admin.</p>
      <p>📦 <strong>Stack:</strong> Go · Telegram Bot API · Systemd</p>
      <p>🔗 Repositório privado (em fase de abertura)</p>
    </td>
  </tr>
</table>

---

## 🔬 Infraestrutura Self-Hosted

Tenho um cluster caseiro com **11 containers Docker** rodando 24/7 em Raspberry Pi 4 + Orange Pi Zero 2W, conectados via NFS e Tailscale.

<details>
<summary><strong>Ver detalhes da infraestrutura</strong></summary>

### Raspberry Pi 4 (8GB)
| Serviço | Função |
|---------|--------|
| Nextcloud | Nuvem pessoal |
| AdGuard Home | DNS + bloqueio de anúncios |
| Jellyfin | Streaming multimídia |
| Gitea | Git self-hosted |
| Duplicati | Backup automatizado |
| Calibre | Biblioteca de eBooks |

### Orange Pi Zero 2W (Cluster Worker)
- **IA Local:** Ollama + TinyLlama + Qwen2.5-Coder 3B
- **OpenCode 24/7:** Agente de desenvolvimento autônomo com Groq + Gemini + DeepSeek
- **NFS Server:** Exporta SATA3 (219GB) para o RPi
- **Armazenamento:** 168GB livres em SATA3

### Infraestrutura de Rede
- **Tailscale:** VPN mesh entre RPi, OrangePi e dispositivos móveis
- **Tunelamento:** Acesso remoto seguro sem portas expostas
- **NFS:** RPi monta SATA3 do OrangePi via NFS (backups, dados compartilhados)
- **Gitea:** Git self-hosted com mirror para GitHub
- **Backup automatizado:** Scripts Python com rotação de 7 dias
- **Monitoramento:** Watchdog a cada 5 minutos + alertas Telegram

</details>

---

## 🧰 Hardware e Maker

Trabalho com eletrônica no nível dos componentes — AVR puro, sensores, servomotores, módulos, displays. Cada projeto é montado, testado e documentado do zero.

<details>
<summary><strong>Placas e microcontroladores que uso</strong></summary>

| Família | Modelos |
|---------|---------|
| **Arduino** | Uno, Nano, Mega, Pro Mini, ATtiny85 |
| **ESP** | ESP32, ESP8266, ESP32-CAM |
| **Raspberry Pi** | Pi 4 (8GB), Pi Pico, Pi Zero 2W |
| **Orange Pi** | Zero 2W (cluster worker) |
| **Banana Pi** | Testes e prototipação |
| **STM32** | Blue Pill, Black Pill |
| **PIC** | Microchip PIC16F, PIC18F |

</details>

Componentes que domino: sensores (ultrassônico HC-SR04, PIR, DHT22, LM35), servomotores SG90/MG995, motores DC + ponte H, módulos Relé, display LCD 16x2, matriz de LEDs, Bluetooth HC-05, WiFi ESP, RF 433MHz e muito mais.

---

## Stack

<div align="center">

### Backend

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### Frontend

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Infraestrutura

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![NFS](https://img.shields.io/badge/NFS-Storage-005C99?style=for-the-badge)
![Tailscale](https://img.shields.io/badge/Tailscale-VPN-24292F?style=for-the-badge&logo=tailscale&logoColor=white)
![Gitea](https://img.shields.io/badge/Gitea-Self%20Hosted-5E2C8A?style=for-the-badge&logo=gitea&logoColor=white)

### Hardware & Maker

![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352B?style=for-the-badge&logo=espressif&logoColor=white)
![AVR](https://img.shields.io/badge/AVR-Puro-7C3AED?style=for-the-badge)

### Ferramentas & IA

![Ollama](https://img.shields.io/badge/Ollama-IA%20Local-412991?style=for-the-badge&logo=ollama&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-Llama%203.3-F59E0B?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-2.0%20Flash-1A73E8?style=for-the-badge&logo=google&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-V4-4F46E5?style=for-the-badge)

</div>

---

## Meu Fluxo de Trabalho

```mermaid
flowchart LR
  A["Problema real"] --> B["Entendimento do contexto"]
  B --> C["Arquitetura simples"]
  C --> D["Implementação"]
  D --> E["Teste e auditoria"]
  E --> F["Documentação"]
  F --> G["Entrega utilizável"]
  G --> H["Open Source"]
```

Código bom precisa ter **contexto, decisão técnica, teste, documentação** — e de preferência, ser aberto para que outros aprendam e contribuam.

---

## Filosofia

Tenho um compromisso real com **código aberto**. Ele me trouxe até onde estou. Meus projetos são todos open-source (a maioria ainda privada enquanto amadurece, mas com intenção de abrir).

Uso **Gitea** como meu Git self-hosted para desenvolvimento interno, com mirror automático para GitHub. Tudo que construo passa por:

- 🔒 **Segurança desde o início** (LGPD, RBAC, criptografia, headers HTTP)
- 📖 **Documentação como parte do código** (não como depois)
- 🧪 **Testes e auditoria** (para entregar coisa que funciona)
- ♻️ **Backup automatizado** (porque dado bom merece proteção)

---

## Estatísticas

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=MiguelFAraujo&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="Estatísticas do GitHub" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MiguelFAraujo&layout=compact&theme=tokyonight" alt="Linguagens mais usadas" />

</div>

---

## Contato

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Vamos%20conversar%20no%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miguel-de-araujo)

**Open source me trouxe até aqui. Tudo que faço é aberto.**

</div>
