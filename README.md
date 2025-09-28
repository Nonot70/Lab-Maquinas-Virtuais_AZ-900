# ☁️ Máquinas Virtuais no Azure – Bootcamp Microsoft Azure AZ-900  

<div align="center">  
  <img src="https://learn.microsoft.com/en-us/media/learn/certification/badges/microsoft-certified-fundamentals-badge.svg" width="120px" alt="Azure AZ-900 Badge"/>  
  <h3>🚀 Desafio do Bootcamp Microsoft Azure AZ-900 – DIO + Microsoft</h3>  
</div>  

---

## 📖 Sobre o Projeto  

Este repositório reúne meu **desafio prático** do bootcamp **Microsoft Azure AZ-900**, promovido pela **DIO em parceria com a Microsoft**.  

O objetivo é **consolidar o aprendizado sobre máquinas virtuais no Azure**, registrando cada etapa da configuração realizada no laboratório.  

---

## 🛠️ Etapas do Laboratório  

### 1️⃣ Acesso ao Portal Azure  
- 🔑 Login no [Portal Azure](https://portal.azure.com).  
- 🔍 Exploração da interface principal e serviços disponíveis.  

---

### 2️⃣ Criação da Máquina Virtual  

**Passos principais:**  
1. Acessar **Máquinas Virtuais**.  
2. Clicar em **Criar → Máquina Virtual**.  
3. Selecionar o sistema operacional **Windows**.  

---

### 3️⃣ Configurações da VM  

- 🌍 **Região:** West US 2  
- 🏢 **Zona de disponibilidade:** 1  
- 🖥️ **Imagem:** Windows Server 2022  
- ⚡ **Tamanho:** B1s (plano gratuito)  
- 🔐 **Credenciais:** usuário e senha fortes  
- 📡 **Portas de entrada:** RDP (3389)  

---

### 4️⃣ Discos  

- 💽 **SO:** 127 GiB (Standard SSD)  
- 🗑️ Exclusão junto com a VM habilitada  
- 🔒 Criptografia gerenciada pelo Azure  
- ➕ Discos extras: não adicionados  

---

### 5️⃣ Rede  

- 🌐 Rede virtual/sub-rede padrão  
- 🌍 IP público estático  
- 🔒 NSG básico (liberando apenas RDP)  
- ❌ Sem balanceamento de carga  

---

### 6️⃣ Gerenciamento & Monitoramento  

- 🛡️ **Microsoft Defender:** plano básico  
- 🔄 **Atualizações automáticas:** habilitadas  
- 📊 Monitoramento básico  
- ❌ Backup e identidade gerenciada não configurados  

---

### 7️⃣ Tags  

- ❌ Não aplicadas neste lab  
- ✅ Em produção são essenciais para governança e custos  

---

### 8️⃣ Conexão à VM  

1. 🔗 Cliquei em **Conectar**.  
2. ⬇️ Baixei o arquivo `.rdp`.  
3. 🖥️ Acesse via RDP com as credenciais criadas.  

---

## 📋 Resumo das Configurações da Máquina Virtual  

| Categoria        | Configuração Escolhida | Observação |
|------------------|------------------------|------------|
| 🌍 **Região**    | West US 2              | Plano gratuito compatível |
| 🏢 **Zona**      | Zona 1                 | Simplificação para o lab |
| 🖥️ **Imagem**   | Windows Server 2022    | Microsoft Learn |
| ⚡ **Tamanho**   | B1s                    | Econômico e gratuito |
| 🔐 **Segurança** | Padrão                 | Suficiente para estudo |
| 💸 **Spot**      | Não habilitado         | Garantia de disponibilidade |
| 👤 **Credenciais**| Usuário + senha forte | Para acesso RDP |
| 📡 **Portas**    | RDP (3389)             | Aberto a todos os IPs no lab |
| 💽 **Disco SO**  | 127 GiB - SSD Standard | Econômico |
| ➕ **Discos extras** | Não adicionados    | Apenas temporário |
| 🌐 **IP público**| Estático               | Necessário para RDP |
| 🔒 **NSG**       | Básico                 | Apenas RDP liberado |
| 🛡️ **Defender** | Plano básico           | Segurança mínima |
| 🔄 **Updates**   | Automáticas habilitadas| |
| ❌ **Backup**    | Não configurado        | Não necessário no lab |
| 📊 **Monitoramento**| Básico              | Sem alertas |
| 📦 **Extensões** | Não adicionadas        | Foco no essencial |
| 🏷️ **Tags**     | Não aplicadas          | Importantes em produção |

---

## ✅ Conclusão  

Este laboratório permitiu compreender:  
✔️ O **processo completo de criação de uma VM no Azure**.  
✔️ A importância de cada configuração (rede, discos, segurança, gerenciamento).  
✔️ Boas práticas para **custos, segurança e organização**.  

Com isso, consolidei os conceitos fundamentais sobre **Infraestrutura como Serviço (IaaS)** no **Microsoft Azure**.  

---

<div align="center">  
  Feito com ☁️ e muito 💻 durante o Bootcamp  
</div>
