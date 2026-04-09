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
#### 4. **Evolução temporal**
- **Gráficos**: Linhas temporais
- **Análises**: 
  - Inscrições por dia
  - Inscrições por hora
  - Distribuição por dia da semana

#### 5. **Estatísticas de idade**
- **Gráficos**: Histograma de idades
- **Faixas**: Distribuição por faixas etárias (se disponível)

### **Funcionalidades Interativas Avançadas**
- **Filtragem por período**: Seletores de datas de início/fim
- **Filtragem por país**: Seleção com vários critérios
- **Filtragem por pacote**: Análise direcionada por oferta
- **Filtragem por pagamento**: Segmentação por método
- **Atualização em tempo real**: Botão para atualizar os dados
## Configuração Técnica

### Pré-requisitos
- Python 3.7+
- Ficheiro `Formulário_FINAL_OPTIMIZADO.xlsx` no mesmo diretório

### Bibliotecas utilizadas
- `streamlit`: Interface web interativa
- `plotly`: Gráficos interativos modernos
- `pandas`: Manipulação e análise de dados
- `folium`: Mapas geográficos interativos
- `streamlit-extras`: Componentes avançados da interface do utilizador

### Porta predefinida
- **URL local**: http://localhost:8501 (ou porta automática disponível)

## Estrutura dos ficheiros
```
├── dashboard_streamlit.py           # Aplicação principal
├── styles.css                      # Estilos CSS personalizados
├── limpeza_formulário.py         # Script de limpeza de dados
├── iniciar_dashboard.py             # Script de início automático
├── Formulário_FINAL_OTIMIZADO.xlsx  # Dados finais limpos
├── Formulário sem título (respostas).xlsx  # Dados originais
├── .streamlit/
│   └── config.toml                 # Configuração do tema e do servidor
└── README_Dashboard.md             # Documentação completa
```

## Design e Interface

### **Design Premium Aplicado**
- **Tema moderno**: Configuração de cores consistentes via `config.toml`
- **CSS personalizado**: Estilos avançados com gradientes e animações
- **Interface responsiva**: Adaptação automática para dispositivos móveis/computadores
- **Gráficos de métricas**: Design moderno com efeitos de hover
- **Barra lateral elegante**: Centro de controlo com design premium

### **Melhorias de UX/UI**
- **Animações fluidas**: Transições e efeitos visuais
- **Cores temáticas**: paleta harmoniosa e profissional
- **Tipografia moderna**: tipo de letra otimizado para a legibilidade
- **Layout otimizado**: disposição equilibrada dos elementos
- **Economia de espaço**: filtros agrupados numa linha

## Funcionalidades interativas

###  Gráficos interativos
- **Zoom** e **panorâmica** em todos os gráficos
- **Passar o cursor** para exibir os detalhes
- **Legendas** clicáveis para filtrar
