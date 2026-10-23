# Número Secreto

Jogo de adivinhação desenvolvido para praticar fundamentos de desenvolvimento web. O objetivo é descobrir um número secreto entre 1 e 10; a cada tentativa, a aplicação informa se o número correto é maior ou menor que o palpite.

## Funcionalidades

- geração aleatória do número secreto;
- dicas indicando se o número é maior ou menor que o palpite;
- contagem das tentativas até o acerto;
- leitura das mensagens em voz alta, em português;
- reinício rápido para uma nova partida;
- controle para evitar a repetição de números até que todas as possibilidades sejam utilizadas;
- layout adaptado para diferentes tamanhos de tela.

## Tecnologias utilizadas

- **HTML5** — estrutura e elementos da interface;
- **CSS3** — estilização, layout responsivo e identidade visual;
- **JavaScript** — regras do jogo, manipulação da página e geração dos números;
- **ResponsiveVoice** — síntese de voz das mensagens exibidas;
- **Google Fonts** — fontes Chakra Petch e Inter.

## Como executar

Não é necessário instalar dependências ou realizar uma etapa de compilação.

1. Clone o repositório:

   ```bash
   git clone https://github.com/VitorHugo09-dev/numero-secreto.git
   ```

2. Acesse a pasta da aplicação:

   ```bash
   cd numero-secreto/3386-git-github-projeto_inicial
   ```

3. Abra o arquivo `index.html` no navegador.

Para uma melhor experiência de desenvolvimento, você também pode servir essa pasta com uma extensão como **Live Server**. É necessário acesso à internet para carregar a síntese de voz e as fontes externas.

## Como jogar

1. Digite um número entre 1 e 10.
2. Clique em **Chutar**.
3. Use a dica apresentada para fazer a próxima tentativa.
4. Ao acertar, confira a quantidade de tentativas e clique em **Novo jogo** para recomeçar.

## Estrutura do projeto

```text
numero-secreto/
└── 3386-git-github-projeto_inicial/
    ├── img/        # Imagens da interface
    ├── app.js      # Lógica e interações do jogo
    ├── index.html  # Estrutura da página
    └── style.css   # Estilos e responsividade
```

## Apresentação para estágio

Ao apresentar este projeto, vale destacar:

- a separação entre estrutura, estilo e comportamento;
- o uso de funções e manipulação do DOM com JavaScript;
- a lógica para gerar números aleatórios sem repetição imediata;
- o cuidado com responsividade e retorno por voz ao usuário;
- os aprendizados obtidos e os próximos passos que você implementaria.

Uma apresentação curta possível:

> “Desenvolvi um jogo de adivinhação com HTML, CSS e JavaScript para praticar lógica de programação e manipulação do DOM. A aplicação fornece dicas, registra tentativas, evita repetir números entre partidas e inclui retorno por voz. O projeto também me ajudou a organizar responsabilidades entre os arquivos e pensar na experiência em diferentes telas.”

## Próximos passos

- adicionar validação e mensagens para entradas inválidas;
- incluir níveis de dificuldade com intervalos diferentes;
- registrar o melhor número de tentativas;
- melhorar a acessibilidade por teclado e leitores de tela;
- publicar uma demonstração online.

## Autor

Desenvolvido por [VitorHugo09-dev](https://github.com/VitorHugo09-dev).

