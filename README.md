# 🧩 PuzzleCare — SaaS de Gestão para Clínicas Multidisciplinares

> **⚠️ Aviso**
>
> Este repositório contém **apenas a documentação pública** do projeto.
> O código-fonte completo está armazenado em repositório privado na organização
> da empresa. Esta página existe para fins de portfólio e referência.

---

![PuzzleCare](https://raw.githubusercontent.com/meaeduarda/saas_puzzlecare/main/saas_puzzlecare.png)

---

## 📋 Sobre o Projeto

O **PuzzleCare** é um sistema SaaS completo para gestão de clínicas
multidisciplinares especializadas no atendimento infantil, com foco em crianças
com Transtorno do Espectro Autista (TEA) e atrasos no desenvolvimento.

O sistema foi desenvolvido para atender uma clínica real em Recife/PE,
substituindo processos manuais (planilhas, papéis, WhatsApp) por uma plataforma
unificada que integra clientes, profissionais e gestão clínica.

---

## ✨ Funcionalidades

### 👤 Portal do Cliente
- Cadastro com verificação por e-mail (token)
- Autenticação com fator duplo (2FA) via número de contato
- Agendamento de visitas com geração de protocolo
- Acompanhamento de planos terapêuticos em PDF
- Painel personalizado com timeline

### 🏥 Painel Administrativo
- **Pacientes** — Cadastro completo, fotos, evoluções clínicas
- **Grade Terapêutica** — Alocação de pacientes por sala/profissional
- **Pré-cadastro Clínico** — Formulário multi-etapas (identificação, queixa,
  antecedentes, desenvolvimento, observação clínica)
- **Evoluções** — Registro diário com anexos (fotos, PDFs) e histórico
- **Agenda** — Integração com Google Calendar
- **Visitas** — Controle de agendamentos com confirmação
- **Colaboradores** — Cadastro de profissionais com perfis de acesso

### 🔐 Segurança
- Autenticação com senhas hasheadas (bcrypt)
- Verificação em duas etapas (2FA)
- Tokens de verificação por e-mail
- Sessões gerenciadas por sessão PHP
- Backup automático de dados

## 🛠 Stack Tecnológica

| Tecnologia | Versão | Função |
|---|---|---|
| **PHP** | 8.3 | Backend / Lógica de negócio |
| **Apache** | 2.4 | Servidor web |
| **HTML5 / CSS3 / JavaScript** | — | Frontend |
| **JSON** | — | Armazenamento de dados (estrutura baseada em arquivos) |
| **PHPMailer** | — | Envio de e-mails transacionais |
| **Dompdf** | — | Geração de PDFs |

---

## 📌 Aprendizados

- Arquitetura de software para SaaS com foco em clínicas de saúde
- Implementação de autenticação com verificação em duas etapas
- Geração dinâmica de PDFs com dados clínicos
- Integração com APIs de e-mail (SMTP) e WhatsApp
- Gerenciamento de sessão e controle de acesso por perfil
- Manipulação de uploads e anexos com validação de tipos/tamanho


> 📫 Para mais informações sobre o projeto, entre em contato.
