# resumo-lab-localizando-servicos-por-categoria-azure
Este repositório contém um resumo das lições aprendidas durante o desenvolvimento do lab da DIO

## **1. Personalização da Interface**  

### **1.1. Alterando o Idioma**   
1. No canto superior direito, clique no seu perfil.  
3. Selecione **Configurações** > **Preferências de idioma**.  
4. Escolha o idioma desejado e salve as alterações.  

### **1.2. Alterando a Aparência**  
1. Acesse **Configurações** no menu de perfil.  
2. Em **Tema**, escolha uma das opções:  
   - **Claro**  
   - **Escuro**  
   - **Contraste elevado**  
3. Salve para aplicar.  

## **2. Localizando Serviços por Categoria**  

### **2.1. Categoria: Computação**  
Inclui serviços relacionados ao processamento e execução de aplicações:  

#### **IaaS (Infraestrutura como Serviço):**  
- **Máquinas Virtuais (VMs):** Criação de VMs personalizáveis.  
- **Conjuntos de Dimensionamento de VMs:** Escalabilidade automatizada para VMs.  

#### **PaaS (Plataforma como Serviço):**  
- **App Services:** Hospedagem de aplicações web, APIs e back-ends móveis.  
- **Azure Functions:** Execução de código sob demanda.  

#### **Serverless:**  
- **Azure Kubernetes Service (AKS):** Gerenciamento de contêineres Kubernetes.  
- **Azure Logic Apps:** Criação de fluxos de trabalho automatizados.  

---

### **2.2. Categoria: Rede**  
Serviços para configurar redes seguras e escaláveis:  

- **Azure Firewall:** Segurança e filtragem de tráfego de rede.  
- **Azure Bastion:** Acesso seguro a VMs sem a necessidade de IP público.  

---

### **2.3. Categoria: Armazenamento**  
Gerenciamento de dados e backups:  

- **Armazenamento de Blobs:** Para armazenar grandes volumes de dados não estruturados.  
- **Discos Gerenciados:** Para VMs, fornecendo armazenamento de alto desempenho.  
- **Azure Migrate:** Migração de servidores e bases de dados para o Azure.  

---

## **3. Serviços em Versão Prévia**  
Serviços e recursos ainda em desenvolvimento são marcados como **Versão Prévia**. Eles oferecem acesso antecipado a novas funcionalidades, mas podem não ter suporte total nem garantias de SLA.  

---

## **4. Acordo de Nível de Serviço (SLA)**  
O SLA (Service Level Agreement) define garantias de disponibilidade e desempenho dos serviços Azure. Exemplos:  

- **Máquinas Virtuais:** 99,9% de disponibilidade para uma única VM.  
- **App Services:** 99,95% para ambientes de produção.  
