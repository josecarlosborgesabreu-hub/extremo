# Extremo — Site & Ementa Digital

Site oficial da Extremo Padaria Pastelaria Pizzaria e Hamburgueria.
Rua da Carvalheira, 658 · Arnoso Santa Eulália · V.N. Famalicão

---

## Ficheiros do site

| Ficheiro | O que é | URL |
|---|---|---|
| `index.html` | Ementa digital | extremo-ementa.netlify.app |
| `links.html` | Link-in-bio (Instagram) | extremo-ementa.netlify.app/links.html |
| `encomendas.html` | Encomendas takeaway | extremo-ementa.netlify.app/encomendas.html |
| `mesa.html` | Pedido da mesa (QR) | extremo-ementa.netlify.app/mesa.html?mesa=N |
| `sobre.html` | Site institucional | extremo-ementa.netlify.app/sobre.html |
| `qr-mesas.html` | Gerador de QR codes | uso interno |

---

## Como actualizar a ementa (preços ou produtos)

Não é necessário saber programação. Siga estes passos:

### 1. Aceder ao GitHub
- Ir a [github.com](https://github.com) e fazer login
- Abrir o repositório **extremo-ementa**

### 2. Abrir o ficheiro para editar
- Clicar no ficheiro que quer alterar (ex: `index.html`)
- Clicar no ícone do lápis ✏️ no canto superior direito

### 3. Fazer a alteração
- Usar **Ctrl+F** (ou Cmd+F no Mac) para encontrar o texto que quer alterar
- Por exemplo, para mudar o preço da Pizza Média de 14€ para 15€, procurar "14,00€" e alterar

### 4. Guardar
- Descer até ao fundo da página
- Clicar em **"Commit changes"**
- O site actualiza automaticamente em menos de 1 minuto

---

## Como adicionar uma pizza nova

Encontrar no `index.html` a secção das pizzas e copiar este bloco, alterando o nome e descrição:

```html
<div class="pizza-item">
  <div class="pizza-row">
    <div>
      <div class="pizza-name">NOME DA PIZZA</div>
      <div class="pizza-desc">Ingrediente 1, ingrediente 2, ingrediente 3</div>
    </div>
    <div class="pizza-prices">
      <span><span class="lbl">P</span>10€</span>
      <span><span class="lbl">M</span>14€</span>
      <span><span class="lbl">F</span>18€</span>
    </div>
  </div>
</div>
```

---

## Como actualizar o número de uma mesa nos QR codes

- Abrir o ficheiro `qr-mesas.html` no browser
- Alterar o número inicial e final das mesas
- Clicar em "Gerar QR Codes" e depois "Imprimir"

---

## Contactos técnicos

Para alterações mais complexas ao site, contactar o responsável pelo projecto.

- WhatsApp Extremo: 912 146 436
- Instagram: @extremopadariapastelaria
