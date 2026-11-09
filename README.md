# Simulador de Crédito Habitação

Página web que simula um crédito habitação em Portugal: prestação mensal, juros, imposto do selo e o efeito de amortizar antes do tempo.

**Problema que resolve:** antes de ir ao banco é difícil perceber quanto vai custar uma casa ao longo de 30 ou 40 anos. Aqui vês a prestação, quanto pagas de juros e quanto poupas se amortizares.

🔗 **Experimenta online:** https://martiinnsss.github.io/credito-habitacao/

## Funcionalidades

- **Taxa variável** (Euribor + spread) ou **taxa fixa**
- Prestação mensal, montante financiado, **total de juros** e total pago ao banco
- **Imposto do selo** sobre o crédito (0,6%) e sobre os juros (4%, quando não é habitação própria e permanente)
- **Taxa de esforço** a partir do rendimento do agregado, com aviso quando fica alta
- Aviso quando o financiamento passa dos 90% do valor da casa
- Teste de stress: quanto sobe a prestação se a taxa subir 1 ponto percentual
- **Amortização antecipada:** valor e ano, a reduzir o prazo ou a prestação, com a comissão de reembolso (0,5% em taxa variável, 2% em taxa fixa)
- Gráfico de capital e juros pagos por ano e tabela de amortização
- Funciona no computador e no telemóvel, sem instalar nada

## Como usar

Abre o ficheiro `index.html` no browser.

## Limitações

- Considera a mesma taxa durante todo o prazo; em taxa variável, a prestação muda sempre que a Euribor é revista
- Não inclui seguros, comissões bancárias, avaliação, escritura, IMT nem o imposto do selo sobre a compra da casa
- O valor da Euribor que vem preenchido é só uma referência e tem de ser confirmado

## Tecnologias

HTML · CSS · JavaScript (sem bibliotecas nem frameworks) · gráfico em SVG

---
Feito por **Gonçalo Martins** — estudante de Engenharia Informática e Aplicações.
