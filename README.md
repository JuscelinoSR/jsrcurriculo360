# jsrcurriculo360
O Carreira 360 é uma aplicação web que ajuda o usuário a criar currículos profissionais, organizados e compatíveis com sistemas ATS. A ferramenta permite preencher dados, visualizar o currículo em tempo real, analisar pontos de melhoria e exportar em PDF, mantendo os dados salvos apenas no navegador.
# Carreira 360 — Gerador de Currículo ATS

O **Carreira 360** é uma aplicação web desenvolvida para ajudar usuários a criarem currículos profissionais, claros e compatíveis com sistemas ATS.

A ferramenta permite preencher dados pessoais, experiências profissionais, formação acadêmica, cursos, competências e projetos, exibindo uma prévia do currículo em tempo real. Também conta com uma análise educativa de compatibilidade ATS, oferecendo sugestões de melhoria de forma transparente e sem prometer aprovação em processos seletivos.

---

## 📌 Objetivo do projeto

O objetivo do projeto é facilitar a criação de currículos profissionais com uma estrutura simples, organizada e adequada tanto para leitura humana quanto para sistemas de recrutamento automatizados.

Este é um projeto educacional, criado como MVP para prática de desenvolvimento front-end, experiência do usuário, acessibilidade e organização de informações profissionais.

---

## 🚀 Funcionalidades

* Preenchimento de dados pessoais.
* Cadastro de resumo profissional.
* Lista dinâmica de experiências profissionais.
* Lista dinâmica de formação acadêmica.
* Cadastro de cursos e certificações.
* Criação e remoção de competências em formato de tags.
* Cadastro de projetos.
* Prévia do currículo em tempo real.
* Análise ATS educativa com pontuação estimada.
* Comparação local de palavras-chave com a descrição da vaga.
* Salvamento automático no navegador.
* Salvamento manual do rascunho.
* Importação de dados em formato JSON.
* Exportação dos dados em JSON.
* Exportação do currículo em PDF usando a impressão nativa do navegador.
* Opção para limpar todos os dados com confirmação.
* Interface responsiva para desktop, tablet e celular.

---

## 🧠 Análise ATS

A análise ATS é feita localmente no navegador, sem uso de inteligência artificial, API externa ou backend.

A pontuação é apenas uma estimativa orientativa, baseada em critérios verificáveis, como:

* Dados essenciais preenchidos.
* Resumo profissional dentro da faixa recomendada.
* Experiência profissional com informações completas.
* Formação acadêmica preenchida.
* Quantidade mínima de competências.
* Compatibilidade de palavras-chave com uma descrição de vaga, quando informada.

> A análise não garante aprovação em processos seletivos. Ela serve apenas como apoio para melhorar a organização do currículo.

---

## 🔒 Privacidade

Os dados preenchidos pelo usuário ficam armazenados somente no navegador, por meio do `localStorage`.

O projeto não utiliza:

* Banco de dados.
* Backend.
* Autenticação.
* API externa.
* Serviço pago.
* Chaves secretas.
* Supabase.

O usuário pode limpar todos os dados a qualquer momento.

---

## 🛠️ Tecnologias utilizadas

* React
* TypeScript
* Vite
* Tailwind CSS
* shadcn/ui
* Lucide Icons
* TanStack Router
* TanStack Query

---

## 💻 Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

### 2. Acesse a pasta do projeto

```bash
cd seu-repositorio
```

### 3. Instale as dependências

```bash
npm install
```

### 4. Execute o projeto em ambiente local

```bash
npm run dev
```

### 5. Acesse no navegador

```bash
http://localhost:5173
```

---

## 📄 Exportação em PDF

A exportação do currículo é feita com a impressão nativa do navegador usando `window.print()`.

Durante a impressão:

* Apenas o currículo fica visível.
* A interface do sistema é ocultada.
* O layout segue formato A4.
* O currículo mantém estrutura em uma única coluna.
* O modelo é adequado para leitura por pessoas e sistemas ATS.

---

## 📁 Importação e exportação de dados

O usuário pode baixar os dados preenchidos em um arquivo `.json` e importar esse arquivo novamente depois.

Isso permite continuar a edição do currículo sem depender de conta, login ou banco de dados.

---

## 🎨 Identidade visual

A interface foi pensada para transmitir profissionalismo, clareza e confiança.

A identidade visual utiliza:

* Azul-marinho.
* Azul médio.
* Branco.
* Cinzas neutros.
* Verde para indicadores positivos.
* Âmbar para alertas.

O foco principal é manter uma experiência simples, limpa e acessível.

---

## 📱 Responsividade

O projeto foi desenvolvido para funcionar bem em:

* Celulares a partir de 360 px.
* Tablets.
* Desktops.

Em telas maiores, o formulário e a prévia são exibidos lado a lado.
Em telas menores, a navegação é organizada para facilitar a edição e visualização do currículo.

---

## ✅ Critérios do MVP

Este MVP foi estruturado com foco em:

* Fluxo principal funcional.
* Interface responsiva.
* Dados salvos localmente.
* Prévia em tempo real.
* Exportação em PDF.
* Análise ATS transparente.
* Código organizado.
* Experiência simples para o usuário.

---

## ⚠️ Aviso importante

O **Carreira 360** auxilia na organização e melhoria do currículo, mas a revisão final das informações é responsabilidade do usuário.

A ferramenta não deve ser usada para inventar experiências, resultados, formações ou competências.

---

## 📚 Status do projeto

Projeto em desenvolvimento como MVP educacional de bootcamp.

Funcionalidades futuras possíveis:

* Gerador de carta de apresentação.
* Versão personalizada para LinkedIn.
* Sugestões de melhoria por área profissional.
* Modelos adicionais de currículo.
* Histórico de versões locais.
* Análise mais detalhada por tipo de vaga.

---

## 👨‍💻 Autor

Desenvolvido por **Juscelino Silva**.

Projeto criado com foco em aprendizado, carreira, tecnologia e desenvolvimento de soluções úteis para pessoas em busca de crescimento profissional.

---

## 📜 Licença

Este projeto é de uso educacional.
A licença pode ser definida futuramente conforme a evolução do projeto.
