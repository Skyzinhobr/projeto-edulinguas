# 🎓 EduLinguas AI

Sistema web inteligente para acompanhamento pedagógico, análise de desempenho escolar e gestão educacional, desenvolvido com tecnologias modernas de Front-End e integração com Inteligência Artificial.

## 📖 Sobre o Projeto

O **EduLinguas AI** foi criado para auxiliar professores, coordenadores e instituições de ensino no acompanhamento do desempenho dos alunos, oferecendo recursos de análise pedagógica, geração de relatórios, OCR para leitura de gabaritos e apoio por Inteligência Artificial.

A plataforma centraliza informações acadêmicas, facilitando a tomada de decisões pedagógicas através de dashboards, métricas e avaliações em tempo real.

---

# 🎯 Objetivos

* Centralizar dados educacionais.
* Automatizar processos de avaliação.
* Gerar diagnósticos pedagógicos.
* Facilitar o acompanhamento de turmas e alunos.
* Utilizar Inteligência Artificial para apoio educacional.
* Melhorar a análise de desempenho escolar.

---

# 🚀 Funcionalidades

## 📊 Dashboard Inteligente

* Indicadores de desempenho escolar.
* Estatísticas por turma.
* Gráficos interativos.
* Evolução da aprendizagem.

## 👨‍🎓 Gestão de Alunos

* Cadastro de alunos.
* Importação em lote.
* Organização por turmas.
* Histórico de desempenho.

## 👩‍🏫 Gestão de Professores

* Cadastro de professores.
* Sistema de convites.
* Controle de acesso.

## 🏫 Gestão de Turmas

* Criação e gerenciamento de turmas.
* Associação de alunos.
* Controle de desempenho coletivo.

## 📝 Avaliações

* Cadastro de avaliações.
* Correção e acompanhamento.
* Resultados por aluno e turma.

## ✅ Gabaritos

* Criação de gabaritos.
* Correção automatizada.
* Comparação de respostas.

## 📷 OCR de Gabaritos

* Leitura automática de gabaritos.
* Processamento de imagens.
* Extração de respostas.

## 🤖 Inteligência Artificial

* Diagnóstico pedagógico.
* Recomendações educacionais.
* Apoio à análise de resultados.

## 📈 Relatórios

* Relatórios acadêmicos.
* Indicadores de aprendizagem.
* Exportação de dados.

## 🔐 Autenticação

* Login de usuários.
* Cadastro.
* Recuperação de senha.
* Controle de acesso.

---

# 🛠️ Tecnologias Utilizadas

## Front-End

* React 19
* TypeScript
* TanStack Router
* TanStack Query
* Vite

## Interface

* Tailwind CSS
* Radix UI
* Lucide Icons
* Recharts

## Backend e Banco de Dados

* Supabase

## Inteligência Artificial

* Integração com recursos de IA
* Processamento de dados educacionais

## OCR

* jsQR
* Processamento de imagens
* Leitura de gabaritos

---

# 📂 Estrutura do Projeto

```text
src/
│
├── components/
│   ├── layout/
│   └── ui/
│
├── routes/
│   ├── index.tsx
│   ├── alunos.tsx
│   ├── turmas.tsx
│   ├── professores.tsx
│   ├── avaliacoes.tsx
│   ├── gabaritos.tsx
│   ├── relatorios.tsx
│   ├── ocr.tsx
│   └── ia.tsx
│
├── integrations/
│   └── supabase/
│
├── hooks/
│
├── lib/
│
└── data/
```

---

# ⚙️ Como Executar o Projeto

## 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/edulinguas-ai.git
```

## 2. Entrar na pasta

```bash
cd edulinguas-ai
```

## 3. Instalar dependências

```bash
npm install
```

ou

```bash
bun install
```

## 4. Configurar variáveis de ambiente

Crie um arquivo `.env`:

```env
VITE_SUPABASE_URL=sua_url
VITE_SUPABASE_ANON_KEY=sua_chave
```

## 5. Executar

```bash
npm run dev
```

ou

```bash
bun run dev
```

---

# 📚 Conceitos Aplicados

* Componentização com React
* TypeScript
* Gerenciamento de Estado
* Consumo de APIs
* Autenticação
* CRUD
* Responsividade
* Dashboards
* Data Visualization
* OCR
* Inteligência Artificial
* Boas práticas de desenvolvimento

---

# 📸 Telas do Sistema

Adicione aqui capturas de tela do projeto:

* Dashboard
* Gestão de Alunos
* Avaliações
* OCR
* Relatórios
* IA

---

# 👨‍💻 Autor

Desenvolvido por **Flávio Sousa Lima e Daniel Teixeira do Nascimento**.

Projeto acadêmico voltado para inovação educacional e análise pedagógica inteligente.

---

# 📄 Licença

Este projeto foi desenvolvido para fins educacionais e acadêmicos.
