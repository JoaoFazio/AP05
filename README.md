# Nome: João Gabriel e Fernando Seiji

## AP05 – Implementação de Aplicação Web com Node.js e Vue.js.


# HTML

#### • html: Esta tag define o início do documento HTML.

#### •  lang="pt-br": Atributo que define o idioma do documento como português brasileiro.

#### •  head: Esta tag contém informações sobre o documento, como metadados, links para estilos, scripts e o título da página.

#### •  meta charset="UTF-8" : Define o conjunto de caracteres usado no documento como UTF-8, que suporta vários idiomas.

#### •  meta name="viewport" content="width=device-width, initial-scale=1.0" : Define a configuração de visualização para dispositivos móveis, ajustando a largura para o tamanho do dispositivo e definindo a escala inicial como 1.0.

#### •  <title>Lista de tarefas</title>: Define o título da página.

# body

#### •  body: Esta tag contém todo o conteúdo visível da página.

#### •  div id="app" div: Define um contêiner com o ID "app" onde o aplicativo Vue será montado.

#### •  <script type="module" src="/src/main.js"></script>: Inclui o arquivo JavaScript que contém o código do aplicativo Vue. O atributo type="module" indica que o script é um módulo JavaScript.


# CSS (style.css)

# :root

#### •	Define as propriedades padrão para o documento.

#### •	Define a fonte padrão como "Inter", seguido de fontes de sistema e de backup.

#### •	Define a altura da linha como 1.5 vezes o tamanho da fonte.

#### •	Define o peso da fonte como 400 (normal).

#### •	Configura o esquema de cores para se adaptar a preferências do usuário entre claro e escuro.

#### •	Define a cor do texto como um branco levemente transparente.

#### •	Define a cor de fundo como um cinza escuro.

#### •	Aplica propriedades de renderização de fonte para melhor legibilidade e suavização em navegadores.

# a

#### •	Define a cor e o peso da fonte para links.

#### •	Remove a decoração de texto padrão dos links.

#### •	Define a cor do link quando o cursor está sobre ele.


# body (corpo do documento)

#### •	Remove as margens padrão do corpo do documento.

#### •	Usa o flexbox para centralizar o conteúdo verticalmente.

#### •	Define a largura mínima como 320 pixels e a altura mínima como 100% da altura da janela de visualização.

# h1 (títulos de nível 1)

#### •	Define o tamanho da fonte para títulos de nível 1 como 3.2 vezes o tamanho padrão da fonte.

#### •	Define a altura da linha como 1.1 vezes o tamanho da fonte.

# button (botões)

#### •	Define o estilo dos botões, incluindo borda arredondada, tamanho do texto, peso da fonte e espaçamento interno.

#### •	Define a cor de fundo do botão como um cinza escuro.

#### •	Adiciona efeitos de transição para a cor da borda quando o cursor passa sobre o botão.

#### •	Define a aparência do botão quando está em foco.

# .card (cartões)

#### Define o espaçamento interno dos elementos com a classe .card.

# #app (aplicação)

#### •	Define a largura máxima do elemento com o ID app como 1280 pixels.

#### •	Centraliza o elemento horizontalmente.

#### •	Define o espaçamento interno do elemento.

#### •	Define o alinhamento do texto como centralizado.

# @media (prefers-color-scheme: light) (mídia de preferência de esquema de cores claro)

#### •	Aplica estilos específicos quando o usuário prefere um esquema de cores claro.

#### •	Altera as cores do texto, links e botões quando o cursor passa sobre eles.

# button:focus e button:focus-visible (estado de foco do botão)

#### •	Define a aparência do botão quando está em foco, seja através da navegação por teclado (por exemplo, usando a tecla Tab para navegar pelos elementos da página) ou através de um dispositivo apontador.

#### •	Adiciona uma borda de destaque de 4 pixels quando o botão está em foco.

#### •	-webkit-focus-ring-color é uma variável que representa a cor padrão da borda de foco nos navegadores WebKit (como o Google Chrome).

# :root

#### •	Define variáveis personalizadas que podem ser usadas em todo o documento para cores, sombras, etc.

#### •	Isso torna mais fácil modificar a aparência do aplicativo, pois as alterações podem ser feitas em um único lugar.

# Seletores universais:

#### Define estilos padrão para todos os elementos, como margem, preenchimento, modelo de caixa e fonte.

# Estilos gerais:

#### •	Define estilos para elementos específicos, como inputs e botões.

#### •	Define a cor de fundo e a cor do texto para o corpo do documento.

#### •	Define estilos para títulos de seção.

# Estilos para elementos específicos:

#### •	Define estilos para um título de saudação que contém um input, usando flexbox para alinhar os elementos.

#### •	Define a cor, tamanho da fonte e peso da fonte para o título e o input.

# Estilos para formulários:

#### •	Define estilos para inputs de texto em um formulário, incluindo largura, espaçamento, cor do texto, cor de fundo, borda e sombra.

#### •	Define estilos para um conjunto de opções em forma de grade.

# Estilos para botões e seletores de opção:

#### •	Esconde inputs de rádio e checkboxes.

#### •	Define estilos para bolhas que são usadas como seletores de opção, incluindo tamanho, borda, sombra e cor.

# Estilos para bolhas:

#### Define estilos para o efeito de seleção nas bolhas, aumentando seu tamanho e opacidade quando estão marcadas.

# Estilos para botões e ações:

#### •	Define estilos para botões de envio em um formulário, incluindo largura, espaçamento, cor do texto, cor de fundo, borda, sombra e transição de opacidade.

#### •	Define estilos para botões de ação em itens de lista de tarefas, incluindo espaçamento, borda, cor do texto, cursor e transição de opacidade.

# Estilos para itens de lista de tarefas:

#### •	Define estilos para a lista de tarefas e itens individuais, incluindo espaçamento, alinhamento, cor de fundo, preenchimento, borda, sombra e margem.

#### •	Define um estilo específico para itens de lista de tarefas concluídos, alterando a aparência do texto riscado.

# Main.js

## Importação de dependências:

#### •	``` import { createApp } from 'vue ``` Importa a função createApp da biblioteca Vue, que é usada para criar uma instância do aplicativo Vue.

#### •	``` import App from './App.vue' ``` Importa o componente principal do aplicativo Vue a partir do arquivo App.vue.

## Importação de arquivos de estilo:

#### •	``` import './style.css' ``` Importa estilos adicionais do arquivo style.css.

#### •	``` import './main.css' ``` Importa estilos adicionais do arquivo main.css.

## Inicialização do aplicativo Vue:

#### •	``` createApp(App) ``` Cria uma instância do aplicativo Vue com o componente principal App.vue.

#### •	``` .mount('#app') ``` Monta o aplicativo Vue no elemento HTML com o ID app. Este elemento serve como o contêiner raiz para todo o aplicativo Vue.

# JavaScript:

```javascript

<script setup>
import { ref, onMounted, computed, watch } from 'vue'

const todos = ref([])
const name = ref('')

const input_content = ref('')
const input_category = ref(null)

const todos_asc = computed(() => todos.value.sort((a,b) =>{
	return a.createdAt - b.createdAt
}))

watch(name, (newVal) => {
	localStorage.setItem('name', newVal)
})

watch(todos, (newVal) => {
	localStorage.setItem('todos', JSON.stringify(newVal))
}, {
	deep: true
})

const addTodo = () => {
	if (input_content.value.trim() === '' || input_category.value === null) {
		return
	}

	todos.value.push({
		content: input_content.value,
		category: input_category.value,
		done: false,
		editable: false,
		createdAt: new Date().getTime()
	})
}

const removeTodo = (todo) => {
	todos.value = todos.value.filter((t) => t !== todo)
}

onMounted(() => {
	name.value = localStorage.getItem('name') || ''
	todos.value = JSON.parse(localStorage.getItem('todos')) || []
})
</script>

```

•	Este bloco de script Vue é configurado com o setup syntax, uma forma compacta e conveniente de definir a lógica do componente.

•	Importa várias funções e objetos do Vue, incluindo ref, onMounted, computed e watch.

•	Define várias variáveis reativas, como todos, name, input_content e input_category, usando a função ref.

•	Calcula uma lista de tarefas ordenadas por data de criação com base na variável todos, usando a função computed.

•	Define observadores (watchers) para name e todos, que monitoram alterações nessas variáveis e atualizam o armazenamento local conforme necessário.

•	Define funções addTodo e removeTodo para adicionar e remover tarefas da lista.

•	No gancho onMounted, inicializa as variáveis name e todos a partir do armazenamento local.

# HTML (Template):

```javascript

<template>
	<main class="app">

```
#### Define a estrutura principal do componente, que contém todo o conteúdo do aplicativo.

```javascript

		<section class="greeting">
			<h2 class="title">
				Eae, <input type="text" id="name" placeholder="Insira seu nome aqui" v-model="name">
			</h2>
		</section>

```

#### Esta seção exibe uma saudação ao usuário, com um campo de entrada para inserir o nome. O nome é vinculado à variável name usando v-model.

```javascript

		<section class="create-todo">
			<h3>Crie uma tarefa</h3>
			<form id="new-todo-form" @submit.prevent="addTodo">

```

#### Esta seção contém um formulário para adicionar uma nova tarefa. O evento @submit.prevent impede o comportamento padrão de envio do formulário.

```javascript

				<h4>O que tem na sua lista de tarefas?</h4>
				<input 
					type="text" 
					name="content" 
					id="content" 
					placeholder="Ex: Fazer um bolo"
					v-model="input_content" />

```

#### Um campo de entrada de texto onde o usuário pode inserir o conteúdo da nova tarefa. O valor é vinculado à variável input_content.

```javascript

				<h4>Escolha uma categoria</h4>
				<div class="options">

```

#### Esta parte permite que o usuário escolha uma categoria para a nova tarefa.

```javascript

					<label>
						<input 
							type="radio" 
							name="category" 
							id="category1" 
							value="business"
							v-model="input_category" />
						<span class="bubble business"></span>
						<div>Negócios</div>
					</label>
					<label>
						<input 
							type="radio" 
							name="category" 
							id="category2" 
							value="personal"
							v-model="input_category" />
						<span class="bubble personal"></span>
						<div>Pessoal</div>
					</label>

```
     
#### Dois botões de rádio permitem que o usuário escolha entre as categorias "Negócios" e "Pessoal". O valor selecionado é vinculado à variável input_category.

```javascript
				<input type="submit" value="Adicionar tarefa" />
			</form>
		</section>

````
  
#### Um botão de envio para adicionar a nova tarefa ao enviar o formulário.

```javascript
		<section class="todo-list">
			<h3>Lista de tarefas</h3>
			<div class="list" id="todo-list">

```
   
#### Esta seção exibe a lista de tarefas existentes.

```javascript
				<div v-for="todo in todos_asc" :class="`todo-item ${todo.done && 'done'}`">

```
    
#### Um loop v-for é usado para iterar sobre todas as tarefas existentes. Cada tarefa é representada por um elemento <div> com a classe todo-item. Se a tarefa estiver marcada como concluída, a classe done será aplicada para exibir um estilo específico.

```javascript
					<label>
						<input type="checkbox" v-model="todo.done" />
						<span :class="`bubble ${
							todo.category == 'business' 
								? 'business' 
								: 'personal'
						}`"></span>
					</label>

```
     
#### •	Um checkbox é usado para marcar uma tarefa como concluída. O estado de conclusão da tarefa é vinculado à variável todo.done.
#### •	Uma bolha é exibida para representar a categoria da tarefa. A classe da bolha é definida com base na categoria da tarefa.

```javascript

<div class="todo-content">
						<input type="text" v-model="todo.content" />
					</div>
					<div class="actions">
						<button class="delete" @click="removeTodo(todo)">Excluir</button>
					</div>
				</div>
			</div>
		</section>
	</main>
</template>

```

#### •	O conteúdo da tarefa é exibido em um campo de entrada de texto, onde o usuário pode editar o conteúdo da tarefa. O conteúdo é vinculado à variável todo.content.
#### •	Um botão "Excluir" é fornecido para remover a tarefa da lista quando clicado.

# Node.js e NPM:

Baixado no site https://nodejs.org/en

Depois de instalado foi verificado no terminal se foi instalado corretamente com node -v e npm -v

Node.js é usado para criar aplicativos de servidor com JavaScript. Ele permite que os desenvolvedores executem código JavaScript fora do navegador, o que significa que podem construir servidores, APIs e aplicativos de linha de comando usando JavaScript.

O npm é o gerenciador de pacotes usado com Node.js. Ele ajuda os desenvolvedores a instalar, compartilhar e gerenciar as bibliotecas e ferramentas que seus aplicativos precisam para funcionar corretamente.

# Vue.js:

#### Instalado no terminal com  npm create vue@latest

#### Depois de configurar usei no terminal cd C:\Users\fazio\OneDrive - UNIOESTE\Área de Trabalho\Faculdade\2º Ano\TDS\AP05

#### Depois vue create e o nome do projeto

#### E depois foi colocado no terminal npm install

#### E a seguir foi colocado no terminal cd nome do arquivo e npm run serve ou run dev

#### Por fim no terminal do vscode foi usado npm run dev para rodar a aplicação em um localhost

# Bootstrap:

#### instalação feita com npm install bootstrap

# Webpack:

#### Instalação feita com npm install webpack webpack-cli –save-dev

#### Pode ser utilizado para empacotar e compilar seus arquivos JavaScript, CSS, etc.

# Repositório git e Codeberg:

https://github.com/JoaoFazio/AP05

#### A criação do repositório foi feita no github em novo repositório e foi atribuído o nome de AP05.

