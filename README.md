# 🧩 PuzzleCare — Plataforma SaaS para Gestão de Clínicas Multidisciplinares

> **⚠️ Projeto pessoal / freelancer**
>
> O PuzzleCare é um projeto desenvolvido por mim como parte das atividades da
> Cronos Solutions Tech, uma agência pessoal independente na qual participo em
> horários não comerciais.
>
> Este repositório contém **apenas a documentação pública** do sistema.
> O código-fonte completo está em repositório privado da organização freelancer,
> utilizado para fins de portfólio e demonstração técnica.

---

![PuzzleCare](https://raw.githubusercontent.com/meaeduarda/saas_puzzlecare/main/saas_puzzlecare.png)

---

## 📋 Sobre o Projeto

O **PuzzleCare** é uma plataforma SaaS desenvolvida para digitalizar e
centralizar a gestão de clínicas multidisciplinares com foco em atendimento
infantil, especialmente casos de Transtorno do Espectro Autista (TEA) e atrasos
no desenvolvimento.

O sistema foi criado a partir de uma necessidade real de uma clínica em
Recife/PE, substituindo processos manuais como planilhas, papéis e comunicação
fragmentada por uma solução integrada para gestão de pacientes, equipe e
acompanhamento terapêutico.

---

## ✨ Funcionalidades

### 👤 Portal do Cliente
- Cadastro com verificação por e-mail (token)
- Autenticação com verificação em duas etapas (2FA)
- Agendamento de visitas com geração de protocolo
- Acompanhamento de planos terapêuticos em PDF
- Painel personalizado com histórico e timeline de atividades

### 🏥 Painel Administrativo
- **Gestão de Pacientes** — cadastro completo, fotos e evolução clínica
- **Grade Terapêutica** — organização de pacientes por sala e profissional
- **Pré-cadastro Clínico** — formulário multi-etapas (identificação, queixa,
  histórico e desenvolvimento)
- **Evoluções Clínicas** — registros diários com anexos (imagens e PDFs)
- **Agenda Integrada** — sincronização com Google Calendar
- **Controle de Visitas** — agendamento e confirmação de atendimento
- **Gestão de Colaboradores** — perfis com níveis de acesso

### 🔐 Segurança
- Hash de senhas com bcrypt
- Autenticação com verificação em duas etapas (2FA)
- Tokens de verificação por e-mail
- Controle de sessão via PHP
- Estrutura com backups automáticos de dados

---

## 🛠 Stack Tecnológica

| Tecnologia | Versão | Função |
|---|---|---|
| **PHP** | 8.3 | Backend e lógica de negócio |
| **Apache** | 2.4 | Servidor web |
| **HTML5 / CSS3 / JavaScript** | — | Frontend |
| **JSON** | — | Persistência de dados estruturados |
| **PHPMailer** | — | Envio de e-mails transacionais |
| **Dompdf** | — | Geração de PDFs clínicos |

---

## 📌 Aprendizados

- Desenvolvimento de sistema SaaS com arquitetura modular
- Autenticação com 2FA e segurança de sessão
- Geração dinâmica de documentos (PDFs clínicos)
- Integração com serviços externos (SMTP e Google Calendar)
- Organização de regras de negócio para ambiente clínico
- Estruturação de sistema com perfis de acesso (RBAC básico)
- Manipulação de uploads e validação de arquivos

---

## 📫 Sobre este projeto

Este projeto faz parte do meu portfólio pessoal como desenvolvedora,
representando experiências práticas com sistemas reais, foco em resolução de
problemas e aplicação de conceitos de engenharia de software em cenários
próximos ao mercado.
