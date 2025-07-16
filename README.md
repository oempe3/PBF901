# Análise de Consumo e Nível do Tanque PBF901

Este projeto apresenta uma aplicação web moderna para análise de dados de consumo e nível do tanque PBF901, com design inspirado no Flutter.

## Características

- **Design Moderno**: Interface limpa e profissional com estilo Flutter-like
- **Responsivo**: Compatível com dispositivos desktop e mobile
- **Gráficos Interativos**: Visualizações dinâmicas usando Plotly.js
- **Análise Completa**: Médias diárias, semanais e quinzenais
- **Dados em Tempo Real**: Carregamento automático de dados CSV

## Arquivos

- `analise_tanque.html` - Aplicação principal
- `Verificação consumo e nível do tanque PBF901_CSV.csv` - Dados do tanque
- `README.md` - Este arquivo

## Como Usar

1. Abra o arquivo `analise_tanque.html` em um navegador web
2. Os dados serão carregados automaticamente do arquivo CSV
3. Visualize os gráficos de consumo diário e nível do tanque
4. Analise as estatísticas apresentadas

## Tecnologias Utilizadas

- HTML5
- CSS3 (com variáveis CSS e design responsivo)
- JavaScript (ES6+)
- Plotly.js para gráficos
- PapaParse para processamento CSV
- Google Fonts (Poppins)

## Melhorias Implementadas

- Paleta de cores moderna (#42A5F5 e #66BB6A)
- Tipografia Poppins para melhor legibilidade
- Cards com sombras suaves
- Layout responsivo
- Micro-interações visuais
- Estrutura de código limpa e organizada

## Suporte

Para executar localmente, você pode usar qualquer servidor HTTP simples:

```bash
# Python
python -m http.server 8080

# Node.js
npx http-server

# PHP
php -S localhost:8080
```

Depois acesse `http://localhost:8080/analise_tanque.html`

