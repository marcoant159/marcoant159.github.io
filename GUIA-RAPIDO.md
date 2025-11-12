# 🚀 Guia Rápido - Como Adicionar Sua Imagem

## Método 1: Via GitHub.com (Mais Fácil!)

### Passo 1: Acesse seu repositório
Vá para: https://github.com/marcoant159/marcoant159.github.io

### Passo 2: Entre na pasta images
- Clique na pasta `images`

### Passo 3: Faça upload da sua imagem
- Clique no botão **"Add file"** no canto superior direito
- Selecione **"Upload files"**
- Arraste sua imagem ou clique em "choose your files"
- **IMPORTANTE**: Renomeie sua imagem para `profile.jpg` antes de fazer upload
  - Se sua imagem for PNG, pode deixar como `profile.png` e depois atualizar o `index.html`

### Passo 4: Faça commit
- Na parte inferior da página, escreva uma mensagem como "Adiciona foto de perfil"
- Clique em **"Commit changes"**

### Passo 5: Aguarde
- Aguarde 2-5 minutos
- Acesse: https://marcoant159.github.io
- Sua foto já estará lá! 🎉

---

## Método 2: Via Git (Para quem sabe usar linha de comando)

```bash
# 1. Clone o repositório (se ainda não tiver)
git clone https://github.com/marcoant159/marcoant159.github.io.git
cd marcoant159.github.io

# 2. Copie sua imagem para a pasta images
# Renomeie para profile.jpg
cp /caminho/para/sua/imagem.jpg images/profile.jpg

# 3. Adicione e faça commit
git add images/profile.jpg
git commit -m "Adiciona foto de perfil"
git push

# 4. Aguarde alguns minutos e acesse: https://marcoant159.github.io
```

---

## 📝 Personalizando seus links

Depois de adicionar sua foto, edite o arquivo `index.html`:

1. No GitHub, clique em `index.html`
2. Clique no ícone de lápis ✏️ (Edit this file)
3. Procure e altere:
   - **Linha 17**: Seu nome
   - **Linha 18**: Sua bio
   - **Linha 22**: Link do seu Instagram (mude `seu_usuario`)
   - **Linha 31**: Seu WhatsApp (mude o número)
   - **Linha 36**: Seu email
4. Clique em "Commit changes"

---

## 💡 Dicas

- **Tamanho da imagem**: Use uma foto quadrada (ex: 500x500 pixels)
- **Formato**: JPG, PNG ou WebP funcionam
- **Tamanho do arquivo**: Mantenha abaixo de 500KB para carregar rápido
- **Atualização**: Após fazer commit, aguarde 2-5 minutos para ver as mudanças

---

## ❓ Problemas?

### Minha imagem não aparece
- Verifique se o nome do arquivo é exatamente `profile.jpg`
- Se sua imagem for PNG, atualize a linha 13 do `index.html` para `profile.png`
- Aguarde alguns minutos após fazer commit
- Limpe o cache do navegador (Ctrl+F5 ou Cmd+Shift+R)

### Não consigo fazer upload
- Certifique-se de estar logado no GitHub
- Verifique se tem permissão no repositório
- Tente usar um navegador diferente

---

## 🎨 Quer mudar as cores?

Edite o arquivo `style.css`:
- **Linha 11**: Muda o gradiente de fundo
- **Linha 49**: Muda a cor da borda da foto
- **Linhas 88-92**: Muda a cor dos botões

Divirta-se personalizando! 🚀
