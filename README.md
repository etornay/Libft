<h1>1. Consideraciones técnicas:</h1>

• Declarar variables globales está prohibido.

• Si necesitas separar una función compleja en varias, asegúrate de utilizar la palabra
static para ello. De esta forma, las funciones se quedarán en el archivo apropiado.

• Pon todos tus archivos en la raíz de tu repositorio.

• Se prohibe entregar archivos no utilizados.

• Todos los archivos .c deben compilarse con las flags -Wall -Werror -Wextra.

• Debes utilizar el comando ar para generar la librería. El uso de libtool queda
prohibido.

• Tu libft.a tiene que ser creado en la raíz del repositorio.



<h1>2. Funciones de libc:</h1>

Para empezar, deberás rehacer algunas funciones de la libc. Tus funciones tendrán los
mismos prototipos e implementarán los mismos comportamientos que las funciones originales. Deberán ser tal y como las describe el man. La única diferencia será la nomenclatura.
Empezarán con el prefijo “ft_”. Por ejemplo, strlen se convertirá en ft_strlen.

Deberás escribir tus propias funciones implementando las siguientes funciones originales. No requieren de funciones autorizadas:

**• isalpha**

**• isdigit**

**• isalnum**

**• isascii**

**• isprint**

**• strlen**

**• memset**

**• bzero**

**• memcpy**

**• memmove**

**• strlcpy**

**• strlcat**

**• toupper**

**• tolower**

**• strchr**

**• strrchr**

**• strncmp**

**• memchr**

**• memcmp**

**• strnstr**

**• atoi**

Para implementar estas otras dos funciones, tendrás que utilizar malloc():

**• calloc**

**• strdup**
