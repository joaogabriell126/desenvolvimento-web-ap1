# Divulgação de Night of the Nun (2018) - Avaliação AP1

## Inspiração e design 

Este é um site desenvolvido para a primeira avaliação formal (AP1) da disciplina de Desenvolvimento Web. O projeto constitui a prática de responsividade tanto para desktop quanto para smartphones, atendendo aos requisitos solicitados.

O site foi criado com o intuito de divulgar um dos jogos da empresa Puppet Combo. Night of the Nun faz parte de uma franquia de jogos que me prendem devido ao seu estilo PS1. 

Graças ao meu gosto pelo design antigo da internet, optei por manter um design similar aos antigos forums de internet, aqueles mesmo que você entrava para procurar dicas de jogos como, por exemplo, Mu online. O que deixa mais evidente é o uso da segunda coluna como forma de uma seção de comentários, uma prática que costumava ver em muitos sites assim.  

### Uso das fontes escolhidas
Mesmo não tendo muitos conhecimentos de design a escolha da fonte dos títulos foi proposital devido a atmosfera do jogo e a sensação que ele passa. Acredito que, a fonte VT323 tenha sido uma otima escolha e, que mesmo com o seu padrão pixelado, não será um problema de leitura ou de legibilidade, principalmente devido ao público alvo do site (jovens), além de ter passado por testes como WEVE e Lighthouse (ambas extensões do google).

Ao mesmo tempo, decidi não me aprofundar muito nesse sistema de tipografia, por isso, me mantive no classico Roboto como fonte para o corpo, permintindo uma clara legibilidade do conteúdo principal, sendo uma ótima fonte para ser utilizado em aparelhos telefonicos.

## Organização de projeto

Devido ao tamanho do projeto, escolhi fazer uso separado de páginas CSS, nomeadas com a respectiva página html, fiz isso para manter a facilitade de leitura e procura dos seletores em meio das palavras, fazendo com que, consequentimente, a manutenção do código seja fácil e prática futuramente.

**Organização dos CSS**

- css
    - pages
        - contato.css
        - home.css
        - servicos.css
        - sobre.css
    - global.css

O arquivo **"global.css"** foi utilizado para reforçar a facilidade de manutenção e de uma organização do código. Nele, você escontrará o uso de componentes globais, como: body, header, footer, buttons e títulos (h1). Como eles possuem a mesma configuração, não faria sentido repeti-las em cada uma das páginas, assim, sendo fácil fazer alterações futuras sem a necessidade de muita procura.

Tentei manter o projeto organizado através dos comentários, não apenas como forma de explicar certos usos, mas também como separador de bloco, tentando melhorar a legibilidade das páginas.

## Links Importantes
- Link do site hospedado: [https://desenvolvimento-web-ap1.vercel.app](https://desenvolvimento-web-ap1.vercel.app).

- Link para o github: [https://github.com/joaogabriell126/desenvolvimento-web-ap1](https://github.com/joaogabriell126/desenvolvimento-web-ap1).