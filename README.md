# Painel de análise do formulário

**Funcionalidades interativas avançadas**
-  **Filtragem por período**: Seletores de datas de início/fim
-  **Filtragem por país**: Seleção com vários critérios
-  **Filtragem por pacote**: Análise direcionada por oferta
-  **Filtragem por pagamento**: Segmentação por método
-  **Atualização em tempo real**: Botão de atualização de dados
-  **Layout otimizado**: Filtros numa única linha para poupar espaço O Streamlit fornece uma interface web interativa para analisar os dados do formulário limpo.

## Início rápido

### Método 1: Script de início
```bash
python lancer_dashboard.py
```

### Método 2: Comando direto
```bash
streamlit run dashboard_streamlit.py
```

## Funcionalidades do Painel

### Métricas-chave exibidas
#### 1. **Distribuição das ofertas selecionadas**
-  **Gráficos**: Gráfico circular e histograma
-  **Detalhes**: Número de inscritos por pacote (Premium, Essencial, Standard, Vantagem)
-  **Análise**: Preços médios, mínimos e máximos por pacote

#### 2. **Distribuição geográfica**
-  **Gráficos**: Histograma e mapa interativo
-  **Dados**: Número de participantes por país
-  **Visualização**: Mapa com marcadores proporcionais

#### 3. **Formas de pagamento**
-  **Gráficos**: Barras e anéis
-  **Análise**: Distribuição das opções (Mobile Money, cartão de crédito, etc.)
