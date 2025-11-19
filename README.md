
# 📌 Ótica da Família – Página de Agendamento de Exames

Este projeto é uma **landing page simples, moderna e responsiva** desenvolvida para a *Ótica da Família*.
A página permite que o usuário preencha seus dados e envie automaticamente um pedido de agendamento de exame via **WhatsApp**.

O site também contém um **modo claro/escuro**, cards animados e máscaras automáticas para CPF e telefone.

---

## 🚀 Tecnologias Utilizadas

* **HTML5**
* **CSS3**
* **Bootstrap 5.3**
* **Bootstrap Icons**
* **jQuery**
* **jQuery Mask**
* **JavaScript (puro)**

---

## 🎯 Funcionalidades

### ✔️ **Formulário com máscaras**

* CPF formatado automaticamente (**000.000.000-00**)
* Telefone com DDD (**(00) 00000-0000**)

### ✔️ **Envio direto para o WhatsApp**

O formulário gera uma mensagem automática contendo:

* Nome
* Telefone
* CPF

E abre o WhatsApp com tudo preenchido.

### ✔️ **Modo Claro e Escuro**

* Transição suave entre temas
* Tema salvo no navegador usando `localStorage`
* Ícone dinâmico (lua/sol)

### ✔️ **Cards animados**

* Animação ao passar o mouse
* Mudança de cores
* Ícones grandes e atraentes

### ✔️ **Botão flutuante do WhatsApp**

* Ícone oficial
* Fica sempre visível para contato rápido
* Aumenta de tamanho ao passar o mouse

---

## 📱 Responsividade

A página foi construída com **Bootstrap**, garantindo:

* Layout totalmente responsivo
* Compatibilidade com celulares, tablets e desktops
* Ajustes automáticos para diferentes tamanhos de tela

---

## 🛠 Como Executar

Não é necessário instalar nada.
Basta abrir o arquivo `index.html` em qualquer navegador moderno.

### Ou subir em serviços como:

* **Netlify**
* **Vercel**
* **GitHub Pages**

---

## 🧩 Estrutura do Projeto

```
/projeto
│── index.html
│── /css  (se desejar separar futuramente)
│── /js   (opcional)
└── /assets (imagens e ícones)
```

Atualmente o código está todo centralizado em um único arquivo HTML.

---

## 📞 Configuração do WhatsApp

O número configurado no código é:

```
558799889431
```

Para alterar, basta substituir onde aparece:

```javascript
https://wa.me/558799889431
```

E também dentro da função de envio no JavaScript.

---

## 🌗 Troca de Tema

O botão de tema:

* Alterna entre `body.light` e `body.dark`
* Salva a preferência no `localStorage`
* Atualiza automaticamente o ícone do botão

---

## 🔒 Segurança e Validações

* Telefone validado antes do envio
* Preenchimento obrigatório dos campos
* Máscaras evitam erros de digitação

---

## 📄 Licença

Este projeto é livre para uso e modificação.

