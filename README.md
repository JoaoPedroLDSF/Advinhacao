🎯 Jogo do Número Secreto
📋 Sobre o Projeto
Bem-vindo ao Jogo do Número Secreto! Este é um projeto de um simples jogo de adivinhação desenvolvido em JavaScript, que tem como objetivo desafiar a capacidade de previsão do usuário. O jogo consiste em acertar um número aleatório gerado pelo programa, oferecendo dicas de "maior" ou "menor" para guiar o jogador até a resposta correta.

Neste jogo, você pode testar suas habilidades e se divertir tentando acertar o número secreto com o menor número de tentativas possíveis. O desafio está em fazer palpites inteligentes e deduções rápidas!

🚀 Funcionalidades
🔢 Número Aleatório: O número secreto é gerado aleatoriamente a cada nova execução do jogo, garantindo uma experiência única sempre que o jogador iniciar.
🧩 Dicas de Maior/Menor: A cada tentativa incorreta, o programa informa se o número secreto é maior ou menor que o palpite fornecido, ajudando a ajustar as próximas escolhas.
🔄 Controle de Tentativas: O jogo acompanha quantas tentativas foram necessárias para o jogador acertar o número, proporcionando uma métrica para competir consigo mesmo ou com amigos.
🎉 Mensagem de Vitória: Quando o jogador acerta, uma mensagem de congratulação é exibida, junto com o número de tentativas utilizadas.
🛠️ Tecnologias Utilizadas
O projeto é desenvolvido utilizando:

HTML: Estrutura básica do jogo.
JavaScript: Lógica de geração do número aleatório, tratamento das entradas do usuário e controle das tentativas.
CSS (opcional): Para estilização adicional e melhorias na aparência do jogo, caso deseje expandir a interface.
📦 Estrutura do Código
O código principal do jogo está estruturado da seguinte forma:

Definição do Número Secreto: O número secreto é gerado usando Math.random() e fica armazenado em uma variável. Neste projeto, ele varia entre 1 e 5000.
Loop de Palpites: O jogador insere palpites por meio de um prompt, e o jogo continua pedindo novas entradas até que o número secreto seja encontrado.
Dicas: O programa fornece dicas indicando se o número secreto é maior ou menor que o palpite.
Contador de Tentativas: A cada tentativa errada, um contador é incrementado para registrar o total de tentativas.
Mensagem Final: Ao acertar, o jogo exibe uma mensagem de vitória indicando o número secreto e quantas tentativas foram necessárias.
🕹️ Como Jogar?
Passo 1: Clone este repositório para o seu ambiente local
Passo 2: Abra o arquivo HTML no seu navegador.
Passo 3: Uma mensagem de boas-vindas será exibida e o jogo começará.
Passo 4: Digite um número entre 1 e 5000 no prompt e siga as dicas fornecidas pelo jogo até acertar o número secreto.
Passo 5: Ao acertar, uma mensagem de vitória será exibida junto com o número total de tentativas.
✨ Possíveis Melhorias
Se quiser aprimorar o projeto, aqui estão algumas sugestões:

✅ Adicionar uma interface gráfica com botões e campos de entrada para substituir o prompt e os alerts.
✅ Implementar níveis de dificuldade, com variações no intervalo de números.
✅ Adicionar um contador de tempo para medir quanto tempo o jogador levou para encontrar o número.
✅ Criar um sistema de placar para armazenar o menor número de tentativas para cada jogador.
✅ Disponibilizar um botão de "Reiniciar Jogo" para facilitar a repetição da brincadeira.
🔗 Links Úteis https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Math/random
🔗 Links Úteis https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide
Documentação do Math.random() - Saiba mais sobre como funciona a geração de números aleatórios no JavaScript.
Referência de Sintaxe de JavaScript - Guia completo de referência de sintaxe e boas práticas.
🔧 Melhorias Futuras
Opção de Reinício: Implementar a opção de jogar novamente sem a necessidade de recarregar a página.
Modo Difícil: Adicionar um modo onde o número máximo seja maior ou onde o número de tentativas seja limitado.
Interface Gráfica: Melhorar a interface do jogo com botões e elementos visuais mais interativos em vez de apenas prompts e alerts.
