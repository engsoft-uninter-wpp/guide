# Guia da Comunidade · Engenharia de Software UNINTER 🎓💻

Este é o repositório do portal/guia oficial de estudantes do curso de **Bacharelado em Engenharia de Software da UNINTER**. 

O projeto consiste em um site estático moderno e responsivo que serve como centralizador de links para a comunidade de alunos no WhatsApp, auxiliando na integração, comunicação e partilha de conhecimento acadêmico e profissional.

---

## 📌 Sobre o Projeto

Com as frequentes atualizações da matriz curricular de Engenharia de Software, alunos de turmas e anos diferentes frequentemente cursam disciplinas idênticas ou equivalentes sob nomes distintos. 

Para solucionar o problema de fragmentação e evitar a criação de múltiplos grupos redundantes, este portal organiza a comunidade de acordo com as **UCFCs (Unidades Curriculares de Formação Continuada)** da grade vigente (ano 2025 em diante). Cada grupo da comunidade no WhatsApp unifica:
* As disciplinas da grade curricular atual correspondentes àquela UCFC.
* As disciplinas equivalentes de grades curriculares anteriores.

Dessa forma, independentemente do ano de ingresso no curso, todos os alunos que estão estudando o mesmo conteúdo se encontram no mesmo espaço.

---

## ✨ Funcionalidades Principais

- **🚀 Guia Passo a Passo**: Instruções visuais simples de como o aluno pode identificar suas disciplinas no Ambiente Virtual de Aprendizagem (AVA) da UNINTER e encontrar a UCFC correspondente.
- **📌 Canais de Convivência Gerais**:
  - `Comece por Aqui`: Canal introdutório e de regras (restrito para anúncios).
  - `Avisos`: Comunicados importantes e notícias sobre a comunidade (restrito para anúncios).
  - `Geral`: Bate-papo livre sobre tecnologia, carreira e estudos.
- **🌱 Grupos Acadêmicos por UCFC (1 a 18)**: Organizados por ano do curso (1º ao 4º ano, além de disciplinas Especiais e Eletivas).
- **💼 Grupos Temáticos Especiais**:
  - `Vagas, Cursos e Projetos`: Divulgação curada de oportunidades profissionais, hackathons, cursos adicionais e projetos.
  - `Dúvidas`: Espaço aberto para dúvidas de teor estritamente acadêmico e de funcionamento do AVA.
  - `Grupo das Meninas`: Espaço dedicado para networking, apoio e fortalecimento da presença feminina na área de tecnologia.
- **♿ Acessibilidade**: Construído com tags semânticas do HTML5 e atributos ARIA para garantir uma boa experiência de navegação por leitores de tela.
- **📱 Layout Responsivo**: Desenvolvido seguindo princípios de Mobile-First, oferecendo uma experiência fluida tanto em celulares quanto em desktops.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi intencionalmente construído com tecnologias web fundamentais (Vanilla stack) para garantir velocidade, leveza de carregamento e hospedagem facilitada:

- **HTML5** (Semântico e com recursos de acessibilidade).
- **CSS3** (Variáveis customizadas, Flexbox, Grid Layout, e efeitos visuais como gradientes e micro-animações).

---

## 📂 Estrutura de Arquivos

```text
engsoft-uninter-wpp/
│
├── images/               # Capturas de tela do AVA e ícones da página
├── index.html            # Estrutura principal da página e estilos embutidos
└── README.md             # Esta documentação
```

---

## 🚀 Como Executar Localmente

Como o projeto é um site estático puro (sem dependências de backend ou frameworks complexos), executá-lo é extremamente simples:

1. **Abertura Direta**:
   Basta dar um duplo clique sobre o arquivo `index.html` para abri-lo diretamente em qualquer navegador web de sua preferência (Chrome, Firefox, Edge, Safari, etc.).

2. **Utilizando um Servidor Local (Recomendado)**:
   Se desejar simular um ambiente de produção (para testar caminhos de imagens e links com mais precisão), você pode servir a pasta localmente:
   - **Com VS Code**: Instale a extensão *Live Server*, abra a pasta do projeto e clique no botão **Go Live** no canto inferior direito.
   - **Com Python**: Abra o terminal no diretório do projeto e execute:
     ```bash
     python -m http.server 8000
     ```
     Depois, acesse `http://localhost:8000` no seu navegador.
   - **Com Node.js (npx)**:
     ```bash
     npx serve
     ```

---

## 📝 Contribuição e Atualizações

Para sugerir melhorias no layout, atualizar links de convite de grupos do WhatsApp que foram renovados ou reportar problemas:
1. Abra uma *Issue* detalhando a alteração necessária.
2. Envie um *Pull Request* com as alterações sugeridas.

---

*Desenvolvido com carinho pelos estudantes de Engenharia de Software da UNINTER. 🚀*
