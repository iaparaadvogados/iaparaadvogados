# Skills e Agentes de IA para o Direito

Skills e agentes de IA são formas de organizar instruções, processos e capacidades reutilizáveis para modelos de Inteligência Artificial.

No contexto jurídico, eles podem ser usados para criar assistentes especializados em tarefas como análise de contratos, pesquisa jurisprudencial, revisão de peças, triagem de documentos, organização de processos e produção de conteúdo.

---

## O que são skills de IA?

Skills são conjuntos de instruções, arquivos, exemplos e procedimentos que ajudam um agente de IA a executar uma tarefa específica de forma mais consistente.

Em vez de escrever o mesmo prompt toda vez, uma skill pode documentar:

- Objetivo da tarefa
- Quando usar
- Como executar
- Quais critérios seguir
- Quais erros evitar
- Qual formato de resposta entregar
- Quais fontes devem ser consultadas
- Quais limites a IA deve respeitar

---

## Referências públicas sobre skills

### Anthropic Skills

Repositório público com implementação de skills para Claude.

Link: [Anthropic Skills](https://github.com/anthropics/skills)

Útil para:

- Entender como estruturar skills
- Criar capacidades reutilizáveis
- Organizar instruções para agentes
- Estudar padrões de automação com IA

---

### Agent Skills

Página sobre o padrão Agent Skills, usado para estruturar capacidades reutilizáveis para agentes de IA.

Link: [Agent Skills](https://agentskills.io/home)

Útil para:

- Entender o padrão de skills
- Criar skills portáveis
- Documentar agentes
- Organizar automações com IA

---

### Claude Code Best Practices

Guia com boas práticas para uso de Claude Code, incluindo configuração de projeto, contexto e integrações.

Link: [Claude Code Best Practices](https://www.anthropic.com/engineering/claude-code-best-practices)

Útil para:

- Projetos com agentes de IA
- Organização de contexto
- Uso de arquivos de configuração
- Desenvolvimento assistido por IA

---

## Ideias de skills para advogados

### Skill de pesquisa jurídica

Objetivo: apoiar a pesquisa inicial sobre temas jurídicos, separando hipóteses, fundamentos, dúvidas e pontos que precisam ser validados.

Possíveis usos:

- Levantar temas relevantes
- Organizar linhas de argumentação
- Criar roteiro de pesquisa
- Separar legislação, doutrina e jurisprudência
- Indicar pontos que exigem validação

---

### Skill de validação de jurisprudência

Objetivo: ajudar o advogado a verificar se uma jurisprudência citada por IA realmente existe, está atualizada e faz sentido para o caso.

Possíveis usos:

- Checar precedentes
- Identificar risco de jurisprudência falsa
- Verificar aderência ao caso
- Listar dados mínimos do julgado
- Recomendar validação em fonte oficial

---

### Skill de análise de contratos

Objetivo: revisar contratos, identificar riscos, inconsistências, omissões e cláusulas que merecem atenção.

Possíveis usos:

- Revisar cláusulas
- Criar checklist de riscos
- Comparar versões
- Apontar obrigações das partes
- Sugerir perguntas para o cliente

---

### Skill de revisão de petições

Objetivo: revisar clareza, estrutura, coerência, fundamentação e riscos de uma peça jurídica.

Possíveis usos:

- Melhorar organização
- Revisar linguagem
- Encontrar contradições
- Criar sumário dos argumentos
- Verificar se pedidos e fundamentos estão alinhados

---

### Skill de marketing jurídico

Objetivo: apoiar a criação de conteúdo jurídico informativo, respeitando limites éticos e evitando promessas de resultado.

Possíveis usos:

- Criar artigos educativos
- Gerar posts para redes sociais
- Adaptar linguagem para público leigo
- Criar FAQs
- Planejar calendário editorial

---

## Modelo básico de skill jurídica

```md
# Skill: Validação de Jurisprudência

## Objetivo

Ajudar o usuário a verificar se uma jurisprudência citada por IA ou encontrada em pesquisa preliminar realmente existe, é relevante e está atualizada.

## Quando usar

Use esta skill quando o usuário quiser:

- Conferir uma jurisprudência citada por IA
- Validar um precedente
- Verificar se um julgado existe
- Checar se uma decisão ainda é aplicável
- Reduzir risco de usar jurisprudência falsa ou desatualizada

## Procedimento

1. Identifique os dados citados:
   - Tribunal
   - Número do processo
   - Relator
   - Órgão julgador
   - Data de julgamento
   - Data de publicação
   - Ementa
   - Tese atribuída ao julgado

2. Aponte dados ausentes ou suspeitos.

3. Separe o que está claro do que precisa ser validado.

4. Oriente a conferência em fonte oficial.

5. Não confirme a existência do julgado sem fonte verificável.

## Regras

- Não invente número de processo.
- Não crie ementa.
- Não atribua tese a tribunal sem confirmação.
- Não trate a resposta da IA como fonte oficial.
- Informe quando os dados forem insuficientes.
- Recomende validação em base oficial ou ferramenta verificável.

## Formato de resposta

1. Dados identificados
2. Pontos que precisam de validação
3. Riscos encontrados
4. Sugestão de busca
5. Próximo passo recomendado
```
