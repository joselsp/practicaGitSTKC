> **- ¿Qué comando utilizaste en el paso 11? ¿Por qué?**
> git reset --hard HEAD~1

Con reset movemos el puntero head y la rama actual donde indiquemos. En este caso, a un commit previo y además deshacemos los cambios en local con --hard.

**- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
git reflog
git reset --hard 205c327

Igual que el caso anterior, pero en este caso utilizamos git reflog para localizar el commit al que queremos situarnos; el commit que hicimos en el paso 10 con los cambios de la rama styled.

**- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
No porque styled ya contiene todos los cambios que contiene el commit de master ya que es su commit padre.

**- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
Si hubo conflicto porque los ficheros de ambas ramas tenían las mismas líneas modificadas.

**- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
No hubo conflicto porque master no tenía ningún cambio respecto a la rama absorbida (styled).

**- ¿Qué comando o comandos utilizaste en el paso 25?**
git log --graph --decorate

**- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
Si podría haber sido fast forward ya que al realizar el merge no se hubieran perdido cambios de otros commits.

**- ¿Qué comando o comandos utilizaste en el paso 27?**
git reset HEAD~1

**- ¿Qué comando o comandos utilizaste en el paso 28?**
git checkout -- git-nuestro.md

**- ¿Qué comando o comandos utilizaste en el paso 29?**
git branch -D title

**- ¿Qué comando o comandos utilizaste en el paso 30?**
git reflog
git reset --hard 18a32dd

**- ¿Qué comando o comandos usaste en el paso 32?**
git reflog
git reset --hard 6968e48

**- ¿Qué comando o comandos usaste en el punto 33?**
git reflog
git reset --hard 18a32dd
