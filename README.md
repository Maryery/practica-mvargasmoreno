# **PRACTICA GIT, GITHUB, EJERCICIO 1**

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    
    git --hard HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

    git reflog  (porque muestra el commit que quieres recuperar).<br/>
    git reset --hard 7404d0 (recupera el commit borrado y queda todo como estaba).

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

    No, porque la rama styled ya contiene a master.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

    Si, porque modificamos el archivo, en las mismas líneas, en 2 ramas diferentes.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

    No, porque originó un fast forward.

- ¿Qué comando o comandos utilizaste en el paso 25?

    git log --graph (Ver el grafo)<br/>
    git --decorate (ver commits y ramas)<br/>
    git log --graph --decorate --pretty=online (toda la información más reducida)

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

    Si, porque las ramas forman una lista.

- ¿Qué comando o comandos utilizaste en el paso 27?

    git reset HEAD~1
    
- ¿Qué comando o comandos utilizaste en el paso 28?

    git  reset --hard

- ¿Qué comando o comando utilizaste en el paso 29?   

    git branch -D title

-  ¿Qué comando o comando utilizaste en el paso 30?

    git checkout -b title<br/>
    notepad git-nuestro.md<br/>
    git add git-nuestro.md<br/>
    git commit -m "Añado titulo"<br/>
    git checkout master<br/>
    git merge --no--ff title

-   ¿Qué comando o comando utilizaste en el paso 32?
    
    git reflog (buscamos número del primer commit)<br/>
    git checkout <primer-commit>

-   ¿Qué comando o comando utilizaste en el paso 33?

    git reflog (buscamos número del último commit)<br/>
    git checkout <último-commit>




