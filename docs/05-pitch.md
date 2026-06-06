# Pitch — TaxAdvisorAI (3 minutos)

> Dica: use slides simples para apoiar. Não precisa ser nada elaborado — fundo limpo, pouco texto, uma imagem por slide. O que importa é você falar com segurança e mostrar o projeto funcionando.

---

## Roteiro

### 1. O Problema (30 segundos)

**O que falar:**

Em dezembro de 2023, o Brasil aprovou a maior reforma tributária desde a Constituição de 1988. A mudança vai afetar empresas, trabalhadores e consumidores — todo mundo. Mas tem um problema: quase ninguém entende o que exatamente vai mudar.

Cinco impostos vão desaparecer. Três novos vão surgir. O período de transição dura até 2033. E as informações disponíveis são ou técnicas demais — textos de lei que ninguém lê — ou rasas demais — manchetes que não explicam nada.

O resultado? Incerteza. Empresários que não sabem se vão pagar mais ou menos. Cidadãos que não sabem o que esperar. Estudantes que precisam entender o tema mas não têm por onde começar.

**Slide sugerido:** título "O problema" + uma frase grande: *"A maior reforma tributária do Brasil. E quase ninguém entende o que muda."*

---

### 2. A Solução (1 minuto)

**O que falar:**

O TaxAdvisorAI é um chatbot educativo que explica a Reforma Tributária em linguagem simples. O usuário digita uma pergunta — qualquer dúvida sobre IBS, CBS, Imposto Seletivo, cronograma, impactos — e recebe uma resposta clara, com exemplos práticos.

Mas o diferencial não é só a interface. É a forma como o agente foi construído:

Primeiro, **guardrails**: o agente tem regras explícitas de comportamento. Ele não responde o que não sabe. Quando a alíquota ainda não foi definida em lei, ele diz isso — em vez de inventar um número. Quando a pergunta está fora do escopo, ele redireciona em vez de tentar responder de qualquer jeito.

Segundo, **base de conhecimento editável**: o conteúdo sobre a reforma fica em arquivos de texto organizados por tema. Para atualizar o agente conforme novas leis complementares são publicadas, basta editar esses arquivos — sem mexer em nenhuma linha de código.

Isso torna o projeto simples de manter e fácil de escalar.

**Slide sugerido:** diagrama da arquitetura (está no `01-documentacao-agente.md`) + lista dos dois diferenciais

---

### 3. Demonstração (1 minuto)

**O que mostrar:**

1. Abrir o TaxAdvisorAI rodando localmente em `localhost:7860`
2. Clicar num dos exemplos prontos — ex.: *"Qual a diferença entre IBS e CBS?"*
3. Mostrar a resposta chegando em streaming (efeito de "digitando")
4. Fazer uma pergunta fora do escopo ao vivo — ex.: *"Me ajuda a declarar o IR?"* — e mostrar o guardrail redirecionando
5. Fazer uma pergunta sobre alíquota — ex.: *"Qual vai ser o percentual do IBS?"* — e mostrar o agente sendo honesto sobre a indefinição

**Dica:** grave uma versão de backup em vídeo antes da apresentação. Demo ao vivo é ótimo, mas conexão de internet e API podem trair na hora errada.

---

### 4. Diferencial e Impacto (30 segundos)

**O que falar:**

Existem vários chatbots de IA por aí. O que diferencia o TaxAdvisorAI é a decisão de não deixar o modelo "voar livre".

Guardrails não são código complicado — são arquivos de texto que qualquer pessoa consegue editar. Isso significa que um professor, um contador ou um jurista pode atualizar o comportamento do agente sem precisar saber programar.

E o impacto potencial é real: democratizar o acesso à informação tributária. Hoje, entender a reforma exige contratar um especialista ou ter tempo para estudar legislação. Com uma ferramenta como essa, qualquer pessoa pode começar a entender o que muda — e tomar decisões mais informadas.

**Slide sugerido:** frase de fechamento — *"Informação tributária acessível para todo mundo."*

---

## Checklist do Pitch

- [ ] Duração máxima de 3 minutos
- [ ] Problema explicado de forma que qualquer pessoa entenda
- [ ] Demonstração ao vivo (ou vídeo de backup gravado)
- [ ] Diferenciais mencionados: guardrails + base editável
- [ ] Impacto explicado em termos práticos
- [ ] Áudio claro e sem ruído de fundo
- [ ] Slides limpos, sem excesso de texto

---

## Link do Vídeo

> Cole aqui o link do pitch quando gravar (YouTube, Loom, Google Drive, etc.)

[Link do vídeo]
