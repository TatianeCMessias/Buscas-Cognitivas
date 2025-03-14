# Buscas-Cognitivas

## Descrição

Este guia apresenta o passo a passo para configurar uma pesquisa no Azure Cognitive Search, além de explorar seus benefícios, 
ferramentas que podem se integrar a essa funcionalidade e os aprendizados adquiridos.

## Tecnologias Utilizadas:
- Azure Cognitive Search
- Portal do Azure

## Como Configurar a Pesquisa no Azure

1 - Crie um Serviço de Pesquisa no Azure
- Acesse o Portal do Azure (portal.azure.com);
- No menu lateral, clique em Criar um recurso;
- Pesquise por Azure Cognitive Search e selecione a opção;
- Escolha um Nome, Grupo de Recursos e um Plano de Preço adequado ao seu projeto;
- Clique em Criar e aguarde a implantação do serviço.

2 - Crie um Serviço no Azure AI Search
- Acesse o Portal do Azure;
- Crie um novo recurso e busque por Azure AI Search;
- Escolha a camada de preço e crie o serviço.

3 - Crie e Configure um Índice de Pesquisa
- No Azure AI Search, acesse Índices e clique em Adicionar;
- Defina os campos do índice (exemplo: título, descrição, categoria);
- Escolha um campo como chave primária (exemplo: ID do documento);
- Habilite recursos de IA, como cognição de linguagem, sinônimos e ranking inteligente.

4 - Ingerir Dados no Índice
- Utilize o Storage Account para armazenar os dados;
- Selecione a assinatura correta;
- Escolha o nome do Storage Account;
- Escolha a opção Locally-Redundant Storage (LRS);
- Clique em Review e Criar para finalizar a configuração.

5 - Ativar a Pesquisa Inteligente
- Habilite cognição AI para extrair insights dos dados;
- Utilize Processamento de Linguagem Natural (PLN) para melhorar a compreensão das perguntas;
- Configure sinônimos e stemming para otimizar os resultados;
- Acesse Data Storage e clique em Container;
- Crie um novo container;
- Faça o upload da documentação e descompacte a pasta;
- Volte para AI Search, importe os dados e selecione os arquivos desejados;
- Acesse o Search Explorer para visualizar os resultados da pesquisa.

6 - Ferramentas que se Beneficiam do Azure Cognitive Search
- Chatbots e Assistentes Virtuais: Melhoram a precisão das respostas baseadas em documentos e bases de conhecimento;
- Plataformas de Suporte ao Cliente: Permitem buscas inteligentes em FAQs e documentação técnica;
- E-commerce: Melhoram a experiência do usuário com buscas mais relevantes de produtos;
- Análise de Dados: Auxiliam na extração de insights de grandes volumes de informações.

7 - Aprendizados Adquiridos
- Durante o processo de configuração do Azure Cognitive Search, alguns dos principais aprendizados incluem:
- A importância de uma boa estruturação dos dados para otimizar os resultados da pesquisa;
- Como a integração com o Processamento de Linguagem Natural melhora a compreensão das consultas;
- A flexibilidade da ferramenta ao permitir integração com diferentes fontes de dados;
- Como a personalização  dos sinônimos melhora a precisão das buscas.







    
