# Backups S7 - Projetos STEP 7

Repositório de backups de projetos **SIMATIC STEP 7** para testes de automação industrial com CLPs Siemens S7-300.

## 📋 Sobre

Este repositório contém configurações de teste para integração de sistemas de automação industrial, incluindo comunicação com inversores de frequência e módulos de I/O remotos via PROFIBUS-DP.

## 🗂️ Projetos

### MX_CPU_2
**Configuração de teste: S7-300 315-2DP + Sinamics S120 CU310**

- **Objetivo:** Teste de comunicação e acionamento de inversor
- **CLP:** SIEMENS S7-300 CPU 315-2DP
- **Dispositivo:** Inversor Sinamics S120 CU310
- **Protocolo:** PROFIBUS-DP
- **Inclui:**
  - Configuração de rede PROFIBUS
  - Parâmetros de comunicação
  - Setup de hardware
  - Metadados para testes de integração

### S7_Pro4
**Configuração de teste: Entradas Analógicas via ET200**

- **Objetivo:** Aquisição de sinais analógicos
- **CLP:** SIEMENS S7-300 CPU 315-2DP
- **Módulos:**
  - ET200 (153-2BA02-0XB0) - Acoplador remoto
  - 331-1KF01-0AB0 - Módulo de entrada analógica
- **Protocolo:** PROFIBUS-DP
- **Inclui:**
  - Configuração de I/O remoto
  - Setup de rede PROFIBUS
  - Parâmetros de aquisição analógica

## 🔧 Tecnologias

- **Software:** SIMATIC STEP 7 v5.7
- **Hardware:** 
  - Siemens S7-300 (CPU 315-2DP)
  - Sinamics S120 CU310
  - ET200 (153-2BA02-0XB0)
  - Módulo 331-1KF01-0AB0
- **Protocolo:** PROFIBUS-DP

## 🚀 Como Usar

1. Abra o **SIMATIC Manager** (STEP 7 v5.x)
2. Vá em `File` → `Open Project`
3. Navegue até a pasta do projeto desejado
4. Selecione o arquivo `.s7p`
5. Configure a comunicação com o hardware real ou simulador

## ⚠️ Requisitos

- SIMATIC STEP 7 v5.5 ou superior
- Conhecimento em programação de CLPs Siemens
- Hardware compatível ou simulador (PLCSIM)

## 📝 Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👤 Autor

**MX Drives**
- Email: fernando@mxdrive.com.br

---

*Última atualização: 27 de novembro de 2025*
