# Diretriz V8 — primeira dobra no celular (páginas de vendas, captura e quiz)

Vale para **qualquer celular**, não só iPhone 11. Sem rolar, a primeira dobra mostra tudo abaixo.

**Página de vendas**, nesta ordem: foto do expert (no topo, atrás da headline, com degradê) → headline →
subheadline curta (2 a 3 linhas) → botão com a largura toda → valor ("a partir de R$ X") →
data / formato / local numa lista curta com ícones.

**Captura**: mesma ordem, com o formulário ou o botão de cadastro no lugar do valor.

**Quiz**: sem foto do expert; abre direto na primeira pergunta, com todas as opções visíveis sem rolar.

## Conferência obrigatória antes de publicar
Com Playwright (`isMobile: true`), o último item da dobra deve terminar acima da altura da tela e sem rolagem horizontal em:
360×640 (Android pequeno) · 375×667 (iPhone SE) · 390×664 (iPhone 13, Safari) · 414×715 (iPhone 11, Safari) · 412×780 (Android grande).
O pior caso é 360×640: se cabe nele, cabe nos outros.
