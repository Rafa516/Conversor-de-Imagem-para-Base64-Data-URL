# 🖼️ Conversor de Imagem para Data URL (Base64)

![Screenshot](/assets/screenshot.png)

Uma ferramenta web para conversão de imagens em Data URLs com codificação Base64, ideal para incorporação direta em HTML e CSS.

## 📚 Introdução

### O que é um Data URL?
Um **Data URL** é um esquema URI que permite incorporar arquivos diretamente no código, usando o formato:
```
data:[<mediatype>][;base64],<data>
```

Para imagens, o formato geralmente é:
```html
data:image/<formato>;base64,<dados codificados em base64>
```

**Exemplo de uso:**
```html
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAA...">
```

**Vantagens:**
- Elimina requisições HTTP adicionais
- Útil para pequenas imagens
- Bom para ambientes offline
- Pode ser usado em CSS e HTML

**Desvantagens:**
- Aumenta o tamanho do arquivo HTML/CSS
- Não é armazenado em cache pelo navegador
- Recomendado apenas para imagens pequenas (<2KB)

## ✨ Funcionalidades

- **Conversão instantânea** para Data URL
- **Visualização da imagem** antes da conversão
- **Botão de cópia** com ícone intuitivo
- **Interface responsiva** que se adapta a dispositivos móveis
- **Feedback visual** durante a interação
- **Suporte múltiplo** para formatos de imagem

## 🛠️ Tecnologias

- **Bootstrap 5** - Framework CSS para design responsivo
- **FileReader API** - Leitura de arquivos no cliente
- **JavaScript Moderno** - Lógica de conversão
- **HTML5** - Estrutura semântica
- **CSS3** - Estilização avançada

## 🚀 Como Usar

1. **Selecionar imagem**
   - Clique no botão "Procurar"
   - Escolha um arquivo de imagem

2. **Visualizar conversão**
   - A imagem será exibida automaticamente
   - O código Base64 aparecerá no campo abaixo

3. **Copiar código**
   - Clique no botão <i class="bi bi-clipboard"></i>
   - O Data URL será copiado para a área de transferência

## 🌐 Demonstração Online



