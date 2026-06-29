# Resumenes-plan-lector-codex

1. Tener codex instalado en el sistema y una cuenta de ChatGPT de 20$ o + con acceso a Codex ya iniciada.
2. Ir a ChatGPT **Deep Research** y decirle tus inquietudes del libro (complejidades que el libro pueda tener... por ejemplo, el libro de Pedro Páramo es muy complejo de leer por cambios temporales, etc). Decirle también a Chat que **NO QUIERES PERDER TIEMPO** y necesitas una "guía de lectura eficiente para entender fácilmente las dificultades; anticiparte y superarlas".

[EJEMPLO DE PROMPT](https://github.com/santiagollll/Resumenes-plan-lector-codex/blob/main/prompt-deep-research)

![https://chatgpt.com/deep-research](https://raw.githubusercontent.com/santiagollll/Resumenes-plan-lector-codex/refs/heads/main/drsrch.webp)

3. Esperar a que ChatGPT haga el informe del Deep Research. Cuando tengamos el informe de DEEP RESEARCH. Tenemos que descargar este informe como "MARKDOWN". La app de chatgpt nos debiese dejar descargarlo como Markdown... en el caso que **no sea posible** descargarlo como markdown, entonces **NO** vamos a descargarlo como .PDF ni tampoco como "Word / docx / doc". En cambio, vamos a copiar TODO EL CONTENIDO del informe poco a poco en un documento "**.txt**". Esto lo podemos hacer con el programa "Bloc de notas" en Windows.

Obviamente, vamos a preocuparnos de que todo vaya quedando copiado y pegado de forma correcta, sin errores en el formato (lo vamos corrijiendo si hace falta).

[EJEMPLO DE INFORME](https://github.com/santiagollll/Resumenes-plan-lector-codex/blob/main/InformeDeepResearch.txt)

4. Ahora, ya con el informe (que habla sobre dificultades del libro y spoilea cosas) tenemos que hacer el resumen del libro. Para esto, es necesario descargar un resumen que ya exista de otro libro + el otro libro, a modo de EJEMPLO para Codex.

En este caso, yo usé la página web de "gradesaver.com" que tiene muy buenos resúmenes por capítulos + análisis. Usé el resumen de Cien años de Soledad.

https://www.gradesaver.com/cien-a%C3%B1os-de-soledad/guia-de-estudio/summary-cap%C3%ADtulos-1-2

**IMPORTANTE**: Cuando ya tengas el resumen del libro, tienes que crear un archivo ".txt" en el cuál almacenes todo el resumen completo (ósea, basicamente ir copiando y pegando desde la página web de "gradesaver.com" todo el resumen en un documento .txt. Esto se puede hacer con el programa de "Bloc de notas" en windows. Esto, capítulo a capítulo, hasta tener el resumen completo en ese archivo .txt

5. Ahora descargamos el libro correspondiente al resumen de ejemplo. (Como yo usé el resumen de ejemplo de Cien años de soledad, entonces descargo el libro de cien años de soledad).

¿Dónde y cómo lo descargo?: NO LO DESCARGAS COMO PDF. En cambio, lo descargas como "**.epub**". Cuando ya tengas el .epub de Cien años de soledad, tienes que usar un programa para "Convertir .epub a .txt". Esto es importante, porque Codex no puede leer pdf ni epub ni nada. Solo lee .txt, y convertir .epub a .txt garantiza una precisión absoluta.

¿Qué programa para convertir?: https://calibre-ebook.com/es/download ; por cierto, quizás también sirva un conversor "online"... no lo sé.

¿Donde lo descargo como ".epub"?: En google buscas "(nombre del libro) .epub" y lo descargas desde google... o usas una pagina diferente para descargarlo... O buscas en google "Telegram, biblioteca secreta", y aprendes a usar la biblioteca secreta de Telegram.

6. Ahora, descargamos el libro del cuál necesitamos generar un resumen, también en .txt. Esto lo hacemos igual que como lo hicimos anteriormente en el paso "5"

¿Qué pasa si el libro que nosotros tenemos está únicamente dispoible en .docx, o únicamente disponible en .PDF y NO está en .epub?: En ese caso, tenemos que convertirlo a .txt. Lo que yo recomiendo al 100%, es usar **MISTRAL OCR**.

Mistral OCR lo podemos usar a través de, [una página web](https://santiagollll.github.io) o a través de una [extensión de Chrome](https://github.com/santiagollll/Chrome-Mistral-OCR).



7. Ahora, tenemos lo siguiente:
-Codex configurado (cuenta $20 o +)
-Informe de Deep Research en .txt o .md (markdown)
-Libro de ejemplo en .txt
-Resumen de ejemplo en .txt
-El libro que necesitamos que nos haga un resumen en .txt

Con esto, tenemos que organizar un "espacio de trabajo" para luego producir el resumen. ENTONCES!. Vamos a crear una carpeta nueva en nuestro computador. Esa carpeta le vamos a poner el nombre de "resumen-plan-lector".

8. Ok. Ya cuando tengamos la carpeta y estemos dentro de esa carpeta vacía, vamos a crear más carpetas DENTRO DE ESTA. (ósea, estamos dentro de "resumen-plan-lector", y ahora vamos a crear MÁS CARPETAS dentro de "resumen-plan-lector".)

La primera carpeta, tiene que tener el nombre del libro que vamos a usar a modo de EJEMPLO para darle ese resumen a modo de ejemplo. En mi caso, "cien-años-de-soledad". (es preferible, remplazar la "ñ" por una "n", por si acaso).

La segunda carpeta, tiene que tener el nombre del libro que necesitamos que la IA nos genere un resumen. En este caso, "hijo-de-ladron".

9. Ya tenemos las carpetas creadas. Entonces, en la carpeta del libro que vamos a usar a modo de ejemplo (en este caso "cien-años-de-soledad), vamos a poner dentro:
  - El libro ejemplar en formato .txt
  - El resumen ejemplar del libro ejemplar en formato .txt

**IMPORTANTE**: Los dos archivos DEBEN tener los nombres bien configurados. Para el "libro ejemplar", yo usé el nombre "Cien-años-de-soledad.txt" y para el resumen, usé el nombre "Resumen-cien-años-de-soledad.txt"

10. Ahora, vamos a ir a la carpeta del libro el cual queremos tener el resumen (hijo de ladrón en mi caso).

Dentro de la carpeta, ponemos: 1. El libro de hijo de ladron en formato .txt, con el nombre de archivo BIEN PUESTO (hijo-de-ladron.txt). 2. Ponemos el documento que ChatGPT nos dió en el "DEEP RESEARCH" (el informe que hicimos anteriormente). Este informe, le vamos a dar el nombre de "ResumenGeneral.txt"... NO TE PREOCUPES, no va a ser ese el resumen final. Pero es necesario que pongas el archivo con ese nombre en esa carpeta.

11. Ahora, vamos a abrir CODEX dentro de la carpeta "resumen-plan-lector". Lo importante, es que Codex quede abierto dentro de esta carpeta (que a su vez, contiene las otras dos carpetas) para que pueda tener acceso a todos los archivos.

*"¿Yo siempre uso el comando "codex" para abrir codex... esta bien así?"*. NO, no esta bien eso. Lo que tienes que hacer es:
1. Dentro de la TERMINAL (o cmd), abrir la carpeta "resumen-plan-lector".
2. Cuando tu terminal esté ubicada en ese directorio, entonces, ahí si abres Codex con el comando "codex".

¿NO SABES A LO QUE ME REFIERO?: Entonces pidele ayuda a ChatGPT para configurar esto y seguir el paso 11 de esta guía.

12. Ok. Cuando tengamos Codex abierto, ahora vamos a pegarle un **PROMPT** que le indique exactamente como realizar el resumen del libro que queremos. Este prompt indica la ubicacion de los archivos y da muchas instrucciones útiles a codex para que haga un buen resumen.

¿Qué prompt?. Bueno, el prompt que yo usé en su momento es [ESTE](https://github.com/santiagollll/Resumenes-plan-lector-codex/edit/main/Prompt.txt)


**Tienes que editar ese prompt que usé yo en su momento, cambiando SOLAMENTE los datos relevantes / necesarios para ajustar el libro de ejemplo; el libro que tu necesitas y algunos parámetros. Intenta mantener el resto de cosas como están, pues ese prompt funciona bien**.

13. **ANTES** de darle el prompt a codex, tienes que configurar el modelo de codex para que use **POR LO MENOS** "gpt-5.5" en modo "xhigh".

Esto es super importante. Cuando ya tengas Codex con "gpt-5.5" en "xhigh", le das el prompt, y envías el mensaje. Luego, gpt va a comenzar a trabajar

14. Va a ocurrir, que Codex te va a decir "ya termine los capitulos "a-b"". En ese momento, tu tienes que decirle simplemente: "CONTINÚA". Para que Codex siga con el resto de capítulos.
   
**IMPORTANTE**: Yo (al menos) el primer mensaje de todos usé el modo "xhigh", y luego, en el resto de mensajes usé el modo "high", y aún así funcionó super bien. Te recomiendo que hagas lo mismo (primer mensaje a codex en modo "xhigh" y el resto en "high").

Esto, con el objetivo de que la "couta" de Codex se gaste mas lentamente, y no te quedes en "PANA" antes de tiempo.

15. Listo, ya debieras tener todo listo.

16. Adjunto, todos los archivos que usé yo, por si quieres usar los mismos archivos de ejemplo míos (para evitar tener que descargar el resumen desde cero en gradesaver.com) y así ahorrar tiempo. Y también para mostrar el resultado final.

[Cien años de soledad (LIBRO)](https://github.com/santiagollll/Resumenes-plan-lector-codex/blob/main/Cien%20anos%20de%20soledad%20-%20Gabriel%20Garcia%20Marquez.txt)

[Resumen cien años de soledad](https://github.com/santiagollll/Resumenes-plan-lector-codex/blob/main/Resumen%20100%20an%CC%83os%20de%20soledad.md)

[Informe Deep research hijo de ladrón](https://github.com/santiagollll/Resumenes-plan-lector-codex/blob/main/InformeDeepResearch.txt)

[Libro hijo de ladrón](https://github.com/santiagollll/Resumenes-plan-lector-codex/blob/main/Hijo%20de%20ladron%20-%20Manuel%20Rojas.txt)

[Ejemplo del resumen que me hizo codex de hijo de ladrón](https://github.com/santiagollll/Resumenes-plan-lector-codex/blob/main/ResumenCodexFinal.txt)

[PROMPT PARA GENERAR EL RESUMEN FINAL CON CODEX](https://github.com/santiagollll/Resumenes-plan-lector-codex/edit/main/Prompt.txt)
