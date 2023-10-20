# Análise de Contratos Governamentais

### **Introdução**
No campo da ciência de dados, reconheço a importância de examinar áreas da administração que possuem um impacto substancial na sociedade, como a gestão de contratos governamentais. Meu objetivo principal com este projeto é entender melhor a distribuição de verbas, verificar a conformidade dos contratos e explorar os detalhes que cercam esses acordos. Pretendo, com esta investigação, contribuir para uma maior transparência e eficiência na administração pública.

### **Construção dos Dados**
Utilizei a biblioteca `Faker` para simular um conjunto de dados realista. Aqui está o resumo de como construí os dados:

- **Colunas**: Foram criadas colunas como "Nome da agência governamental", "Nome do fornecedor", "Duração do contrato", "Valor total do contrato", "Valor pago até o momento", entre outras, para modelar informações comuns em contratos governamentais.
- **Valores**: Utilizei funções específicas do `Faker` para gerar nomes, endereços, datas e valores monetários, garantindo variedade e realismo aos dados.

### **O que foi feito**
1. **Análise Exploratória dos Dados**: Realizei uma inspeção minuciosa do conjunto de dados gerados pelo `Faker`, avaliando as características gerais, tipos de dados e possíveis lacunas.

2. **Visualização Gráfica**: Utilizei `matplotlib` e `seaborn` para desenvolver visualizações que elucidam tendências e padrões nos dados.

### **Análises realizadas e Respostas**

- **Quais são os principais fornecedores?**  
Realizei uma contagem para identificar a frequência com que cada fornecedor apareceu nos contratos. Isso proporcionou uma visão clara dos fornecedores mais frequentes e possivelmente mais confiáveis para o governo.

- **Quais regiões receberam mais verbas?**  
Uma análise por região foi feita para entender a distribuição das verbas governamentais.

- **Quanto falta para pagar de cada contrato?**  
Subtraindo o valor já pago do valor total do contrato, consegui calcular o montante pendente.

- **Que colunas deveriam ser acrescentadas para auxiliar na detecção de fraudes?**  
Adicionei colunas como "Data da Última Auditoria", "Nome do Auditor", e "Número de Alterações no Contrato". Esses detalhes podem ajudar a identificar padrões suspeitos ou atividades irregulares.

- **Visualização da duração dos contratos**  
Examinei a duração dos contratos para entender se existem períodos padrão ou se há grande variação nas durações.

- **Regressão linear sobre verbas**  
Implementei um modelo de regressão linear para entender a relação entre o valor total do contrato e o valor pago até o momento.

- **Qual valor total investido por Ministérios?**  
Agrupei os dados por ministério para visualizar o investimento total de cada um.

- **Conformidade de contratos por Ministérios?**  
Por meio de uma análise de conformidade, pude identificar quais ministérios estão mais alinhados com as regulamentações e quais precisam de mais atenção.

### **Conclusão**
Ao final deste projeto, sinto que consegui lançar uma nova luz sobre a gestão de contratos governamentais. A visualização e análise desses dados são essenciais para entender melhor como os recursos são alocados e garantir que os processos sejam feitos com integridade e eficiência. Mesmo que os dados sejam fictícios, o método e as técnicas utilizadas são totalmente aplicáveis a dados reais, , tornando este projeto uma peça valiosa do meu portfólio.
