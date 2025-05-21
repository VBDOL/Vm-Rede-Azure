# 🏗️ Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

## 🚀 Introdução
Este repositório documenta o processo de **configuração de recursos e dimensionamento de máquinas virtuais (VMs) no Microsoft Azure**. Aqui você encontrará resumos, anotações e dicas sobre como otimizar o desempenho e custo das VMs.

---

## 🎯 Objetivos de Aprendizagem
Ao concluir este desafio, você será capaz de:
- Criar e configurar **Máquinas Virtuais no Azure**.
- Ajustar **dimensionamento e recursos** conforme necessidade.
- Implementar **boas práticas de segurança e rede**.
- Utilizar o **GitHub** para compartilhar documentação técnica.

---

## 🏗️ Passo a Passo para Configuração de VMs no Azure

### 1️⃣ **Acessando o Portal do Azure**
- Entre no [Portal do Azure](https://portal.azure.com).
- Faça login com sua **Conta Microsoft**.

### 2️⃣ **Criando uma Máquina Virtual**
1. No menu lateral, clique em **Criar um recurso**.
2. Selecione **Máquina Virtual** e clique em **Criar**.
3. Escolha o **sistema operacional** (Windows Server, Linux, etc.).
4. Defina o **tamanho da VM** conforme necessidade.

### 3️⃣ **Configurando Dimensionamento da VM**
- Escolha o **tipo de instância** baseado em CPU, memória e armazenamento.
- Utilize **Conjuntos de Dimensionamento de Máquinas Virtuais** para escalabilidade automática.
- Ajuste **vCores e RAM** conforme carga de trabalho.

### 4️⃣ **Configuração de Rede e Segurança**
- **Rede Virtual (VNet)**: Conecte sua VM a uma rede segura.
- **Grupo de Segurança de Rede (NSG)**: Defina regras de acesso.
- **Balanceamento de Carga**: Distribua tráfego entre múltiplas VMs.

### 5️⃣ **Configuração de Disco e Armazenamento**
- Escolha entre **discos SSD Premium** ou **HDD Standard**.
- Configure **armazenamento adicional** conforme necessidade.
- Defina **backup e redundância** para segurança dos dados.

### 6️⃣ **Revisão e Criação**
- Revise todas as configurações e clique em **Criar**.
- Aguarde a implantação da VM.
- Acesse a VM pelo **Azure Portal** ou via **SSH/RDP**.

### 7️⃣ **Gerenciamento e Dimensionamento**
- Utilize **Azure Monitor** para acompanhar métricas de desempenho.
- Ajuste **autoscaling** para otimizar custos e eficiência.
- Configure **alertas e logs** para monitoramento contínuo.

---

## 🔗 Links Úteis
- [Tutorial: Criando Máquinas Virtuais no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/)
- [Guia de Dimensionamento de VMs](https://learn.microsoft.com/pt-br/azure/virtual-machine-scale-sets/)
- [Segurança e Rede no Azure](https://learn.microsoft.com/pt-br/azure/networking/)

---

## 📂 Organização do Repositório
- `README.md` → Documentação completa sobre **Configuração de VMs no Azure**.
- `/images` → Capturas de tela ilustrando o processo (opcional).
- Outros arquivos relevantes para estudo e implementação.

---

## 📢 Reflexão
Este repositório serve como um guia prático para **configuração de recursos e dimensionamento de máquinas virtuais no Azure**. A documentação clara e detalhada facilita o aprendizado e futuras referências!
