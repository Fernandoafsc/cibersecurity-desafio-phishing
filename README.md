# Demonstração de Phishing Educacional - Página de Login da Alura

**AVISO LEGAL**: Este tutorial tem fins exclusivamente educacionais e de conscientização sobre segurança digital. O uso não autorizado desta técnica é crime. Execute apenas em ambientes controlados e com consentimento explícito.

## 📋 Pré-requisitos
- [Kali Linux](https://www.kali.org/) (sistema operacional para testes de penetração)
- **setoolkit** (pré-instalado no Kali Linux)
- Máquina virtual (recomendado) com configuração de rede em **Modo Bridge**

![Modo Bridge no VirtualBox]
*(Exemplo: Configuração de rede > Modo Bridge no VirtualBox)*

---

## 🛠️ Configuração do Ambiente

### 1. Configuração de Rede (Crucial)
```bash
# Verifique o IP após configurar o modo Bridge:
ifconfig

