# 💡 Lâmpada Liga/Desliga com JavaScript e Bootstrap

## 📌 Sobre o Projeto
Este projeto demonstra como manipular o **DOM** com **JavaScript**, permitindo que o usuário **ligue e desligue** uma lâmpada ao clicar em botões. A interface foi construída utilizando **Bootstrap 5** para um design responsivo e moderno.

🔗 **Demonstração Online:** _(adicione aqui o link do GitHub Pages se for publicar)_

## 🎯 Funcionalidades
✅ Alternar entre lâmpada ligada e desligada ao clicar nos botões.
✅ Layout responsivo e estilizado com **Bootstrap 5**.
✅ JavaScript separado em um **arquivo externo** (`script.js`).

## 🛠️ Tecnologias Utilizadas
- **HTML5** - Estrutura do projeto
- **CSS3** - Estilização com Bootstrap
- **JavaScript (ES6+)** - Manipulação do DOM
- **Bootstrap 5** - Interface responsiva e moderna

## 📂 Estrutura de Arquivos
```
📂 Seu Projeto
│── 📁 css/ (estilos opcionais)
│── 📁 js/
│   ├── script.js (lógica do JavaScript)
│── 📁 img/
│   ├── lampada-ligada.png
│   ├── lampada-apagada.png
│── index.html (arquivo principal da página)
```

## 🚀 Como Usar
1. **Baixe o repositório** ou clone.
2. Abra o arquivo `index.html` em qualquer navegador.
3. Clique nos botões **Ligar** e **Desligar** para interagir com a lâmpada!

## 💻 Código Fonte
### **HTML (`index.html`):**
```html
<div class="container text-center mt-5">
    <h1>Controle da Lâmpada</h1>
    <img id="lampada" class="img-fluid" src="img/lampada-apagada.png" alt="Lâmpada Apagada" style="max-width: 200px;">
    <div class="mt-4">
        <button class="btn btn-success me-2" onclick="ligarLampada()">Ligar</button>
        <button class="btn btn-danger" onclick="desligarLampada()">Desligar</button>
    </div>
</div>
```

### **JavaScript (`script.js`):**
```js
function ligarLampada() {
    document.getElementById("lampada").src = "img/lampada-ligada.png";
}

function desligarLampada() {
    document.getElementById("lampada").src = "img/lampada-apagada.png";
}
```

## 📢 Melhorias Futuras
✅ Adicionar um evento de clique na própria lâmpada para ligar/desligar.  
✅ Criar um efeito de **transição suave** ao trocar a imagem.  
✅ Implementar um sistema onde a lâmpada "queima" após muitas interações.  

## 📜 Licença
Este projeto está sob a licença **MIT**. Sinta-se livre para usá-lo e modificá-lo como quiser! 🚀

📌 **Criado por:** Guilherme Salomão Shorane | 💻 _Contato: vitrineata@vitrineata.com.br

