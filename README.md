# 🌱 ONG Raízes do Amanhã

Este projeto é uma página institucional para a ONG **Raízes do Amanhã**, com foco em apresentar seus projetos sociais, incentivar o voluntariado e facilitar o cadastro de novos colaboradores.

---

## 📁 Estrutura do Projeto

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


---

## 🧭 Navegação

- `index.html`: Página inicial com apresentação da ONG e seus projetos.
- `projetos.html`: Exibe os projetos em formato de cartões com imagens e tags.
- `cadastro.html`: Formulário completo para cadastro de voluntários.

---

## 🎨 Estilo e Design

- Sistema de design com variáveis CSS (`:root`) para cores, fontes e espaçamentos.
- Layout responsivo com 5 breakpoints (`@media`) para adaptação em diferentes telas.
- Menu hambúrguer funcional em dispositivos móveis.
- Imagens com bordas arredondadas e sombra suave.
- Tags coloridas para categorização dos projetos.

---

## 📝 Formulário de Cadastro

A página `cadastro.html` contém:

- Campos obrigatórios para dados pessoais e complementares.
- Máscaras aplicadas nos campos **CPF**, **Telefone** e **CEP**.
- Validação para aceitar **somente números** nesses campos.
- Botão de envio estilizado e funcional.

---

## 🔒 Validação dos Campos Numéricos

Os campos `CPF`, `Telefone` e `CEP`:

- Têm limite de caracteres (`maxlength`)
- Aceitam apenas números (`inputmode="numeric"` e `pattern="\d{...}"`)
- Bloqueiam letras e símbolos via JavaScript (`keypress`)

---

## 📦 Dependências

Este projeto utiliza:

- [Inputmask](https://github.com/RobinHerbots/Inputmask) para aplicar máscaras nos campos de formulário.

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/inputmask/5.0.8/inputmask.min.js"></script>
