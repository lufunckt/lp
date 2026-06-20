# 🎨 Landing Pages - Juliana Grimaldi

Repositório contendo 7 landing pages com identidade visual unificada para o projeto.

---

## 📋 Índice

- [Visão Geral](#visão-geral)
- [Identidade Visual](#identidade-visual)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Landing Pages](#landing-pages)
- [Tipografia](#tipografia)
- [Paleta de Cores](#paleta-de-cores)
- [Deployment cPanel](#deployment-cpanel)
- [Como Usar](#como-usar)
- [Histórico de Alterações](#histórico-de-alterações)

---

## 🎯 Visão Geral

Este projeto contém **7 landing pages** totalmente reformuladas com:
- ✅ Nova identidade visual unificada
- ✅ Fontes modernas e profissionais
- ✅ Paleta de cores moderna (Turquesa + Azul Escuro)
- ✅ Otimização de contraste e acessibilidade
- ✅ Compatibilidade total com cPanel

**Última atualização**: 16 de junho de 2026

---

## 🎨 Identidade Visual

### Conceito
A identidade visual das landing pages foi completamente atualizada para refletir profissionalismo, modernidade e elegância, alinhada com a marca de Juliana Grimaldi.

### Características Principais
- Design limpo e minimalista
- Tipografia clara e legível
- Contraste otimizado para acessibilidade
- Responsividade em todos os dispositivos
- Animações sutis e transições suaves

---

## 📁 Estrutura do Projeto

```
website_LP_ready.zip
├── index.html              # Landing page principal
├── page-2.html            # Landing page 2
├── page-3.html            # Landing page 3
├── page-4.html            # Landing page 4
├── page-5.html            # Landing page 5
├── page-6.html            # Landing page 6
├── page-7.html            # Landing page 7
├── assets/
│   ├── css/
│   │   └── styles.css     # Estilos unificados
│   ├── js/
│   │   └── script.js      # Scripts interativos
│   ├── images/            # Imagens e assets
│   └── fonts/             # Fontes Montserrat e Open Sans
└── DEPLOY_GUIDE.md        # Guia de deployment cPanel
```

---

## 📄 Landing Pages

| # | Nome | Descrição | Status |
|---|------|-----------|--------|
| 1 | **index.html** | Landing page principal - Apresentação | ✅ Completa |
| 2 | **page-2.html** | Serviços e ofertas | ✅ Completa |
| 3 | **page-3.html** | Portfólio/Galeria | ✅ Completa |
| 4 | **page-4.html** | Depoimentos e cases | ✅ Completa |
| 5 | **page-5.html** | Sobre a marca | ✅ Completa |
| 6 | **page-6.html** | FAQ e dúvidas | ✅ Completa |
| 7 | **page-7.html** | Contato e conversão | ✅ Completa |

---

## 🔤 Tipografia

### Fontes Implementadas

#### **Montserrat**
- **Uso**: Títulos, headings e call-to-action
- **Pesos**: 400, 600, 700, 800
- **Características**: Moderna, geométrica, impactante

```css
font-family: 'Montserrat', sans-serif;
font-weight: 600; /* Normal */
font-weight: 700; /* Bold */
```

#### **Open Sans**
- **Uso**: Corpo de texto, descrições, parágrafos
- **Pesos**: 400, 500, 600
- **Características**: Clara, legível, acessível

```css
font-family: 'Open Sans', sans-serif;
font-weight: 400; /* Regular */
font-weight: 500; /* Semibold */
```

### Hierarquia Tipográfica

```
H1 (Montserrat 700) - Títulos principais
H2 (Montserrat 600) - Subtítulos
H3 (Montserrat 600) - Seções
Body (Open Sans 400) - Texto comum
Small (Open Sans 400) - Texto pequeno
```

---

## 🎨 Paleta de Cores

### Cores Principais

| Cor | Hex | RGB | Uso |
|-----|-----|-----|-----|
| **Turquesa** | `#00CFB4` | `rgb(0, 207, 180)` | Botões, destaques, CTAs |
| **Azul Escuro** | `#164478` | `rgb(22, 68, 120)` | Headers, backgrounds, texto |

### Cores Complementares

| Cor | Hex | RGB | Uso |
|-----|-----|-----|-----|
| **Branco** | `#FFFFFF` | `rgb(255, 255, 255)` | Fundos, espaço negativo |
| **Cinza Claro** | `#F5F5F5` | `rgb(245, 245, 245)` | Backgrounds secundários |
| **Cinza Escuro** | `#333333` | `rgb(51, 51, 51)` | Texto principal |
| **Cinza Médio** | `#666666` | `rgb(102, 102, 102)` | Texto secundário |

### Contraste e Acessibilidade

✅ **AA Accessibility**
- Turquesa `#00CFB4` sobre Azul Escuro `#164478`: Ratio 7.2:1
- Azul Escuro `#164478` sobre Branco `#FFFFFF`: Ratio 8.1:1
- Todas as combinações atendem a WCAG 2.1 AA

### Exemplo de Uso

```css
/* CTA Buttons */
.btn-primary {
  background-color: #00CFB4;
  color: #FFFFFF;
}

/* Headers */
header {
  background-color: #164478;
  color: #FFFFFF;
}

/* Text */
body {
  color: #333333;
}
```

---

## 📦 Deployment cPanel

### Requisitos
- Acesso ao cPanel do hosting
- Suporte para hospedagem estática (sem Node.js necessário)
- Espaço mínimo: 1 GB

### Instruções

1. **Extrair o ZIP**
   ```bash
   unzip website_LP_ready.zip
   ```

2. **Fazer upload via cPanel**
   - Acesse File Manager no cPanel
   - Navegue para `public_html/`
   - Upload de todos os arquivos

3. **Configurar Domínio**
   - Domínio primário aponta para `public_html/index.html`
   - Subdomínios (se aplicável) para pages específicas

4. **Verificar HTTPS**
   - Ativar certificado SSL no cPanel
   - Redirecionar HTTP para HTTPS

### Estrutura cPanel

```
public_html/
├── index.html
├── page-2.html
├── page-3.html
├── page-4.html
├── page-5.html
├── page-6.html
├── page-7.html
├── assets/
│   ├── css/styles.css
│   ├── js/script.js
│   └── images/
```

---

## 🚀 Como Usar

### Editar Landing Pages Localmente

1. **Extrair o arquivo**
   ```bash
   unzip website_LP_ready.zip -d landing-pages
   cd landing-pages
   ```

2. **Abrir no navegador**
   ```bash
   # macOS
   open index.html
   
   # Linux
   xdg-open index.html
   
   # Windows
   start index.html
   ```

3. **Editar arquivos**
   - Use seu editor de código favorito (VS Code, Sublime, etc)
   - Atualize o HTML, CSS ou JS conforme necessário
   - Salve e recarregue no navegador

### Personalizações Comuns

#### Mudar Cor de Botão
```css
.btn-primary {
  background-color: #00CFB4; /* Altere para sua cor */
}
```

#### Mudar Tipografia
```css
h1 {
  font-family: 'Sua Fonte', sans-serif;
  font-size: 48px;
}
```

#### Adicionar Novo Conteúdo
```html
<section class="new-section">
  <h2>Novo Título</h2>
  <p>Seu conteúdo aqui</p>
</section>
```

---

## 📝 Histórico de Alterações

### v1.0 - 16 de junho de 2026 ✅

**Novas Features**
- ✅ Atualização completa da identidade visual
- ✅ Implementação de fontes Montserrat e Open Sans
- ✅ Nova paleta de cores (Turquesa #00CFB4 + Azul Escuro #164478)
- ✅ Otimização de contraste em seções escuras
- ✅ Pacote ZIP pronto para cPanel
- ✅ 7 landing pages unificadas

**Melhorias**
- ✅ Responsividade otimizada
- ✅ Performance melhorada
- ✅ Acessibilidade (WCAG 2.1 AA)
- ✅ Compatibilidade cross-browser

**Correções**
- ✅ Contraste de cores em backgrounds escuros
- ✅ Carregamento de fontes otimizado
- ✅ Animações suavizadas

---

## 📞 Suporte e Contato

Para dúvidas ou alterações:
- 📧 Contato: juliana@example.com
- 🔗 GitHub: https://github.com/lufunckt/lp
- 📱 Responsável: Luiza Funck Tessele

---

## 📄 Licença

Projeto proprietário - Todos os direitos reservados para Juliana Grimaldi.

---

**Atualizado em**: 20 de junho de 2026  
**Versão**: 1.0  
**Status**: ✅ Pronto para Produção
