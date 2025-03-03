# **Currículum Vitae - Marcelo Amores**  

📌 Proyecto desarrollado con [Quarto](https://quarto.org/) para la creación y publicación de mi currículum vitae en formato web y PDF.  

## 📁 **Estructura del Proyecto**  
- 📂 `_book/` → Carpeta de salida con los archivos generados (no se versiona en GitHub).  
- 📄 `index.qmd` → Archivo principal del CV en formato Quarto.  
- 📄 `_quarto.yml` → Configuración del proyecto (metadatos, formato de salida, etc.).  
- 📄 `README.md` → Este archivo con información sobre el proyecto.  

## ⚙️ **Requisitos y Configuración**  
Para visualizar o compilar el CV, se requiere:  
- [Quarto](https://quarto.org/docs/get-started/) instalado.  
- R y RStudio (opcional si se usa con R).  
- Paquetes adicionales si se personaliza con RMarkdown o LaTeX.  

## 🛠 **Generación y Publicación**  
### **Compilar el CV**  
Para generar el currículum en los formatos deseados, ejecutar en la terminal:  
```sh
quarto render
```

## 📜 **Licencia**  
© 
```{r}
year <- format(Sys.Date(), "%Y")
```
Marcelo Amores. Todos los derechos reservados.  



