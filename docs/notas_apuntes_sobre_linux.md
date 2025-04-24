En este espacion escribe cosas importantes en el cual me servira para
comprender mejor lo que es el ambiente de linux
esta version se llama: garuda que esta basada en arch

// por lo visto garuda es solo una rama de varias versiones de linux en la cual no se nada toca indagar a profundidad para entender
conceptos escenciales //

vim file.txt

lunes: logre aprender gran parte de la primera parte de vimtutor en el cual explica a detalle el uso del modo 'normal'

adjunto el glosario

1. The cursor is moved using either the arrow keys or the hjkl keys.
   h (left) j (down) k (up) l (right)

2. To start Vim from the shell prompt type: vim FILENAME <ENTER>

3. To exit Vim type: <ESC> :q! <ENTER> to trash all changes.
   OR type: <ESC> :wq <ENTER> to save the changes.

4. To delete the character at the cursor type: x

5. To insert or append text type:
   i type inserted text <ESC> insert before the cursor
   A type appended text <ESC> append after the line

NOTE: Pressing <ESC> will place you in Normal mode or will cancel
an unwanted and partially completed command.

hay que mejorar la comprension en ingles...
actualizacion del di 04/23

se aprendio a borrar de distintas manera no creo llegar a implementar todo de una es mas herramientas que uno
se acostumbra conforme la necesidad lo amerite sigo pollito

Lesson 1.2 SUMMARY

1. To delete from the cursor up to the next word type: dw
2. To delete from the cursor up to the end of the word type: de
3. To delete from the cursor to the end of a line type: d$
4. To delete a whole line type: dd

5. To repeat a motion prepend it with a number: 2w
6. The format for a change command is:
   operator [number] motion
   where:
   operator - is what to do, such as d for delete
   [number] - is an optional count to repeat the motion
   motion - moves over the text to operate on, such as w (word),
   e (end of word), $ (end of the line), etc.

7. To move to the start of the line use a zero: 0

8. To undo previous actions, type: u (lowercase u)
   To undo all the changes on a line, type: U (capital U)
   To undo the undos, type: CTRL-R

---

en la leccion 1,3,1 se usa el P para acomodar lo borrado en la siguiente linea

en caso de error de github al sincronizar escribir en terminal lo siguiente
sssh-add -l  
ssh-add ~/.ssh/dlenard_gh
