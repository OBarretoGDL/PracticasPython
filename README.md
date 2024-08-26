# Pokédex

## Descripción

Pokémon Info Collector es un proyecto que utiliza la [PokeAPI](https://pokeapi.co/) para obtener información sobre Pokémon, guardarla en archivos JSON y mostrar los detalles junto con una imagen del Pokémon en un entorno Jupyter Notebook. El proyecto proporciona una interfaz interactiva para consultar datos y visualizar imágenes de Pokémon.

## Requisitos

Para ejecutar este proyecto, necesitas tener instalado Python 3 y las siguientes librerías:

- `requests`: Para realizar solicitudes HTTP a la API de Pokémon.
- `ipywidgets`: Para crear y mostrar widgets en un entorno Jupyter Notebook.
- `IPython`: Para la visualización de imágenes y datos en Jupyter Notebook.

## Uso
Obtener Información del Pokémon:

Abre un entorno Jupyter Notebook.
Importa las librerías necesarias y define las funciones proporcionadas en el proyecto.
Llama a la función mostrar_pokemon con el nombre o número del Pokémon que deseas consultar.

## Notas
Asegúrate de ejecutar el código en un entorno compatible con ipywidgets, como Jupyter Notebook.
Los archivos JSON se guardarán en la carpeta pokedex. Puedes modificar la ruta en el código si deseas guardar los archivos en otra ubicación.
Contribuciones

Puedes instalar las librerías necesarias con el siguiente comando:

```bash
pip install requests ipywidgets

