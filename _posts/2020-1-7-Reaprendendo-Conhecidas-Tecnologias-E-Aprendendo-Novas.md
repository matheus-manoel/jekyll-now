---
layout: post
title: Reaprendendo Conhecidas Tecnologias e Aprendendo Novas
---

## 7.1.2020

Ano novo, vida nova: é chegada a hora de retomar a busca por um estágio. Já fiz esse mesmo processo em 2017, quando consegui meu primeiro emprego. De lá pra cá muita coisa mudou, inclusive minha preparação para esse momento. Se naquela vez desenvolvi alguns projetos pessoais com a única função de me preparar para processos seletivos, dessa vez não fiz isso. Sem problemas: daquela vez eu não tinha 1 ano de experiência real no mercado de trabalho.

Enviei alguns curriculuns hoje e já obtive algumas respostas, dentre elas um desafio para fazer em casa, antes de qualquer outra etapa. Nada como trabalhar 7 dias de graça para uma empresa... Oba! Brincadeiras a parte, eu realmente discordo desse método de processo seletivo, mas aceitei o desafio porque vai ser um bom treinamento para a onda de processos seletivos que vem pela frente. E no fim eu posso até conseguir um estágio! hehe

Outro ponto que me levou a aceitar o desafio são as tecnologias: React e GraphQL. Eu trampei com React por um ano e foi amor a primeira vista. Quando saí do meu primeiro estágio, infelizmente, fiquei sem utilizar essa ferramenta. É um bom momento para reaprender. Já GraphQL eu não conheço. E não tem momento ruim para aprender algo novo. Vamo que vamo!

Hoje já tá um pouco tarde e eu vou usar pra tirar um descanso, assistir uns vídeos e responder outras empresas que entraram em contato. Amanhã é hora de começar de fato. Escreverei nesse post as atualizações dessa saga na medida em que avanço.

## 8.1.2020

Capuccino feito. Hora de começar.

Um amigo meu me passou suas credenciais pro udemy e recomendou um curso chamado Modern React with Redux. Valeu Ivan!

Dei uma olhada e o curso tem 47.5 horas. Será que vale a pena? Tirando as aulas marcadas com [Legacy], que totalizam 17 horas, o curso passa a ter mais ou menos 30 horas. Na velocidade 2, são 15 horas de conteúdo. Tô de férias e arrumar um estágio é minha responsabilidade mais importante no momento: vale a pena!

Vou começar a assistir.

### Update

Tenho uma versão muito desatualizada do node. Vou atualizá-la.

Feito.

### Update

Na hora de instalar o create-react-app, deu erro de permissão. Para reinstalar como adm, usei "sudo !!". Esse comando copia o último comando no lugar de !!. Fica a dica.


### Update

Liguei o GoYo: plugin pro vim pra escrever sem distrações. Agora vai.

Alguns comandos relembrados:

- npx create-react-app app
- npm start

Lembro que eu usava o yarn como substituto ao npm. Um colega de trabalho me apresentou e era muito mais rápido. Vou dar uma pesquisada melhor depois para retormar seu uso. Por enquanto, vai assim mesmo.


### Update

Terminei a parte 1 do curso. Foi importante para lembrar conceitos simples. Vou agora selecionar partes que considero importantes para lembrar com qualidade, para a partir daí por a mão na massa (talvez depois de dar uma estudada em GraphQL).

Partes escolhidas:

- Communicating with Props
- Class-Based Components (2 primeiras vídeo-aulas)
- State in React Components
- Understanding Lifecycle Methods
- Handling User Input with Forms and Events
- Making API Requests with React
- Let's Test Your React Mastey!

Fiquei interessado também em algumas partes que falam sobre redux e react-redux. Lmebro que quando aprendi adorei. Mas uma coisa de cada vez. Talvez nem seja necessário para cumprir o desafio proposto.

Falando nisso, nem falei qual era o desafio, né? Vou colar aqui embaixo:

"Nosso desafio é simples! Queremos que você construa um sistema onde seja
possível gerenciar questões de múltipla escolha, utilizando React e GraphQL
(requisitos mínimos). Deve ser possível adicionar, editar e deletar perguntas e
respostas, assim como visualizar na forma de listagem todas as perguntas já
cadastradas no sistema. Não colocamos nenhuma restrição ou definição para o
desenvolvimento de layout das telas, ficando a seu critério pensar na solução como um todo."

### Update

Fiz o suficiente de Communicating with Props pra lembrar. Próximo.

### Update

Class-Based Components também concluído. Bora relembrar state.


### Update

Enquanto eu assistia uns vídeos, recebi um email de outra empresa com outro desafio. Vou me dedicar ao outro nos próximos momentos, documentando meu avanço num post como esse. Em algum momento volto pra cá. Até mais!

### Update

Só pra finalizar bem essa primeira parte antes de partir pro desafio da outra empresa, vou terminar de assistir os vídeos na viagem de ônibus que farei amanhã.


## 9.1.2020

Acordei, comi uma batata recheada feita pela minha vó e peguei o busão pra minha cidade. Hoje tenho uma entrevista em uma startup interessante. No ônibus, seguem os estudos.

Relembrar o ciclo de vida de um componente é fundamental. É a partir desse entendimento que é possível saber onde colocar cada funcionalidade de um componente, como sua interação com APIs por exemplo. Não lembro quantas vezes me ferrei quando estava aprendendo por conta disso. Segue os métodos do ciclo:

constructor -> render -> (content is visible on screen) -> componentDidMount -> (sit and waits for updates) -> componentDidUpdate -> (sits and waits til component is no longer shown) -> componentWilUnmount.
