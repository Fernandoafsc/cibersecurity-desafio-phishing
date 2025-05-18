# Demonstração de Phishing Educacional - Página de Login da Alura

**AVISO LEGAL**: Este tutorial tem fins exclusivamente educacionais e de conscientização sobre segurança digital. O uso não autorizado desta técnica é crime. Execute apenas em ambientes controlados e com consentimento explícito.

![Banner de segurança digital](image-banner.png)

## 📋 Pré-requisitos
- [Kali Linux](https://www.kali.org/) (sistema operacional para testes de penetração)
- **setoolkit** (pré-instalado no Kali Linux)
- Máquina virtual (recomendado) com configuração de rede em **Modo Bridge**

![Modo Bridge no VirtualBox](image-bridge.png)  
*(Exemplo: Configuração de rede > Modo Bridge no VirtualBox)*

---

## 🔧 Configuração da ferramenta SEToolkit

### 1. Acesso root no modo administrador
```bash
sudo su
```
### 2. inciar da ferramenta setoolkit com o comando:

```bash
setoolkit
```

### 3. Abrindo a ferramenta, selecione a opção "1" Social-Engineering Attacks.
![](image-6.png)

### 4. Continuando, selecione a opção "2" Web Site Attack Vectors.
(image-3.png)

### 5. Continuando, selecione a opção "3" Credential Harvester Attack Method.
![](image-4.png)

### 6. Continuando, selecione a opção "2" Site Cloner.
![](image-5.png)

### 7. Para continuar com a congiguração, a ferramenta identificar o ip que está rodando na máquina. A ferramente, vai usar a máquina como um servidor para receber os dados. É só clicar no botão Enter e irá aparecer o IP da paquina no tela. 
![](image-2.png)

### 8. O program irá solicitar a URL que irá clonar.
![](image-1.png)

### 9. Após adicionar o URL, clica no botão (Enter), a configuração está feita. Enviar para alguém o IP e aguarda que seja realizado o acesso na página e programa receber os dados de acesso. 


### Resultado
![](image.png)
