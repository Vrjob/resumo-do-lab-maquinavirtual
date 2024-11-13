# Resumo

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do laboratório na **DIO**.

### **Service Level Agreement (SLA)**
Um **SLA** é um contrato formal que define os níveis de serviço que um provedor de nuvem se compromete a oferecer, incluindo tempo de atividade e desempenho.

### **Nível de Serviço**
Refere-se aos padrões de qualidade acordados entre o provedor de serviços e o cliente, geralmente definidos em termos de tempo de atividade, resposta e capacidade de recursos.

### **Tempo de Inatividade**
O **tempo de inatividade** é o período durante o qual um serviço ou sistema está fora de operação, impactando a disponibilidade para os usuários.

### **Porcentagem SLA**
A **porcentagem SLA** indica o tempo de operação disponível de um serviço, com base no SLA acordado. Por exemplo, **99,9% de disponibilidade** significa que o sistema pode estar inativo por até 0,1% do tempo.

### **ID da Plataforma para Gerenciamento de Usuários**
Identificador único usado para gerenciar e controlar o acesso dos usuários em plataformas baseadas em nuvem, como a **Azure**.

### **Microsoft Ressarce Caso Não Funcione**
A **Microsoft** oferece compensações ou créditos caso o nível de serviço acordado não seja atendido, de acordo com os termos do SLA.

### **Máquina Virtual a Partir da Minha Requisição, Microsoft Não Precisa Ressarcir**
Se a criação da **máquina virtual** for feita conforme a solicitação do cliente, a **Microsoft** não é obrigada a ressarcir o cliente caso ocorra algum problema, a menos que o SLA seja violado.

### **Quando Recebo uma Requisição, a Primeira Coisa é o Tempo de Inatividade Aceitável**
Ao receber uma solicitação, a prioridade é **determinar o tempo máximo de inatividade aceitável** para o serviço.

### **É Preciso Trabalhar com a Probabilidade de Inatividade e Saber, Como Arquiteto de Sistemas, Definir o SLA Aceitável para o Projeto**
Como **arquiteto de sistemas**, é essencial analisar a **probabilidade de inatividade** e definir um **SLA** que atenda às necessidades do projeto.

### **Para Teste Não Tem Problema, Pode Trabalhar no Mais Barato, Mas, no Mercado, Melhor Elevar o SLA**
Para **ambientes de teste**, pode-se utilizar **opções mais baratas**, mas para **ambientes de produção**, é recomendável optar por um **SLA** mais elevado.

### **"Quanto Mais 9s, Mais Tempo Disponível, Quanto Menos, Pior"**
Quanto mais "9s" (porcentagem de disponibilidade) em um **SLA**, mais confiável será o serviço, enquanto menos "9s" indicam maior risco de **indisponibilidade**.

### **Quando Criamos uma Máquina Virtual, Opções de Disponibilidade Significam**
As opções de **disponibilidade** ao criar uma **máquina virtual** indicam como a infraestrutura será projetada para garantir **alta disponibilidade** e resistência a falhas.

### **Zona de Disponibilidade**
Refere-se a uma **área física isolada** dentro de uma **região da nuvem**, projetada para proteger contra falhas em larga escala e melhorar a **disponibilidade** do serviço.

### **Quanto Mais Replica, Menos Tempo de Indisponibilidade, Mais Potência, Pois Mais Lugares Estão Trabalhando Naquilo, Bom Contra Desastres e Influencia em Alta Disponibilidade, Apesar do Alto Custo**
Quanto mais **réplicas** forem feitas de uma **máquina virtual**, menor será o **tempo de indisponibilidade**, maior será a **potência** do sistema e mais resistente ele será a **desastres**, embora o **custo** também aumente.

### **Nada Grátis na Nuvem**
Embora muitas ofertas na **nuvem** pareçam gratuitas, sempre há **custos** associados a serviços, especialmente em relação ao uso de **recursos**, **armazenamento** e **alta disponibilidade**.

---
