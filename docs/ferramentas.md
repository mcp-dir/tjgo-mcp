# Ferramentas

Jurisprudência TJGO expõe 3 ferramentas (todas somente leitura).

### 1. `jurisprudencia_buscar`
**Input**: `termo`, `tipo` (opcional), `tribunais` (opcional), `data_de` (opcional), `data_ate` (opcional), `ordenar` (opcional), `max` (opcional)

Busca jurisprudência (acórdãos, súmulas, orientações jurisprudenciais, temas) por termo ou tese.

### 2. `jurisprudencia_sumulas`
**Input**: `termo`, `max` (opcional)

Busca SÚMULAS (incluindo vinculantes) por termo.

### 3. `jurisprudencia_documento`
**Input**: `id` (opcional), `numeracao` (opcional), `tribunal` (opcional), `ids` (opcional)

Lê o INTEIRO TEOR de uma decisão (texto completo do acórdão, não o resumo).

## Prompts de exemplo

```
Pesquise jurisprudência do TJGO direto do Claude, ChatGPT ou do seu agente. Cada acórdão vem com órgão julgador, relator, data, o trecho que casou a busca e o link no site oficial. O acervo publicado deste tribunal está com defasagem, e a própria resposta avisa isso com a data mais recente que encontrou, para você conferir no site oficial antes de tratar uma decisão como o estado atual. A mesma conexão alcança outros 16 tribunais. Grátis, sem login.
Jurisprudência do TJGO sobre usucapião extraordinário
Como o TJGO decide dano moral em relação de consumo?
Leia o inteiro teor do acórdão que você achou e resuma a tese
```
