# Pix do Milhão - Site Modularizado

## 📋 Descrição
Este projeto é uma versão modularizada e aprimorada do site "Pix do Milhão", transformando um código HTML monolítico em uma estrutura de componentes separados e reutilizáveis.

## 🏗️ Estrutura do Projeto

```
pix-do-milhao-site/
├── index.html                 # Página principal
├── css/
│   ├── styles.css            # Estilos base e utilitários
│   ├── components.css        # Estilos específicos dos componentes
│   └── responsive.css        # Estilos responsivos
├── js/
│   ├── components-loader.js  # Carregador de componentes
│   ├── countdown.js          # Funcionalidade do contador
│   ├── promotion.js          # Lógica da seção de promoção
│   └── main.js              # JavaScript principal
├── components/
│   ├── header.html          # Cabeçalho
│   ├── banner.html          # Banner promocional
│   ├── info.html            # Informações dos sorteios
│   ├── countdown.html       # Contador regressivo
│   ├── bonus.html           # Informações de bônus
│   ├── promotion.html       # Seção de promoção
│   ├── lottery-wheel.html   # Giro da sorte
│   ├── winners.html         # Títulos premiados
│   ├── logos.html           # Logos de parceiros
│   ├── extra-info.html      # Informações extras
│   └── footer.html          # Rodapé
└── assets/
    └── images/              # Diretório para imagens
```

## ✨ Melhorias Implementadas

### 🔧 Modularização
- **Componentes Separados**: Cada seção foi dividida em componentes HTML independentes
- **CSS Organizado**: Estilos divididos em arquivos específicos (base, componentes, responsivo)
- **JavaScript Modular**: Funcionalidades organizadas em módulos específicos

### 🎨 Design Aprimorado
- **Gradientes Modernos**: Aplicados em backgrounds e botões
- **Animações Suaves**: Transições e efeitos hover aprimorados
- **Responsividade**: Design totalmente responsivo para mobile, tablet e desktop
- **Acessibilidade**: Melhor estrutura semântica e suporte a leitores de tela

### ⚡ Performance
- **Carregamento Assíncrono**: Componentes carregados de forma assíncrona
- **Animações de Loading**: Feedback visual durante o carregamento
- **Otimização de Imagens**: Suporte a diferentes formatos e resoluções

### 🔄 Interatividade
- **Contador Dinâmico**: Timer regressivo com animações
- **Seleção de Produtos**: Interface interativa para escolha de quantidades
- **Filtros Dinâmicos**: Sistema de filtros para títulos premiados
- **Notificações**: Sistema de feedback para ações do usuário

## 🚀 Como Executar

### Opção 1: Servidor HTTP Local
```bash
cd pix-do-milhao-site
python3 -m http.server 8000
```
Acesse: `http://localhost:8000`

### Opção 2: Servidor Node.js
```bash
cd pix-do-milhao-site
npx http-server -p 8000
```

### Opção 3: Live Server (VS Code)
Use a extensão Live Server do VS Code para desenvolvimento.

## 📱 Responsividade

O site é totalmente responsivo com breakpoints para:
- **Desktop**: > 768px
- **Tablet**: 768px - 480px
- **Mobile**: < 480px
- **Mobile Pequeno**: < 320px

## 🎯 Funcionalidades

### ⏰ Contador Regressivo
- Timer dinâmico até a data do sorteio
- Animações de pulso nos números
- Mensagem de finalização quando o tempo expira

### 🛒 Sistema de Compras
- Seleção de quantidades (5, 10, 20, 50)
- Cálculo automático de preços
- Botões de incremento/decremento
- Feedback visual nas interações

### 🎰 Giro da Sorte
- Informações sobre recompensas
- Cards interativos com hover effects

### 🏆 Títulos Premiados
- Sistema de filtros por valor
- Lista de contemplações
- Carregamento dinâmico de mais resultados

## 🔧 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com Flexbox e Grid
- **JavaScript ES6+**: Funcionalidades interativas
- **Fetch API**: Carregamento de componentes
- **Intersection Observer**: Animações de scroll
- **CSS Animations**: Transições e efeitos visuais

## 🎨 Paleta de Cores

- **Primária**: #FFD400 (Amarelo dourado)
- **Secundária**: #23d34a (Verde sucesso)
- **Background**: #121212 (Preto escuro)
- **Cards**: #1e1e1e, #2a2a2a (Cinzas escuros)
- **Texto**: #ffffff, #ddd (Brancos)

## 📈 Performance

- **Carregamento Modular**: Componentes carregados sob demanda
- **Animações Otimizadas**: CSS transforms para melhor performance
- **Lazy Loading**: Imagens carregadas conforme necessário
- **Minificação**: Código otimizado para produção

## 🔒 Segurança

- **CORS Configurado**: Suporte a diferentes origens
- **Sanitização**: Prevenção de XSS em conteúdo dinâmico
- **Validação**: Verificação de dados de entrada

## 📞 Suporte

Para dúvidas ou problemas, consulte a documentação ou entre em contato com a equipe de desenvolvimento.

---

© 2025 Pix do Milhão - Todos os direitos reservados.

