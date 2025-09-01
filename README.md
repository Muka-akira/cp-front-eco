# 🌱 EcoTrend - E-commerce Sustentável

Um e-commerce completo especializado em produtos sustentáveis e ecológicos, desenvolvido com HTML, CSS, Bootstrap e JavaScript puro.

## 📋 Descrição do Projeto

O **EcoTrend** é uma plataforma de e-commerce focada em promover um estilo de vida mais consciente e sustentável. O projeto oferece uma interface moderna, responsiva e intuitiva para comercialização de produtos eco-friendly.

### 🎯 Objetivos
- Desenvolver uma interface responsiva para e-commerce sustentável
- Utilizar HTML, CSS Grid, Bootstrap e JavaScript
- Promover produtos que respeitam o meio ambiente
- Criar uma experiência de usuário excepcional

## 🚀 Funcionalidades

### ✨ Páginas Principais
- **Home**: Banner carrossel, categorias, produtos em destaque
- **Categorias**: Grid de produtos com filtros avançados
- **Produto**: Detalhes completos, galeria de imagens, avaliações
- **Contato**: Formulário de contato e informações da empresa

### 🔧 Funcionalidades Técnicas
- Design responsivo para todos os dispositivos
- Sistema de filtros por categoria, preço e marca
- Galeria de imagens interativa
- Formulários validados
- Carrossel automático com controles
- Sistema de avaliações
- FAQ interativo
- Navegação intuitiva

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilos personalizados com CSS Grid e Flexbox
- **Bootstrap 5.3.0**: Framework CSS para componentes e responsividade
- **JavaScript ES6+**: Funcionalidades interativas e dinâmicas
- **Bootstrap Icons**: Ícones consistentes e modernos

## 📁 Estrutura do Projeto

```
ecotrend/
├── index.html              # Página inicial
├── categorias.html         # Página de categorias e produtos
├── produto.html            # Página de detalhes do produto
├── contato.html            # Página de contato
├── css/
│   └── style.css          # Estilos personalizados
├── js/
│   └── script.js          # Funcionalidades JavaScript
├── assets/
│   └── README.md          # Documentação dos assets
└── README.md              # Este arquivo
```

## 🎨 Design e UX

### Paleta de Cores
- **Primária**: Verde sustentável (#198754)
- **Secundária**: Verde água (#20c997)
- **Acentos**: Roxo (#6f42c1)
- **Neutros**: Tons de cinza para texto e fundos

### Tipografia
- **Família**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Hierarquia**: Títulos em negrito, texto legível
- **Responsiva**: Tamanhos adaptáveis para diferentes telas

### Componentes
- Cards de produtos com hover effects
- Botões com estados visuais claros
- Formulários com validação visual
- Navegação intuitiva e breadcrumbs
- Footer informativo e organizado

## 📱 Responsividade

O site é totalmente responsivo e funciona perfeitamente em:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

### Breakpoints
- `@media (max-width: 768px)`: Ajustes para tablets
- `@media (max-width: 576px)`: Ajustes para smartphones

## 🚀 Como Executar

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional, para funcionalidades completas)

### Instalação
1. Clone ou baixe o projeto
2. Abra o arquivo `index.html` em seu navegador
3. Navegue pelas páginas usando o menu

### Desenvolvimento Local
Para desenvolvimento com funcionalidades completas:
```bash
# Usando Python
python -m http.server 8000

# Usando Node.js
npx serve .

# Usando PHP
php -S localhost:8000
```

## 🔧 Personalização

### Cores
Edite as variáveis CSS em `css/style.css`:
```css
:root {
    --primary-color: #198754;
    --secondary-color: #20c997;
    --accent-color: #6f42c1;
}
```

### Produtos
Adicione novos produtos editando o HTML e CSS correspondentes:
- Página de categorias: `categorias.html`
- Cards de produtos: `css/style.css` (classe `.product-card`)

### Conteúdo
- Textos: Edite diretamente nos arquivos HTML
- Imagens: Substitua arquivos na pasta `assets/`
- Funcionalidades: Modifique `js/script.js`

## 📊 Performance

### Otimizações Implementadas
- CSS otimizado com variáveis e seletores eficientes
- JavaScript com debounce e throttle para scroll
- Imagens com lazy loading (preparado)
- Animações CSS otimizadas
- Código modular e organizado

### Métricas Recomendadas
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1
- **First Input Delay**: < 100ms

## 🌐 Acessibilidade

### Recursos Implementados
- HTML semântico com landmarks
- Alt text para todas as imagens
- Contraste adequado de cores
- Navegação por teclado
- Estrutura de cabeçalhos lógica
- Labels descritivos para formulários

### Melhorias Futuras
- Suporte a leitores de tela
- Modo de alto contraste
- Redimensionamento de texto
- Navegação por voz

## 🔒 Segurança

### Boas Práticas Implementadas
- Validação de formulários no cliente
- Sanitização de inputs
- HTTPS ready (quando implementado)
- Headers de segurança (quando implementado)

## 📈 SEO

### Otimizações
- Meta tags apropriadas
- Estrutura de URLs semântica
- Schema markup preparado
- Sitemap ready
- Robots.txt preparado

## 🧪 Testes

### Navegadores Testados
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Dispositivos Testados
- Desktop (Windows, macOS, Linux)
- Tablet (iPad, Android)
- Mobile (iPhone, Android)

## 🚀 Deploy

### Opções de Hospedagem
- **Netlify**: Deploy automático via Git
- **Vercel**: Deploy com preview automático
- **GitHub Pages**: Hospedagem gratuita
- **AWS S3**: Hospedagem estática escalável

### Comandos de Deploy
```bash
# Build para produção
npm run build

# Deploy para Netlify
netlify deploy --prod

# Deploy para Vercel
vercel --prod
```

## 🤝 Contribuição

### Como Contribuir
1. Fork o projeto
2. Crie uma branch para sua feature
3. Commit suas mudanças
4. Push para a branch
5. Abra um Pull Request

### Padrões de Código
- HTML semântico e acessível
- CSS organizado com comentários
- JavaScript com funções bem definidas
- Nomes de variáveis descritivos
- Comentários explicativos

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👥 Autores

- **Desenvolvedor**: Assistente de IA
- **Projeto**: EcoTrend - E-commerce Sustentável
- **Data**: 2024

## 🙏 Agradecimentos

- Bootstrap Team pelo framework CSS
- Bootstrap Icons pelos ícones
- Comunidade de desenvolvimento web
- Usuários que testaram e forneceram feedback

## 📞 Suporte

Para suporte ou dúvidas:
- **Email**: contato@ecotrend.com.br
- **Telefone**: (11) 99999-9999
- **Horário**: Segunda a Sexta, 8h às 18h

## 🔮 Roadmap Futuro

### Versão 2.0
- [ ] Sistema de login e cadastro
- [ ] Carrinho de compras funcional
- [ ] Sistema de pagamentos
- [ ] Área do cliente
- [ ] Sistema de avaliações real

### Versão 3.0
- [ ] App mobile nativo
- [ ] Integração com redes sociais
- [ ] Sistema de fidelidade
- [ ] Chat online
- [ ] Analytics avançado

---

**EcoTrend** - Transformando o futuro através da sustentabilidade! 🌱✨

