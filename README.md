# Visão geral

Insights:
O indexador na Pesquisa de IA do Azure facilita a extração de dados textuais da nuvem, preenchendo índices de pesquisa por meio de mapeamentos de campo para campo entre os dados de origem e o índice.

Possibilidades de Ferramentas:
Ferramentas de pesquisa, análise de dados e sistemas de recomendação podem se beneficiar ao acessar rapidamente dados indexados e oferecer respostas mais eficientes.

Aprendizados Adquiridos:
Durante o processo, destaca-se a importância da precisão nos mapeamentos de campo e da otimização do desempenho para garantir resultados de pesquisa eficazes e rápidos.


As possibilidades de extrair nomes de locais, identificar frases-chave, detectar sentimentos, gerar tags e criar legendas automaticamente proporcionam benefícios significativos. Ao extrair localizações, facilita-se a análise geográfica em dados textuais, enquanto a identificação de frases-chave simplifica a compreensão e categorização de grandes volumes de texto. A detecção automatizada de sentimentos permite uma avaliação rápida do tom emocional em textos, sendo útil em análises de feedback e monitoramento de redes sociais. Além disso, a geração automática de tags em imagens melhora a organização de bibliotecas visuais, e a criação de legendas contribui para a acessibilidade de conteúdo visual. Essas funcionalidades não apenas otimizam processos, mas também enriquecem a compreensão de dados, tanto textuais quanto visuais, em diversas aplicações.


# Como configurar na plataforma Azure através do Azure Search AI


## Create an Azure AI services resource

É necessário criar um serviço para as ferramentas se comunicarem

## Create a storage account

No portal da Azure, é necessário criar um storage para poder armazenar os arquivos que serão analisados

## Upload Documents to Azure Storage

No acesso da interface do storage, é necessário fazer o upload dos arquivos que serão analisados

Após configurar, é necessário importar o container através do serviço Azure AI Search, ele será responsável por extarir informações dos documentos. Nesta etapa é configurado os tipos de dados que podem ser extraidos, são oferecidos ferramentas multimodais de Machine Learning.
