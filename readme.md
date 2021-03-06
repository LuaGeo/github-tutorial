# **Projeto "github-tutorial"**   
# (aprendendo a subir projetos)

## 1. Criando um repositorio

![criando um repositorio](images/novo-repositorio.png)

  - Escolha um nome simples e direto, com letras minusculas e palavras separadas por hifens.

  - Escolha também uma descrição para o seu projeto. O restante pode deixar como esta por enquanto.

![nome e descricao](images/nome-e-descricao.png)

## 2. Crie uma pasta para o seu projeto com nome idêntico ao do repositorio:

```bash : mkdir nome-da-pasta```

## 3. Abra o VSCode dentro da pasta recém criada:

```bash : code .```

## 4. No VSCode crie e salve o seu codigo

## 5. Volte ao terminal (ou utilise o terminal do proprio VSCode se tiver sincronizado) e inicie o git:

```bash : git init #(inicia git com pasta aberta)
git status #(mostra o status do git (arquivos em vermelho indicando que ainda não foram comitados nem subidos))
git add . #(subir todos os arquivos em vermelho listados)
git commit -m "Primeiro commit" #(cria o primeiro commit chamado "Primeiro commit")
git log #(lista os commits existentes)
```

## 6. Volte para a pagina do github e copie o git remote do seu repositorio. Cole no terminal:

```bash : git remote add origin https://github.com/LuaGeo/nome-da-pasta.git```

![remote link](images/git-remote.png)

## 7. Suba o seu commit para o seu repositorio:

```bash : git push # em seguida cole o que o terminal pede pra colar, isso sempre acontece para o primeiro commit de cada repositorio, nos seguintes apenas git push basta)```

## 8. Confira na sua pagina do github se tudo deu certo e os arquivos foram adicionados.

# **FIM**

