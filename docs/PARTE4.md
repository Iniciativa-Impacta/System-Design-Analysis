# PARTE 4 - Exercício Prático: Lib Virtual - Plataforma de Assinatura de E-books

## Dinâmica em Sala de Aula

### Objetivo Geral

Construir um SRS completo para a **Lib Virtual - Plataforma de Assinatura de E-books** através de colaboração entre stakeholders e analistas, simulando um projeto real.

## Objetivos Específicos

1. Praticar a análise e documentação de requisitos de software
2. Simular colaboração entre stakeholders e equipe de desenvolvimento
3. Construir um SRS estruturado
4. Exercitar técnicas de elicitação de requisitos
5. Desenvolver habilidades de comunicação técnica

## Estrutura de Grupos

### Composição
- **5 a 6 pessoas por grupo**
- Todos os papéis devem ser representados

### Papéis e Responsabilidades

#### 1. **Facilitador**
- **Responsabilidade:** Coordena a discussão e garante que todos participem
- **Atividades:**
  - Distribui tempo equitativamente
  - Certifica que todos têm voz
  - Mantém foco nos objetivos
  - Documenta decisões importantes
  - Resolve conflitos construtivamente

#### 2. **Stakeholders** (2 pessoas)
- **Responsabilidade:** Representam os usuários da plataforma (leitores, autores, editoras)
- **Perspectivas:**

**Leitor (Assinante):**
- Precisa acessar catálogo de e-books
- Ler e-books em múltiplos dispositivos
- Sincronizar progresso de leitura
- Receber recomendações personalizadas
- Gerenciar assinatura

**Autor Independente:**
- Precisa publicar e-books na plataforma
- Acompanhar métricas de leitura
- Receber remuneração proporcional
- Definir disponibilidade e preços
- Acessar dashboard analítico

**Editora:**
- Precisa gerenciar catálogo digital
- Controlar direitos autorais
- Visualizar relatórios de consumo
- Receber repasses financeiros
- Definir estratégias de distribuição

#### 3. **Analistas de Requisitos** (2 pessoas)
- **Responsabilidade:** Elicitar e documentar os requisitos
- **Atividades:**
  - Fazer perguntas esclarecedoras
  - Traduzir necessidades em requisitos
  - Classificar em funcionais e não-funcionais
  - Priorizar
  - Documentar no template

## Cronograma da Dinâmica (~60 minutos)

### **Parte 1: Preparação** (~5 minutos)
- Divisão em grupos
- Atribuição de papéis
- Distribuição de materiais (MIRO board, post-its virtuais)
- Leitura rápida do propósito

### **Parte 2: Levantamento de Requisitos** (~20 minutos)

#### Fase A: Stakeholders Falam (10 min)
Os stakeholders **listam suas necessidades e expectativas** para o sistema.

**Exemplos de Necessidades por Stakeholder:**

**Leitor (Assinante):**
- "Preciso buscar e-books por gênero, autor ou palavra-chave"
- "Preciso ler em celular, tablet e computador"
- "Preciso que meu progresso sincronize entre dispositivos"
- "Preciso de recomendações baseadas no meu gosto"
- "Preciso gerenciar minha assinatura facilmente"

**Autor Independente:**
- "Quero publicar meus e-books com autonomia"
- "Quero saber quantas pessoas leram meu livro"
- "Quero ver quanto vou receber por mês"
- "Quero definir preço base dos meus livros"
- "Quero dashboard com estatísticas detalhadas"

**Editora:**
- "Queremos enviar catálogo completo para a plataforma"
- "Queremos controlar quais livros ficam disponíveis"
- "Queremos relatório de consumo por título"
- "Queremos receber pagamentos mensais transparentes"

#### Fase B: Analistas Fazem Perguntas (10 min)
Os **analistas de requisitos fazem perguntas** para esclarecer as necessidades.

**Exemplos de Perguntas:**

Para o Leitor:
- "Quais informações são importantes ao buscar um e-book?"
  - Respostas esperadas: título, autor, sinópse, categoria, avaliações, número de páginas
- "Como você quer marcar sua leitura? Favoritos, marcações, notas?"
- "Precisa ler offline? Como deve funcionar?"
- "Que tipo de recomendações você espera?"

Para o Autor:
- "Quais informações você quer monitorar sobre suas obras?"
  - Respostas esperadas: número de leitores, tempo médio de leitura, abandono, conclusão, avaliações
- "Como deve funcionar o cálculo de remuneração?"
- "Quer definir disponibilidade regional dos e-books?"

Para a Editora:
- "Como vocês querem enviar os e-books? Upload individual ou em lote?"
- "Que formato de relatório é necessário?"
- "Como querem controlar direitos autorais e licenciamento?"

**Use post-its (virtuais) para anotar cada requisito identificado.**

### **Parte 3: Classificação e Priorização** (~10 minutos)

#### Passo 1: Classificar (5 min)

Organize os requisitos em:

**Requisitos Funcionais (O QUE):**
- "O sistema DEVE permitir cadastro de e-books"
- "O sistema DEVE permitir busca por autor, gênero e palavra-chave"
- "O sistema DEVE processar assinaturas recorrentes"
- "O sistema DEVE sincronizar progresso de leitura entre dispositivos"
- "O sistema DEVE calcular remuneração proporcional ao consumo"

**Requisitos Não-Funcionais (COMO):**
- "O sistema DEVE abrir e-books em menos de 2 segundos"
- "O sistema DEVE criptografar dados de pagamento"
- "A interface de leitura DEVE ser intuitiva e responsiva"
- "O sistema DEVE funcionar em iOS, Android e Web"
- "O sistema DEVE estar disponível 99.9% do tempo"

**Restrições:**
- "Deve estar em conformidade com LGPD"
- "Orçamento máximo: R$ 200.000"
- "MVP deve estar pronto em 6 meses"
- "Deve suportar formatos EPUB e PDF"

#### Passo 2: Priorizar (5 min)

Use escala simples:

| Nível | Descrição | Exemplos |
|-------|-----------|----------|
| **ALTA** | Crítico para operação | Cadastro, busca, leitura, assinatura |
| **MÉDIA** | Importante mas não crítico | Recomendações, dashboard autor |
| **BAIXA** | Nice-to-have | Notificações, gamificação |

**Matriz de Priorização:**

```
┌──────────────────────────────────────────────┬──────────┐
│ Requisito                                   │ Prioridade│
├──────────────────────────────────────────────┼──────────┤
│ Cadastro de e-books                          │ ALTA     │
│ Busca de e-books                             │ ALTA     │
│ Leitura digital multi-dispositivo            │ ALTA     │
│ Processamento de assinaturas                 │ ALTA     │
│ Sincronização de progresso                    │ ALTA     │
│ Cálculo de remuneração                       │ MÉDIA    │
│ Dashboard de autor/editora                   │ MÉDIA    │
│ Sistema de recomendações                     │ BAIXA    │
│ Notificações automáticas                     │ BAIXA    │
└──────────────────────────────────────────────┴──────────┘
```

### **Parte 4: Documentação no SRS** (~10 minutos)

Organize os requisitos no **template simplificado do MIRO:**

```
LIB VIRTUAL - PLATAFORMA DE ASSINATURA DE E-BOOKS
Data: 04/02/2026
Grupo: [Nome do Grupo]

═══════════════════════════════════════════════════════════

REQUISITOS FUNCIONAIS

RF-001: Cadastro de E-books
├─ Prioridade: ALTA
├─ Descrição: O sistema DEVE permitir cadastro de e-books com os seguintes campos obrigatórios: ISBN, título, autor, editora, categoria, formato (EPUB/PDF)
├─ Ator: Autor, Editora
└─ Caso de Uso: Publicar E-book

RF-002: Busca de E-books
├─ Prioridade: ALTA
├─ Descrição: O sistema DEVE permitir busca de e-books por título, autor, categoria, ISBN ou palavra-chave
├─ Ator: Leitor
└─ Critério de Aceitação: Resultado em menos de 2 segundos

RF-003: Leitura Digital
├─ Prioridade: ALTA
├─ Descrição: O sistema DEVE permitir leitura de e-books em múltiplos dispositivos (Web, iOS, Android)
├─ Ator: Leitor
└─ Restrição: Apenas assinantes ativos podem ler

RF-004: Processamento de Assinatura
├─ Prioridade: ALTA
├─ Descrição: O sistema DEVE processar assinaturas recorrentes mensais com cobrança automática
├─ Ator: Sistema (automático)
└─ Pós-condição: Assinatura ativa ou cancelada

RF-005: Sincronização de Progresso
├─ Prioridade: ALTA
├─ Descrição: O sistema DEVE sincronizar progresso de leitura entre todos os dispositivos do leitor
├─ Ator: Sistema (automático)
└─ Métrica: Sincronização em tempo real (< 5 segundos)

RF-006: Cálculo de Remuneração
├─ Prioridade: MÉDIA
├─ Descrição: O sistema DEVE calcular remuneração de autores/editoras proporcional ao tempo de leitura de suas obras
├─ Ator: Sistema (automático)
└─ Fórmula: Baseado em páginas lidas vs total do catálogo

RF-007: Dashboard Analítico
├─ Prioridade: MÉDIA
├─ Descrição: O sistema DEVE fornecer dashboard com métricas de desempenho para autores e editoras
├─ Ator: Autor, Editora
└─ Métricas: Leitores únicos, tempo médio, taxa de conclusão, receita

═══════════════════════════════════════════════════════════

REQUISITOS NÃO-FUNCIONAIS

RNF-001: Performance
├─ Descrição: O sistema DEVE abrir e-books em menos de 2 segundos
└─ Métrica: Tempo de carregamento < 2s para 95% das aberturas

RNF-002: Segurança
├─ Descrição: O sistema DEVE criptografar dados de pagamento e proteger conteúdo contra pirataria
└─ Implementação: PCI-DSS compliance, DRM para e-books

RNF-003: Disponibilidade
├─ Descrição: O sistema DEVE estar disponível 99.9% do tempo
└─ SLA: Máximo 43 minutos de downtime por mês

RNF-004: Usabilidade
├─ Descrição: Interface de leitura DEVE ser intuitiva e acessível
└─ Padrão: WCAG 2.1 nível AA

═══════════════════════════════════════════════════════════

RESTRIÇÕES

REST-001: Conformidade
├─ Descrição: Deve estar em conformidade com LGPD para dados pessoais
└─ Validação: Auditoria externa obrigatória

REST-002: Formatos
├─ Descrição: MVP deve suportar EPUB e PDF
└─ Justificativa: Formatos mais comuns no mercado

REST-003: Prazo
├─ Descrição: MVP deve estar pronto em 6 meses
└─ Data Limite: 18/08/2026

REST-004: Orçamento
├─ Descrição: Orçamento máximo de R$ 200.000 para MVP
└─ Breakdown: 60% desenvolvimento, 20% infraestrutura, 20% marketing
```

### **Parte 5: Apresentação e Feedback** (~15 minutos)

#### Apresentação (8 min)
Cada grupo apresenta:
1. **Stakeholders representados** (Quem fez as solicitações?)
2. **Requisitos funcionais coletados** (Principais 3-5)
3. **Requisitos não-funcionais** (Restrições identificadas)
4. **Priorização** (O que é crítico?)
5. **Desafios encontrados** (O que foi difícil?)

#### Feedback (7 min)
**Professor e demais grupos fornecem feedback:**
- "Vocês consideraram requisitos de segurança?"
- "Todos os requisitos são verificáveis?"
- "Há conflitos entre requisitos?"
- "A priorização faz sentido?"
- "Faltou pensar em algo?"

## Exemplo de Resultado Final

### Requisitos Coletados - Grupo A

**Funcionalidades Críticas:**
- Cadastro de e-books (ISBN, título, autor, editora, categoria, formato)
- Busca avançada (por autor, título, categoria, palavra-chave)
- Leitura multi-dispositivo com sincronização de progresso
- Processamento de assinaturas recorrentes
- Cálculo de remuneração proporcional ao consumo

**Não-Funcionais:**
- Performance: Abertura de e-book em < 2 segundos
- Segurança: Dados de pagamento criptografados, DRM anti-pirataria
- Disponibilidade: 99.9% uptime
- 📱 Interface: Web, iOS e Android com design responsivo

**Diferenciais da Lib Virtual:**
- Dashboard analítico completo para autores
- Transparência total na remuneração
- Recomendações personalizadas por IA
- Modelo sustentável para autores independentes

## 🎓 Aprendizados Esperados

1. **Elicitação de Requisitos:** Como fazer boas perguntas
2. **Comunicação Técnica:** Traduzir necessidades em linguagem técnica
3. **Priorização:** O que é realmente importante
4. **Documentação:** Como deixar claro para a equipe técnica
5. **Colaboração:** Diferentes perspectivas enriquecem soluções

---

**Reflexão Final:** *"O sucesso de um projeto começa com a compreensão clara do que precisa ser feito."*
