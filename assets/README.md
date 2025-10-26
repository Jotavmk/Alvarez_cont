# Assets - Alvarez Contabilidade

Esta pasta contém todos os recursos visuais do site da Alvarez Contabilidade.

## Estrutura de Pastas

```
assets/
├── images/
│   ├── hero/           # Imagens para o carrossel da seção hero
│   ├── services/       # Imagens relacionadas aos serviços
│   └── about/           # Imagens para a seção sobre
├── icons/              # Ícones personalizados
└── README.md           # Este arquivo
```

## Imagens do Carrossel Hero

Coloque as imagens do carrossel na pasta `assets/images/hero/` com os seguintes nomes:

- `hero-1.jpg` - Contabilidade geral
- `hero-2.jpg` - Análise financeira  
- `hero-3.jpg` - Declarações fiscais
- `hero-4.jpg` - Gestão fiscal
- `hero-5.jpg` - Folha de pagamento

### Especificações das Imagens Hero:
- **Resolução:** 1920x1080px (Full HD) ou superior
- **Formato:** JPG ou PNG
- **Tamanho:** Máximo 2MB por imagem
- **Conteúdo:** Imagens profissionais relacionadas à contabilidade

## Imagens dos Serviços

Coloque as imagens dos serviços na pasta `assets/images/services/`:

- `contabilidade-geral.jpg`
- `declaracoes-fiscais.jpg`
- `consultoria-financeira.jpg`
- `folha-pagamento.jpg`
- `abertura-empresas.jpg`
- `compliance-fiscal.jpg`

## Imagens da Seção Sobre

Coloque as imagens da seção sobre na pasta `assets/images/about/`:

- `equipe.jpg` - Foto da equipe
- `escritorio.jpg` - Foto do escritório
- `reuniao.jpg` - Reunião de trabalho

## Ícones

Coloque ícones personalizados na pasta `assets/icons/` se necessário.

## Como Usar

Após adicionar as imagens, atualize o arquivo `index.html` para referenciar os caminhos locais em vez das URLs do Unsplash.

Exemplo:
```html
<!-- Antes (URL externa) -->
<div class="hero-slide active" style="background-image: url('https://images.unsplash.com/...')">

<!-- Depois (arquivo local) -->
<div class="hero-slide active" style="background-image: url('assets/images/hero/hero-1.jpg')">
```

