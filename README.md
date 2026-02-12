<h1>🎯 Invisible Countdown Game</h1>
<p>Um jogo simples e desafiador desenvolvido com React.O objetivo é clicar no botão **antes que a contagem regressiva termine</p>
<p>Mas existe um detalhe importante.</p>
<p>⏳ A contagem regressiva NÃO é exibida na tela. O jogador precisa confiar na própria percepção de tempo.</p>

<h2>🕹️ Como Funciona</h2>
<ul>
   <li>O jogo inicia uma contagem regressiva invisível.</li>
   <li>O jogador deve clicar no botão antes que o tempo termine.</li>
   <li>Quanto mais próximo de zero for o clique, maior será a pontuação.</li>
   <li>Após o clique, um modal aparece exibindo a pontuação obtida.</li>
   <li>Se clicar cedo demais → pontuação baixa.</li>
   <li>Se clicar tarde demais → tempo esgotado.</li>
</ul>

  
<h2>🧠 Conceitos Trabalhados</h2>
<ul>
   <li>Manipulação de tempo com `setTimeout` / `setInterval`</li>
   <li>Gerenciamento de estado com React</li>
   <li>Componentização</li>
   <li>Exibição condicional de modal</li>
   <li>Lógica de pontuação dinâmica</li>
   <li>Experiência do usuário (UX)</li>
</ul>


<h2>🛠️ Tecnologias Utilizadas</h2>
<ul>
   <li>⚛️ React</li>
   <li>⚡ Vite</li>
   <li>📦 pnpm</li>
   <li>🧩 JavaScript (ES6+)</li>
   <li>🎨 CSS</li>
</ul>

<h2>📂 Estrutura do Projeto</h2>

├── node_modules/ # Dependências do projeto<br/>
├── public/ # Arquivos públicos<br/>
├── src/ # Código-fonte da aplicação<br/>
│ ├── assets/ # Imagens e recursos<br/>
│ ├── components/ # Componentes reutilizáveis<br/>
│ ├── App.css # Estilos principais<br/>
│ ├── App.jsx # Componente raiz<br/>
│ ├── index.css # Estilos globais<br/>
│ └── main.jsx # Ponto de entrada do React<br/>
│<br/>
├── .gitignore<br/>
├── eslint.config.js<br/>
├── index.html # Template base do Vite<br/>
├── package.json # Dependências e scripts<br/>
├── pnpm-lock.yaml # Lockfile do pnpm<br/>
├── vite.config.js # Configuração do Vite<br/>
└── README.md<br/>

<h2>🏆 Sistema de Pontuação</h2>
<p>🎯 Clique muito próximo do tempo final → Pontuação alta</p>
<p>⏱️ Clique distante do final → Pontuação baixa</p>
<p>❌ Tempo esgotado → Pontuação mínima ou zero</p>

<h2>🎯 Objetivo do Projeto</h2>
<p>Este projeto foi desenvolvido para praticar:</p>
<ol>
   <li>Lógica de tempo em JavaScript</li>
   <li>Manipulação de estado no React</li>
   <li>Estruturação de componentes</li>
   <li>Interação com o usuário</li>
</ol>

<h2>🚀 Como Executar o Projeto</h2>
<p>1️⃣ Clone o repositório => git clone https://github.com/leonardomarcatti/refs_portals.git</p>
<p>Entre na pasta criada e digite: pnpm install </p>
<p>Execute: pnpm run dev --host ip_do_host --port numero_de_porta</p>

<h2>📄 Licença</h2>
<p>Projeto desenvolvido para fins educacionais.</p>

<h2>👨‍💻 Autor</h2>
<p>Desenvolvido utilizando React + Vite + pnpm por Leonardo Marcatti da Silva</p>
