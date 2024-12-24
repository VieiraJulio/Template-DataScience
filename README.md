# Análise Estatística para Checagem do Engajamento no Instagram

Este projeto tem como objetivo principal analisar o engajamento do perfil do Instagram da empresa, buscando identificar padrões e estratégias eficazes para melhorar a interação com o público. Utilizando técnicas de análise de dados e visualização, o trabalho foca em compreender métricas importantes como curtidas, comentários, compartilhamentos e o alcance das publicações.


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
|
├── relatorios         <- Análises geradas em HTML, PDF, LaTeX, etc.
│   └── imagens        <- Gráficos e figuras gerados para serem usados em relatórios
```

## Configuração do ambiente

1. Faça o clone do repositório que será criado a partir deste modelo.

    ```bash
    git clone ENDERECO_DO_REPOSITORIO
    ```

2. Crie um ambiente virtual para o seu projeto utilizando o gerenciador de ambientes de sua preferência.
3. 
      ```bash
      conda env export > ambiente.yml
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
