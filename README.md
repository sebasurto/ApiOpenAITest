# ApiOpenAITest
Este código implementa una interfaz gráfica de usuario que utiliza la API de OpenAI para generar respuestas a partir de una entrada de texto. La aplicación solicita al usuario que ingrese un tema de su interés, y luego utiliza el modelo de lenguaje GPT-3.5 de OpenAI para generar una respuesta relacionada con ese tema.

La aplicación usa la biblioteca tkinter para crear la GUI y la biblioteca openai para acceder a la API de OpenAI. También utiliza la biblioteca os para acceder a las variables de entorno, de manera que la API key de OpenAI se pueda almacenar en una variable de entorno segura y no se muestre en el código.

La función obtener_respuesta(prompt) es la que se encarga de hacer la llamada a la API de OpenAI y obtener la respuesta generada por el modelo. La función enviar_mensaje() se encarga de obtener el texto ingresado por el usuario, agregar una solicitud de información y llamar a obtener_respuesta(prompt) para generar la respuesta. La función mostrar_respuesta(respuesta) es la encargada de mostrar la respuesta generada en el cuadro de salida de texto .
