# Panorama das operações de financiamento do BNDS

### **Quem é o BNDES**

De acordo com a página [**"Quem somos"**](https://www.bndes.gov.br/wps/portal/site/home/quem-somos) do site do BNDES:

Fundado em 1952, o Banco Nacional de Desenvolvimento Econômico e Social (BNDES) é uma empresa pública federal vinculada ao Ministério do Desenvolvimento, Indústria, Comércio e Serviços, sendo o principal instrumento do Governo Federal, nosso único acionista, para financiamento de longo prazo e investimento nos diversos segmentos da economia brasileira.

É formado por três empresas: o BNDES e suas subsidiárias – a BNDES Participações S.A. (BNDESPAR), que atua no mercado de capitais, e a Agência Especial de Financiamento Industrial (FINAME), dedicada ao fomento da produção e da comercialização de máquinas e equipamentos. Atua em todo o território nacional.

### **O Dataset**

No portal de dados abertos do BNDES, encontra-se disponível uma área com disponibilidade para download de dois arquivos de microdados de operações financeiras: operações indiretas automáticas e operações não automáticas. Neste segundo arquivo contém tanto as operações diretas (contratadas diretamente com o BNDES) quanto as indiretas (contratadas através de agentes financeiros). As não automáticas são as que necessitam de análise de um Analista do BNDES, e geralmente são as operações de valores maiores.

Nesses conjuntos de dados cada instância é uma operação financeira de financiamento e contém atributos da:

- **empresa:** nome da empresa, CNPJ, municípios e UF onde estão localizados a
empresa, natureza da empresa se é pública ou privada, se for pública se é da esfera federal, estadual ou municipal, porte da empresa (se pequena, média ou grande), Qual setor de atividade econômica da empresa (CNAE com setor e subsetor);
- **forma de negociação:** se direta ou indireta, se indireta qual foi o agente financeiro, qual foi o tipo de garantia da operação;
- **sobre a contratação:** qual tipo de produto BNDES foi contratado, qual instrumento financeiro utilizado, se era para um projeto de inovação, qual área operacional do BNDES tratou desta operação financeira;
- **sobre o financiamento:** Valor contratado, taxa de juros, custo financeiro, prazo de carência, prazo para amortização, modalidade de apoio; situação do financiamento na data da última atualização do dataset (se liquidado ou ativo).

Link para download dos dois arquivos csv contendo os microdados:
- https://dadosabertos.bndes.gov.br/dataset/operacoes-financiamento/resource/9534f677-9525-4bf8-a3aa-fd5d3e152a93
- https://dadosabertos.bndes.gov.br/dataset/operacoes-financiamento/resource/332d446e-d340-46ef-af64-ee6f36e7bd50

### **Porque fazer essa Análise Exploratória de Dados?**

Tem-se o interesse em obter um panorama das operações de financiamento.

1. As contratações de operações de financimentos do BNDES ocorrem principalmente em quais produtos, com quais condições pagamentos e com qual volume de recursos financeiros?

2. Qual perfil dos clientes que realizam operações de financiamentos junto ao BNDES? São Empresas de qual porte, de qual setor da economia? São da esfera pública ou privadas?

3. A origem, porte, localização e setor das empresas contratantes influenciam de qual forma nos tipos de produtos, volume das contratações e condições de pagamentos dos financimentos realizados junto ao BNDES?

4. Existem condições especiais para os financimentos para inovação? Qual perfil de empresa contratam financiamento para inovação?





