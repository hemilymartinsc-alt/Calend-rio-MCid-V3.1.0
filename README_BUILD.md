# Calendário Executivo MCid v3.1.0 — build oficial

Esta versão deve ser empacotada exclusivamente com o `pbiviz package` oficial.

## GitHub Actions (sem instalar nada no computador corporativo)
1. Crie ou use o repositório privado do visual.
2. Envie TODO o conteúdo desta pasta para a raiz do repositório, incluindo `.github/workflows/build-pbiviz.yml`.
3. Abra **Actions** > **Build PBIVIZ**.
4. Execute **Run workflow** se o build não iniciar automaticamente.
5. Ao terminar, baixe o artefato **Calendario-Executivo-MCid-v3.1.0**.
6. Dentro do ZIP do artefato estará o `.pbiviz` gerado oficialmente.

API do visual: 5.10.0.
Power BI Desktop alvo: 2.157.879.0 64-bit (agosto/2026).

## Base consolidada até a v3.0.2
- Layout preparado para 1920×1080 Full HD, com maior legibilidade e fontes ampliadas.
- Topo compactado para ampliar e subir o calendário mensal.
- Subtítulo alterado para `Visão mensal`.
- Texto explicativo das previsões ampliado para leitura.
- Removido `sem horários`.
- Removido `dados do modelo Power BI`.
- Removido o seletor/dropdown de mês e sua seta para baixo; setas laterais foram preservadas.
- Em meses anteriores ao atual, o título padrão do painel passa a ser `EVENTOS`.
- Clique simples em evento expande detalhes; duplo clique mantém a navegação por `Id Evento`.
- Detalhes expansíveis: Secretaria, Fonte/Subfonte, Programa e Quantidade de UH.
- Quando MCMV e Novo PAC estiverem marcados, Programa mostra ambos.


### Ajustes adicionais da v3.0.2
- Removido o texto `Dashboard Executivo` da barra institucional.
- O texto explicativo das previsões é mantido sempre em uma única linha.
- Removido o botão `Hoje` e toda a funcionalidade associada; as setas laterais permanecem.
- Cabeçalhos dos dias da semana ampliados e reforçados em negrito.
- Contagem no painel lateral simplificada para `X evento(s)`, sem `no contexto atual`, com maior destaque.
- Lista de eventos ampliada: data, tipologia, empreendimento, município/UF e detalhes expansíveis receberam fontes maiores e espaçamento adicional.


## Alterações da v3.0.3
- Na lista lateral de eventos, removidas as bolinhas coloridas que identificavam a categoria.
- Cada tipologia passa a ser identificada por uma barra vertical na cor da respectiva categoria.
- Fonte da lista lateral aumentada novamente para Full HD: data, tipologia, empreendimento, município/UF e detalhes expansíveis.
- Painel lateral ampliado em Full HD para acomodar a tipografia maior sem comprometer a leitura.


## Alteração da v3.0.4
- Toda a tipografia da lista lateral de eventos passou para azul institucional escuro `#08245A`, preservando as barras verticais coloridas por categoria e os demais comportamentos.


## V3.1.0
Integração oficial: **V3.0.4 = camada funcional** + **Opção 2 = camada visual**, incorporando também os refinamentos posteriores de legibilidade e títulos dinâmicos.
