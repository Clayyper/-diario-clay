# Diário do Clay

Diário pessoal de **alimentação, suplementos, exercícios, peso e bioimpedância**, com horários de ingestão ou medição e dados do relógio.

## Arquivos
- [index.html](index.html) — aplicativo HTML com painel de nutrientes, suplementos, treino e bioimpedância, incluindo as diferenças em relação às referências exibidas pelo relógio.
- [dados/2026-10-24.json](dados/2026-10-24.json) — registros estruturados e as medidas de 24/10/2026.
- [relatorios/2026-10-24.md](relatorios/2026-10-24.md) — relatório com cronologia, indicadores e desvios de referência.

## Estado atual

- **Os dados estão neste repositório privado.**
- **A aplicação HTML está versionada aqui**, mas ainda **não foi publicada como site acessível por endereço fixo**.
- O HTML independente usa IndexedDB/localStorage para o banco no navegador; **não recebe automaticamente as atualizações do repositório privado**.
- A sincronização com o ChatGPT já pode gravar arquivos no GitHub quando a conexão estiver habilitada e a operação for executada; mas **a sincronização do navegador requer autenticação segura e ainda não está implementada**.
- Não habilitar GitHub Pages com dados pessoais embutidos no HTML. GitHub Pages pode expor o conteúdo publicado mesmo se o código estiver em repositório privado.

## Horários
Quando a pessoa informa consumo, treino ou medição ao ChatGPT, o horário é o da mensagem (horário local America/Sao_Paulo), salvo quando outro é indicado. Os registros de 24/10 tiveram os horários confirmados explicitamente.

## Referência de bioimpedância
Os sinais +/− do relógio são conservados no campo `referenceDifferences`. A referência aproximada é calculada como **medida − diferença**. Esses valores são meramente os comparativos exibidos pelo dispositivo, **não metas clínicas nem diagnósticos**.
