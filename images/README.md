# Como adicionar sua imagem de perfil

## Passos para adicionar sua foto:

1. **Renomeie sua imagem** para `profile.jpg` (ou `profile.png`)
   
2. **Coloque a imagem nesta pasta** (`images/`)

3. Se sua imagem tiver outro formato (PNG, por exemplo), **atualize o arquivo `index.html`**:
   - Abra o arquivo `index.html`
   - Procure pela linha: `<img src="images/profile.jpg" alt="Marco Antonio">`
   - Mude para: `<img src="images/profile.png" alt="Marco Antonio">`

## Formatos suportados:
- `.jpg` ou `.jpeg`
- `.png`
- `.gif`
- `.webp`

## Dicas:
- Use uma imagem quadrada para melhor resultado
- Tamanho recomendado: pelo menos 400x400 pixels
- Mantenha o arquivo leve (menos de 1MB) para carregar mais rápido

## Como fazer upload no GitHub:

### Opção 1: Via navegador (GitHub.com)
1. Acesse seu repositório no GitHub
2. Clique na pasta `images`
3. Clique em "Add file" > "Upload files"
4. Arraste sua imagem ou clique para selecionar
5. Faça commit das mudanças

### Opção 2: Via Git (linha de comando)
```bash
# Clone o repositório (se ainda não tiver clonado)
git clone https://github.com/marcoant159/marcoant159.github.io.git
cd marcoant159.github.io

# Copie sua imagem para a pasta images
cp /caminho/para/sua/imagem.jpg images/profile.jpg

# Adicione e faça commit
git add images/profile.jpg
git commit -m "Adiciona imagem de perfil"
git push
```

Aguarde alguns minutos e sua página estará disponível em: **https://marcoant159.github.io**
