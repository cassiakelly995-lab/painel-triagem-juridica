# ⚖️ Painel CAD V8 — Triagem Jurídica

> Painel interno de gestão da Comissão de Assistência e Advocacia Dativa (CAD) da OAB Santana de Parnaíba — 247ª Subseção.

---

## 🎯 Problema que resolve

A CAD atendia dezenas de cidadãos por semana com controle manual de escala, trocas de plantão e registros em papel. Processos lentos, sujeitos a erro, sem histórico confiável.

Este painel centralizou tudo em um sistema web acessível de qualquer dispositivo, sem instalação.

**Resultado:** processo de nomeação reduzido de 60 para 10 minutos. 15 horas semanais recuperadas. 100% dos registros rastreáveis.

---

## ✨ Funcionalidades

| Módulo | O que faz |
|---|---|
| 📅 **Triagem** | Escala visual de plantão com upload de imagem oficial |
| 🔄 **Trocas e Faltas** | Registro de substituições com autocomplete de advogados |
| 📊 **Relatório Excel** | Exportação automática de toda a escala em `.xlsx` |
| 📄 **Convênio** | Informações do convênio OAB/DPE-SP editáveis |
| 📁 **Documentos** | Repositório com upload para Firebase Storage |
| 👥 **Comissão** | Cadastro de membros e contatos institucionais |
| 📢 **Avisos** | Publicação de comunicados com níveis (info/alerta/urgente) |
| 🔐 **Admin** | Modo presidência com senha — oculta controles sensíveis |

---

## 🛠️ Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

- **Firebase Realtime Database** — sincronização em tempo real entre dispositivos
- **Firebase Storage** — armazenamento de documentos e escala
- **SheetJS (xlsx)** — geração de relatórios Excel no browser
- **TailwindCSS** — estilização responsiva
- **Font Awesome** — iconografia

---

## 📸 Estrutura do sistema

```
painel-triagem-juridica/
└── index.html        ← aplicação completa em arquivo único
```

> Toda a lógica, estilo e integração Firebase estão em um único arquivo HTML — decisão intencional para facilitar deploy via GitHub Pages sem build step.

---

## 🚀 Como usar

1. Acesse o link do GitHub Pages
2. Navegue pelas abas: Triagem, Convênio, Documentos, Comissão, Avisos
3. Para funções administrativas: clique no ícone de usuário no cabeçalho e insira a senha da presidência

---

## 💡 Contexto

Projeto real desenvolvido e implantado na **OAB Santana de Parnaíba — 247ª Subseção**, em uso ativo desde 2025. Desenvolvido de forma autodidata para resolver uma dor real do dia a dia institucional.

> *"Construí porque precisava. Funciona porque testei na prática."*

---

## 👩‍💻 Autora

**Cássia Kelly Lins Reis**
Analista de Projetos & Desenvolvedora de Soluções Digitais
[github.com/cassiakelly995-lab](https://github.com/cassiakelly995-lab)
