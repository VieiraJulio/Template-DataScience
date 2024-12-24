# Análise Estatística para Checagem do Engajamento no Instagram

Este projeto tem como objetivo principal analisar o engajamento do perfil do Instagram da empresa, buscando identificar padrões e estratégias eficazes para melhorar a interação com o público. Utilizando técnicas de análise de dados e visualização, o trabalho foca em compreender métricas importantes como curtidas, comentários, compartilhamentos e o alcance das publicações.

![imagem](imagem/Instagram.jpg)

## Organização do projeto

```
├── .gitignore         <- Arquivos e diretórios a serem ignorados pelo Git
├── ambiente.yml       <- O arquivo de requisitos para reproduzir o ambiente de análise
├── LICENSE            <- Licença de código aberto (MIT)
├── README.md          <- README principal para desenvolvedores que usam este projeto.
|
├── dados              <- Arquivos de dados para o projeto.
|
├── notebooks          <- Cadernos Jupyter.
|   └──src             <- Código-fonte para uso neste projeto.
|      │
|      ├── __init__.py  <- Torna um módulo Python
|      ├── config.py    <- Configurações básicas do projeto

│   └── imagens        <- Gráficos e figuras gerados para serem usados em relatórios
```

## Base de Dados 

Colunas 

 - Tipo: Indica o formato da postagem, como foto, vídeo, reels ou stories, permitindo categorizar o conteúdo publicado.

 - Data: Refere-se à data em que a postagem foi feita, possibilitando análises temporais e identificação de tendências ao longo do tempo.

 - Curtidas: Mostra a quantidade de curtidas recebidas pela postagem, representando um dos principais indicadores de engajamento.

 - Comentários: Aponta o número de comentários deixados pelos seguidores, refletindo a interação mais ativa e qualitativa com o conteúdo.

 - Visualizações: Indica quantas vezes a postagem foi vista, uma métrica importante para avaliar o alcance do conteúdo.

 - Tags: Representa as hashtags usadas na postagem, que podem influenciar no alcance e no engajamento ao atrair públicos interessados em tópicos específicos.

 - Pessoas: Refere-se se o conteúdo da Postagem é de uma pessoa ou Não (Por exemplo uma empresa).

 - Campanhas: Identifica se a postagem faz parte de uma campanha específica, ajudando a medir a performance de ações de marketing.

 - Carrossel: Indica se a postagem é um carrossel (múltiplas imagens ou vídeos), um formato que frequentemente gera mais interações por permitir maior exploração do conteúdo.

 - Interações: Representa o total de ações tomadas pelos seguidores na postagem, como curtidas, comentários, salvamentos e compartilhamentos, sendo um indicador geral de engajamento.

   ## Resumo dos Resultados

   - Podemos observar que no top 5 todas as postagens tinham pessoas e eram fotos de campanha.
     
   - Nas 5 piores postagens, não haviam pessoas e nem eram postagens de campanhas. Isso pode ser um indicador que pessoas e campanhas tem relação com as curtidas.
  
   - Parecer que vídeo e IGTV são estratégias ruins que não devem ser usadas.
  
   - Postagens com pessoas engajam muito mais para essa marca, sendo 3 vezes maior de quando não tem pessoas.
  
   - Quando é uma postagem de campanha, o engajamento também é melhor!
  
   - A média sem usar carrossel é melhor do que quando usamos, então não é algo que possa impactar tanto no resultado das mídias dessa empresa olhando inicialmente.
  
   - A média quando tem pessoas E é publicação de campanhas é de cerca de 19,4 mil curtidas, já quando é apenas pessoas (sem campanha passa para quase 10 mil e se não tiver pessoas chega no máximo a 5,9 mil mesmo em campanhas. Nesse caso a gente já consegue mostrar para a empresa a importância de incluir pessoas usando os seus produtos, o que gera um aumento considerável no engajamento.
