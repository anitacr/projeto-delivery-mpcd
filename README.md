# Análise de Aplicativos de Delivery

## 📍 Contexto: Uma rede de restaurantes trabalha com dois aplicativos de entrega, **RapidoJa** e **ComeBem**, e precisa decidir com qual renovará o contrato[span_0](start_span)[span_0](end_span). Ambos prometem entregas em 35 minutos, e a rede oferece desconto ao cliente se a entrega ultrapassar 50 minutos[span_1](start_span)[span_1](end_span).

## 📊 Base de Dados
A análise utiliza o arquivo 'p05_delivery.csv', contendo 10.000 pedidos recentes com as variáveis[span_2](start_span)[span_2](end_span):
- **app**: Aplicativo utilizado (RapidoJa ou ComeBem).
- **distancia_km**: Distância entre o restaurante e o cliente.
- **tempo_min**: Tempo em minutos entre o pedido e a entrega.

## 🛠️ Tecnologia Utilizadas
- **Python**: Pandas, SciPy, Matplotlib e Seaborn.
- **Google Colab**: Para a execução das análises estatísticas e teste de hipótese ( $\alpha=0.05$ ) [span_3](start_span)[span_3](end_span).
