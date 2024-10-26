# DJ Music Library Organizer

A collection of Jupyter notebooks designed to organize and manage a DJ's music library. This project allows for easy tracking, updating, and organization of songs stored in an Excel file (`Biblioteca.xlsx`) located at `E:\Musica-E\Organizacion`. The primary music folder for scanning new tracks is `E:\Musica-E\DJ Project`, both of which can be modified within the code.

> **Note**: The code is partially written in Spanish, and this project has inspired the idea of creating a desktop application with a user interface as a fun side project.

### Notebooks

- **`load_msc.ipynb`**  
  Generates a complete Excel file listing all songs in the specified music directory.
  
- **`add_new_song.ipynb`**  
  Adds new songs to the Excel list if they aren't already included.
  
- **`bpm_clave.ipynb`**  
  Calculates and updates the BPM (beats per minute) and Key for each song in the list.
  
- **`delete_not_existing.ipynb`**  
  Deletes entries in the Excel sheet for songs that are no longer present in the designated directory.
  
- **`verifica_existencia.ipynb`**  
  Checks for songs listed in the Excel file that may have been removed from the directory.

### Excel File Headers

The Excel file (`Biblioteca.xlsx`) has the following headers for organizing music data:

- `Nombre` | `Titulo` | `Artista` | `Genero` | `Ubicacion` | `BPM` | `Clave / Key` | `Valoracion` | `Comentario` | `Pais` | `Year` | `Etiquetas`
