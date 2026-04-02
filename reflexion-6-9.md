1. 
- git reset: elimina los commits posteriores al seleccionado, borrando sus datos en el nivel que queramos (--soft, --mixed, --hard)
- git revert: crea un commit nuevo que aplica el estado invero al commit anterior seleccionado, dejando intacto el historial.

2. 
- Si ya has hecho un git push y no quieres molestar a colaboradores que podrían haber usado ya tu código nuevo.
- Eliminar un bug en el código sin borrar progreso posterior. Es decir, eliminas código de un commit que generaba errores.

3. git revert no mueve el tiempor hacia antrás, sino que añade un commit al futuro del historial. Es importante con proyectos con
varios colaboradores porque evitas divergencias, no rompes commits en los que ya se basan otros, y ves explicitamente qué cambios se revierten
y cuándo, manteniendo comunicación y flujo.
