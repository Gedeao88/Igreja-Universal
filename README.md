Igreja Universal do Reino de Deus - Site Fogueira Santa
Este projeto é um site responsivo desenvolvido para a Igreja Universal do Reino de Deus para promover o evento "Fogueira Santa". Foi criado como parte de um projeto de extensão universitária para o curso de CST em Análise e Desenvolvimento de Sistemas, utilizando HTML, CSS e JavaScript para proporcionar uma experiência moderna e intuitiva.
Recursos

Cabeçalho: Exibe o logotipo da igreja, o nome e um versículo bíblico de espaço reservado em uma fonte estilo robótica.
Seção do Evento: Inclui uma descrição temporária do evento "Fogueira Santa" com uma imagem em destaque.
Programação: Lista os horários das reuniões para cada dia da semana, estilizados com um fundo gradiente.
Seção de Versículos: Seção interativa onde os usuários podem clicar para revelar versículos bíblicos de espaço reservado (a serem atualizados com conteúdo real).
Álbum de Fotos: Exibe imagens lado a lado em um contêiner horizontal rolável. Clicar em uma imagem abre um modal com setas de navegação para visualizar outras imagens.
Informações Adicionais: Seções de espaço reservado para estacionamento e serviços (a serem atualizadas).
Links Externos: Links clicáveis ​​para recursos relacionados à igreja (Pastor Online, Podcast, Rádios, Telefones, Hinário) com ícones.
Rodapé: Credita o desenvolvedor (Gedeão Batista) com um link para o Instagram e inclui um aviso de direitos autorais de 2025.

Tecnologias Utilizadas

HTML5: Para a estrutura semântica do site.
CSS3: Para estilização, incluindo gradientes, flexbox e design responsivo.
JavaScript: Para recursos interativos, como alternância de versos e navegação modal de imagens.

Estrutura do Projeto
├── index.html
├── style.css
├── imagem/
│ ├── icone.ico
│ ├── logo.png
│ ├── álbum/
│ │ ├── img0.jpg
│ │ ├── img1.jpg
│ │ ├── img2.jpg
│ │ ├── img3.jpg
│ │ ├── img4.jpg
│ │ ├── img5.jpg
│ │ ├── img6.jpg
│ │ ├── img7.jpg
│ │ ├── img8.jpg
│ │ ├── img9.jpg
│ │ ├── img10.jpg
│ │ ├── img11.jpg

index.html: Arquivo HTML principal contendo a estrutura do site e JavaScript para interatividade.
style.css: Arquivo CSS para estilizar o site.
imagem/: Diretório contendo o favicon, o logotipo e as fotos do evento.

Instruções de configuração
Para hospedar este projeto no GitHub e visualizá-lo localmente ou via GitHub Pages, siga estes passos:
Pré-requisitos

Uma conta no GitHub.
Git instalado em sua máquina local (opcional para testes locais).
Um navegador web para visualizar o site.

Etapas

Clone ou Baixe o Repositório:

Clone o repositório para sua máquina local: git clone https://github.com/seu-nome-de-usuário/nome-do-repositório.git

Alternativamente, baixe o arquivo ZIP do GitHub e extraia-o.

Garantia da Estrutura do Arquivo:

Verifique se todos os arquivos estão nos diretórios corretos, conforme mostrado na estrutura do projeto acima.
Certifique-se de que a pasta imagem/ contenha icone.ico, logo.png e a pasta album/ com as imagens img0.jpg a img11.jpg.

Teste Localmente:

Abra index.html em um navegador web para visualizar o site.
Certifique-se de que todas as imagens carreguem corretamente e que os recursos interativos (alternância de verso, modal de imagem) funcionem conforme o esperado.

Hospedar no GitHub Pages:

Crie um novo repositório no GitHub.
Envie os arquivos do projeto para o repositório: cd nome-do-repositório
git add.
git commit -m "Commit inicial"
git push origin main

Habilite o GitHub Pages nas configurações do repositório:
Acesse Configurações > Páginas.
Defina a origem como branch principal e a pasta / (raiz).
Salve e aguarde a implantação do site (a URL será algo como https://seu-nome-de-usuário.github.io/nome-do-repositório).

Acesse o site:

Visite a URL do GitHub Pages para visualizar o site ativo.
Verifique se todos os recursos, incluindo modais de imagem e links externos, funcionam corretamente.

Uso

Atualizando o conteúdo:

Substitua o versículo de espaço reservado no cabeçalho (<p class="verse">) pela citação bíblica real.
Atualize a descrição do evento em <section class="event"> com texto detalhado sobre a Santa da Fogueira.
Substitua os versículos de espaço reservado em <section class="verses"> por conteúdo bíblico real.
Atualize as seções de estacionamento e serviços em <section class="info"> com informações relevantes.
Garanta que todas as imagens em imagem/álbum/ estejam otimizadas para uso na web para melhorar o tempo de carregamento.

Personalizando Estilos:

Modifique style.css para ajustar cores, fontes ou layouts conforme necessário.
O esquema de cores primário usa #203760 com um gradiente branco; atualize o fundo do corpo ou outros elementos para uma estética diferente.

Contribuindo
Este projeto faz parte de um trabalho universitário e não está buscando contribuições ativamente. No entanto, feedback ou sugestões são bem-vindos por meio de problemas no GitHub ou entrando em contato com o desenvolvedor.
Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter detalhes.
Autor
Desenvolvido por Gedeão Batista.

Instagram: gedeaobatista
Criado para: CST em Análise e Desenvolvimento de Sistemas, Projeto de Extensão II

Agradecimentos

Igreja Universal do Reino de Deus pelo contexto e inspiração.
Instrutores e colegas da universidade pela orientação e feedback durante o desenvolvimento do projeto.

Última atualização: maio de 2025
