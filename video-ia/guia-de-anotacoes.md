# Guia de anotações — Da pizza ao agente de IA

Material baseado no texto das aulas 6 a 10 enviado pelo usuário. Narração sintética. O vídeo explica os conceitos e fluxos, mas não substitui executar os projetos das aulas. Tempos de legendas aproximados.

## Aula 6 — O universo da IA
- IA → machine learning → deep learning → IA generativa: qual diferença?
- Token é ______; embedding é ______.
- Por que temperatura baixa não garante a verdade?
- Pré-treinamento, ajuste fino, destilação e MoE: explique uma diferença.
- Janela de contexto: o que fica na mesa?
- Bom pedido: papel, contexto, tarefa, formato e limites.
- Git / GitHub / Pages: três funções diferentes.
- Meu exemplo de critério “pronto quando”: ______.

## Aula 7 — Análise confiável
- Unidade de cada linha: item. Pedidos: id_pedido distintos.
- Faturamento = soma de preco_total.
- Ticket médio = faturamento ÷ pedidos; não ÷ linhas.
- preco_total já inclui quantidade. Converta moeda em texto antes de somar.
- Último mês incompleto: destacar e evitar comparação enganosa.
- Dados de controle do material: 48.620 linhas; 21.350 pedidos; R$ 4.089.300,25 de faturamento; ticket de R$ 191,54.
- Não force 80/20; não afirme causa sem evidência.
- Que dado pessoal eu deveria remover antes de enviar? ______.

## Aula 8 — Agentes e dashboard
- Ciclo: planejar → agir → observar → ajustar.
- Quem executa ferramentas é o aplicativo.
- Workflow tem passos definidos; agente escolhe próximos passos.
- Injeção de prompt: conteúdo externo não deve virar ordem.
- Critério verificável: filtro Frango altera 3 KPIs e 4 gráficos.
- CSV → script → JSON < 200 KB → navegador.
- Testar 390 px; pedir evidência, não promessa.

## Aula 9 — App com spec
- Especificar → planejar → tarefas → implementar → verificar.
- História de usuário: como [quem], quero [o quê], para [por quê].
- Dado / Quando / Então: escreva seu exemplo.
- 2 × R$ 66,25 + R$ 76,25 = R$ 208,75.
- Casos de borda: vazio, zero, recarregamento, tamanhos indisponíveis.
- LocalStorage não sincroniza aparelhos; CSV diário é backup.
- AGENTS.md guarda regras; skills guardam procedimentos reutilizáveis.

## Aula 10 — API, RAG e MCP
- API: programa chama o modelo. Tokens de entrada e saída podem gerar custo.
- Não expor chave no HTML. .env fora do Git. Chave vazada deve ser revogada.
- Embeddings ajudam a buscar por significado.
- RAG: preparar índice → recuperar trechos → responder com fonte.
- RAG não é treinar nos PDFs e não elimina alucinações.
- Sem resposta: dizer que não encontrou.
- Trecho errado: investigar busca. Trecho certo e resposta errada: modelo/prompt.
- MCP: clientes e servidores conectam ferramentas, recursos e prompts.

## Minha aplicação prática
1. Problema que quero resolver: ______.
2. Dados e contexto necessários: ______.
3. Três critérios verificáveis: ______.
4. Como vou conferir os resultados: ______.

## Fontes-base
- https://natan-docs.gitbook.io/ia+dados/ia-na-pratica/aula-06-universo-da-ia
- https://natan-docs.gitbook.io/ia+dados/ia-na-pratica/aula-07-relatorio-com-ia
- https://natan-docs.gitbook.io/ia+dados/ia-na-pratica/aula-08-agentes-e-dashboard
- https://natan-docs.gitbook.io/ia+dados/ia-na-pratica/aula-09-app-com-spec
- https://natan-docs.gitbook.io/ia+dados/ia-na-pratica/aula-10-agente-rag-mcp

Base efetivamente usada: texto integral fornecido na conversa, sem nova consulta aos sites. Valores de planos, rankings e modelos sujeitos a mudanças não foram tratados como condições atuais.
