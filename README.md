# Finange Bot

## Como Contribuir

Primeiro, você vai precisar criar um Bot no seu telegram. Você ver como faz isso <a href="https://help.huggy.io/telegram-bot/como-configurar-o-telegram-bot">aqui</a>!

"Ah, mas por que eu preciso criar um Bot meu, sendo que quero contribuir pro Finange?"! Muito simples! Cada Bot do Telegram funciona por meio de um Token, então, para que você pudesse contribuir diretamente pro Finange, você precisaria ter o Token OFICIAL do Finange, e, por motivos de segurança, isso NÃO é uma opção.

Logo, a forma mais segura de existir esse projeto no formato Open Source é você criar um Bot de simulação, em que você vai rodar o nosso código no seu próprio Bot, testar, ver tudo bonitinho dentro do seu próprio Bot, e, então, você sobe as features/correções para o Finange, entendeu?! Qualquer dúvida, só abrir um <a href="https://github.com/Finange/finange-bot/issues/new/choose"> issue </a> aqui no nosso repositorio que vamos tirar suas dúvidas!

Agora que você já criou seu Bot, vai precisar criar um arquivo na raiz desse projeto chamado `.env`. Pra que? Simples! Lá vai ser o local que você vai guardar informações importantes do projeto, como o TOKEN do Bot - que você recebeu ao criá-lo no Telegram. Para guardar lá, você cria uma variavel chamada `API_TOKEN=<TOKEN>`, substituindo o `<TOKEN>` pelo Token que você recebeu do BotFather. 

Dessa forma, você já consegue testar todo nosso código dentro da sua máquina, com seu Bot de simulação. 

Próxima etapa, você vai instalar o `poetry` na sua máquina usando esse <a href="https://python-poetry.org/docs/">link</a>!

Depois de instalado, você vai rodar o comando `poetry shell` para que seu poetry crie uma máquina virtual para instalar as dependencias do projeto.

Agora, ele vai precisar instalar tais dependências, basta você rodar o comando `poetry install`.

PRONTO! Agora você já pode contribuir com nosso Finange Bot adicionando features ou corrigindo bugs!

Obrigado pela sua contribuição!