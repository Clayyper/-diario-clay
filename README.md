# Diário Clay

Diário de alimentação, suplementos, treinos, peso e bioimpedância.

## Links
- **Aplicativo (após habilitar o GitHub Pages):** https://clayyper.github.io/-diario-clay/
- **Dados:** [dados/2026-10-24.json](dados/2026-10-24.json)
- **Índice de dias:** [dados/index.json](dados/index.json)
- **Relatório:** [relatorios/2026-10-24.md](relatorios/2026-10-24.md)

## Funcionamento
O painel do GitHub Pages consulta os arquivos JSON do repositório ao abrir e ao clicar em "Atualizar do GitHub". O índice `dados/index.json` deve conter todos os dias armazenados. Novas refeições comunicadas pelo chat podem ser acrescentadas ao JSON do dia com a conexão autorizada ao GitHub, após confirmação de gravação. O painel publicado é **somente leitura**; não grava no GitHub por conta própria.

## Publicação
O proprietário precisa ativar Settings → Pages → Deploy from a branch → main → / (root) → Save. O GitHub Pages pode levar alguns minutos para publicar.

## Aviso de privacidade
**O repositório é público.** Isso expõe os arquivos, incluindo dados de peso, suplementação, alimentação e composição corporal, mesmo sem CPF. Alterar posteriormente para privado não garante apagar cópias já disponibilizadas na internet. Publicar apenas dados que aceitaria tornar públicos.

## Medições e horários
Os horários de 24/10/2026 foram informados pelo usuário, e a bioimpedância foi registrada às 14h36. Valores alimentares são estimativas. Diferenças exibidas pelo relógio são referências do dispositivo, não metas clínicas.

## Análise para hipertrofia — atualização de 25/10/2026

O dashboard inclui **25 variáveis nutricionais** (7 existentes + 18 novas): proteínas, energia, carboidratos, gorduras, saturadas, sódio, colesterol, açúcares, fibras, vitaminas A/B1/B6/B9/B12/C/D/E, magnésio, potássio, cálcio, ferro, zinco, fósforo, leucina e água dos alimentos.

- Os registros de **24 e 25/10/2026** foram reprocessados, mantendo horários e quantidade originalmente informados.
- Os **macronutrientes anteriores foram preservados**, pois rótulos e receitas exatas não permitem recalcular valores diferentes com precisão.
- Novos nutrientes usam **estimativas genéricas**, mostradas como **parciais** sempre que existam alimentos sem informação.
- Não atribuímos vitamina C numérica ao suco de acerola diluído sem a proporção de fruta e água. Ele tem vitamina C, porém o teor ingerido é **não determinado**.
- Complexo B e creatina continuam calculados com base nos rótulos fornecidos.
- Esquema completo: [dados/esquema-nutricional.json](dados/esquema-nutricional.json).

Ao adicionar novos alimentos por meio do ChatGPT, registrar os nutrientes conhecidos nas chaves do esquema e **deixar as demais ausentes ou null**, nunca inventar zero. Isso impede totais de vitaminas falsamente completos. A leitura do site é atualizada pelos arquivos JSON do GitHub.
