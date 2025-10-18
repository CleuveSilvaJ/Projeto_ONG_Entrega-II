# 🌱 ONG Raízes do Amanhã

Este projeto consiste em uma página institucional para a ONG **Raízes do Amanhã**, com o objetivo de apresentar seus projetos sociais, incentivar o voluntariado e facilitar o cadastro de novos colaboradores.

## 🌐 Site publicado

Acesse aqui:  
👉 [https://cleuvesilvaj.github.io/Projeto_ONG_Entrega-II/](https://cleuvesilvaj.github.io/Projeto_ONG_Entrega-II/)

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript** (utilizado para máscaras e validações de formulário)
- Estrutura de pastas organizada com imagens locais

---

## 📁 Estrutura do Projeto

```
Exp. Prática 2/
├── index.html               
├── projetos.html           
├── cadastro.html            
├── css/
│   └── style.css            
├── assets/
│   └── imagens/
│       ├── banner-raizes.jpg
│       ├── projeto1.jpg
│       ├── projeto2.jpg
│       ├── projeto3.jpg
│       └── cadastro-banner.jpg
```

---

## 🧭 Descrição das Páginas

- **`index.html`**: Apresentação da ONG, missão, visão e chamada para ação.
- **`projetos.html`**: Exibição dos projetos sociais em formato de cartões com imagens e tags.
- **`cadastro.html`**: Formulário completo para cadastro de voluntários.

---

## 🎨 Estilo e Design

- Sistema de design com variáveis CSS (`:root`) para cores, fontes e espaçamentos
- Layout responsivo com 5 breakpoints (`@media`) para adaptação em diferentes dispositivos
- Menu hambúrguer funcional em telas menores
- Imagens com bordas arredondadas e sombra suave
- Tags coloridas para categorização dos projetos

---

## 📝 Formulário de Cadastro

A página `cadastro.html` inclui:

- Campos obrigatórios para dados pessoais e complementares
- Máscaras aplicadas nos campos:
  - **CPF**
  - **Telefone**
  - **CEP**
- Validação para aceitar **somente números**
- Botão de envio estilizado e funcional

---

## 🔒 Validação dos Campos Numéricos

Os campos `CPF`, `Telefone` e `CEP` possuem:

- Limite de caracteres (`maxlength`)
- Aceitação apenas de números (`inputmode="numeric"` e `pattern="\d{...}"`)
- Bloqueio de letras e símbolos via JavaScript (`keypress`)

---

## 📦 Dependências

Este projeto utiliza a biblioteca:

- [Inputmask](https://github.com/RobinHerbots/Inputmask) — para aplicar máscaras nos campos do formulário

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/inputmask/5.0.8/inputmask.min.js"></script>
```

---

## 🖼️ Créditos das Imagens

As imagens utilizadas têm fins acadêmicos e estão armazenadas localmente na pasta:

```
/assets/imagens/
```
