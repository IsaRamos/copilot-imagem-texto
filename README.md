# Copilot: Teste de análise de Imagem 🌆

Projeto da plataforma DIO. Análise do desempenho do Copilot para receber inputs de imagens e outputs com a descrição das imagens em formato de texto.

## Desenvolvimento ⚙

A ideia foi realizar testes com a IA Generativa [Copilot](https://copilot.microsoft.com/) da Microsoft para analisar o desempenho em visão computacional em descrever imagens.

As 5 imagens selecionadas são propositalmente distintas em temática, componente e estilo.

Deixe na pasta [inputs](https://github.com/IsaRamos/copilot-imagem-texto/tree/main/inputs) as imagens utilizadas neste teste.
Na pasta [outputs](https://github.com/IsaRamos/copilot-imagem-texto/tree/main/outputs) estão três screenshoots do processo. 

Reforço que não realizei alteração do texto gerado pelo Copilot.

## Prompt inicial 💡

```text
Você é especialista em visão computacional e em descrever imagens em formato de texto. 
Quero que você me descreva de forma objetiva e de fácil interpretação cinco imagens. Vou enviar uma imagem de cada vez.
Crie uma tabela seguindo este modelo: | Número | Título para a Imagem | Descrição | e acrescente uma linha para cada imagem enviada.
```

## Resultado 👀

| Nº  | Título para a Imagem | Descrição          |
|:---:| ---------------- | ---------------------- |
| 1   | Cachoeira e Vegetação Exuberante | A imagem mostra uma cachoeira robusta com água caindo vigorosamente entre rochas cobertas de musgo. Há uma névoa fina criada pelo impacto da água, que contribui para um efeito etéreo. Árvores verdes exuberantes cercam a cachoeira, destacando-se contra o céu claro. O primeiro plano é dominado por rochas escuras e ásperas, algumas parcialmente cobertas por vegetação rasteira. A cena transmite uma sensação de natureza selvagem e intocada.|
| 2   | Cidade Futurista à Noite | A imagem retrata uma paisagem urbana futurista à noite, com edifícios que parecem flutuar ou estar suspensos no ar. A arquitetura é irregular e densa, com tamanhos e formas variadas de prédios. Algumas janelas e fontes de luz espalhadas pela cena emitem um brilho suave, sugerindo atividade dentro desse ambiente urbano. No primeiro plano, há um veículo voador com janelas iluminadas, semelhante a um táxi ou drone de transporte, movendo-se entre os prédios. A atmosfera geral da imagem é sombria e evocativa de cenários de ficção científica, possivelmente indicando uma realidade avançada ou alternativa onde as leis tradicionais da física são desafiadas. Não há problemas matemáticos ou de lição de casa presentes nesta imagem para transcrever. |
| 3   | Jogadora de Vôlei em Ação | A imagem mostra uma pessoa em uma pose de ação no vôlei, com o rosto obscurecido para preservar a privacidade. A pessoa está vestindo um conjunto esportivo branco e preto, joelheiras e tênis esportivos azuis. Ela parece estar realizando o movimento de levantar ou passar uma bola de vôlei, que é visível acima de suas mãos. Essa imagem pode ser relevante para discussões sobre esportes, técnicas de vôlei ou treinamento atlético. Não há problemas matemáticos ou de lição de casa presentes na imagem para transcrever. |
| 4  | Pizza Fresquinha e Apetitosa | A imagem mostra uma pizza recém-assada com coberturas que incluem fatias de pepperoni, queijo derretido e o que parecem ser fatias de pimenta jalapeño verde. A pizza está colocada em uma tábua de madeira, e a massa parece dourada, indicando que pode estar crocante. Ao redor da pizza, há pequenas tigelas contendo mais fatias de jalapeño e grãos de pimenta preta. Ao fundo, vemos duas garrafas de vidro com conteúdo que se assemelha a vegetais em conserva ou óleos aromatizados, e uma pequena tigela branca com tomates cereja vermelhos ao lado delas. Essa imagem é interessante, pois exibe um prato popular de maneira apetitosa, sendo relevante para contextos culinários ou conteúdo relacionado a alimentos. Não há problemas matemáticos ou de lição de casa presentes na imagem para transcrever. 🍕 |
| 5   | Banner “LIVE GAME NIGHT” | Um banner gráfico colorido com o texto “LIVE GAME NIGHT” exibido no centro. Abaixo desse texto principal, está escrito “FOLLOW THE BEST PLAYERS”. O fundo é roxo, com vários ícones relacionados a jogos, como um joystick, um controle de videogame, uma televisão e elementos decorativos como estrelas e linhas. Parece ser um anúncio ou convite para um evento de jogos ao vivo, onde os espectadores podem assistir aos melhores jogadores competindo ou mostrando suas habilidades. |

> ⚠ Observação: O Copilot fez uma tabela para cada imagem, ao invés de apenas acrescentar uma linha para cada imagem.

## Análise 🔎

O Copilot teve um bom desempenho. Os títulos transmite corretamente o que são as imagens.

Como também, todas as descrições estão de acordo com as imagens enviadas. Inclusive com informações coerentes sobre sensações e sentimentos que as imagens poderiam provocar nas pessoas.

Por outro lado, apresentou uma informação irrelevante ao final da descrição de três imagens: "Não há problemas matemáticos ou de lição de casa presentes nesta imagem para transcrever."

Uma peculiaridade sobre a imagem 4, da pizza: finalizou a descrição com um emoji 🍕.

## Imagens Royalty Free 🚩

- [Cachoeira](https://www.freepik.com/free-photo/vertical-shot-huilo-huilo-waterfall-southern-chile_13901517.htm) por wirestock
- [Cidade Cyberpunk](https://www.freepik.com/free-photo/multi-dimensional-urban-space-exotic-concepts-digital-painting_14541132.htm#fromView=search&page=1&position=7&uuid=09e5d51a-b3b8-4848-8386-185f88a59c06) por liuzishan
- [Jogadora de Vôlei](https://www.freepik.com/free-photo/young-female-volleyball-player-isolated-white-wall-woman-sport-s-equipment-shoes-sneakers-training-practicing-concept-sport-healthy-lifestyle-motion-movement_12836890.htm#fromView=search&page=1&position=1&uuid=7d6612d5-84b9-41ad-85fd-75b39ddf677a) por master1305
- [Pizza](https://www.freepik.com/free-photo/pepperoni-pizza-with-olives-wooden-board_7218694.htm#fromView=search&page=1&position=1&uuid=9e325e72-e0e8-4684-80ad-7ac6f4af6a6e) por Kamran Aydinov
- [Thumbnail Live Game](https://www.freepik.com/free-vector/game-night-youtube-thumbnail_172780883.htm#fromView=search&page=1&position=9&uuid=3f959fbd-7da3-4d60-a77b-7ac9dfbd022e) por freepik
