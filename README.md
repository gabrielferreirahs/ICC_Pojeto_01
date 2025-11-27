# Sistema de Monitoramento de Hábitos (SMH)
Aplicativo mobile para Android e iOS desenvolvido com foco em auxiliar usuários a criar, acompanhar e manter hábitos diários de forma simples e intuitiva.

---

## 1. Contexto e Objetivo

O Sistema de Monitoramento de Hábitos (SMH) tem como objetivo ajudar usuários a organizar seus hábitos diários, como beber água, estudar, praticar exercícios ou ler.  
O aplicativo permite criar hábitos personalizados, marcar hábitos concluídos e visualizar o progresso semanal.  
O foco é promover organização pessoal, disciplina e constância, sem complexidade.

---

## 2. Usuários

| Usuário        | Interesse / Expectativa |
|----------------|--------------------------|
| Usuário Comum  | Criar hábitos e acompanhar o progresso diário |
| Administrador  | Gerenciar contas e manter o sistema funcionando |

---

## 3. Requisitos Funcionais (RF)

| Código | Descrição | Prioridade |
|--------|-----------|------------|
| **RF01** | O sistema deve permitir o cadastro de usuário (nome, e-mail, senha). | Alta |
| **RF02** | O sistema deve permitir login e autenticação de usuários. | Alta |
| **RF03** | O usuário deve poder cadastrar hábitos (nome, horário, frequência). | Alta |
| **RF04** | O usuário deve poder marcar um hábito como “concluído” no dia. | Alta |
| **RF05** | O sistema deve exibir um painel com o progresso dos hábitos na semana. | Média |
| **RF06** | O usuário deve poder editar e excluir seus hábitos. | Média |
| **RF07** | O aplicativo deve enviar lembretes próximos ao horário configurado do hábito. | Média |
| **RF08** | O administrador deve poder visualizar, editar ou excluir contas de usuários. | Baixa |

---

## 4. Requisitos Não Funcionais (RNF)

| Código | Descrição | Categoria | Prioridade |
|--------|-----------|-----------|------------|
| **RNF01** | O aplicativo deve estar disponível durante o horário geral de funcionamento da aplicação. | Confiabilidade | Alta |
| **RNF02** | O tempo de resposta deve ser inferior a 3 segundos por ação. | Desempenho | Média |
| **RNF03** | As senhas devem ser armazenadas com criptografia segura. | Segurança | Alta |
| **RNF04** | A interface deve ser responsiva, intuitiva e adequada ao uso em smartphones. | Usabilidade | Alta |
| **RNF05** | O sistema deve ser desenvolvido como aplicativo móvel para Android e iOS. | Arquitetura | Média |
| **RNF06** | O aplicativo deve permitir fácil manutenção e atualização. | Manutenibilidade | Baixa |
| **RNF07** | O aplicativo deve permitir uso offline para marcar hábitos e sincronizar quando houver conexão. | Usabilidade / Arquitetura | Baixa |

---

## 7. Licença
Este projeto é apenas para fins educacionais.  
Você pode modificá-lo livremente.

---
