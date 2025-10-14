## Comandos para integrar o git no seu GitHub
```bash
git config user.name "Seu Nome de Usuario" #Faz o git entender o nome da pessoa que está alterando os arquivos
git config user.email "Seu email de Usuario" #Faz o git entender o gmail da pessoa que está alterando os arquivos
git remote add origin https://o_link_do_seu_repositorio_criado_no_github #Junta seu repositorio do github com o Git
git branch -M main #Cria uma raiz chamada "main"
git push -u origin main #Joga todas essas alterações para seu github
```

## Comandos para puxar e salvar seu repositorio do GitHub para o VisualCode
```bash
git clone https://link_do_seu_repositorio_no_github #Clona o seu repositorio para o visual code
git branch develop #Cria uma raiz de desenvolvimento
git switch develop #Troca da raiz principal para a de desenvolvimento
git add seu_arquivo.algo #Adiciona o arquivo à área de espera (prepara pra commit)
git add . #Faz a mesma coisa que o de cima, mas com todos os arquivos e pastas
git commit -m "Exemplo de texto para salvar as mudanças" #Cria um commit com a mensagem, salvando as mudanças preparadas
git push origin develop #Envia os commits da branch develop pro pré repositório remoto
git switch main #Necessario trocar para (main)
git merge develop #Mescla as mudanças da branch develop na branch atual (main)
git push origin main #Envia as mudanças da branch main pro repositório remoto
```