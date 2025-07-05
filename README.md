# Prueba Técnica LAFISE

Este proyecto es una API REST desarrollada en .NET 8 que implementa operaciones bancarias básicas.

## Requisitos Previos

- [Visual Studio 2022] 
- [.NET 8 SDK]
- [SQLite]

## Configuración del Proyecto en Visual Studio

### 1. Abrir el Proyecto

1. Abrir Visual Studio 2022
2. Seleccionar "Abrir un proyecto o solución"
3. Navegar hasta la carpeta del proyecto y seleccionar `PruebaTecniacLAFISE.sln`

### 2. Restaurar Paquetes NuGet

1. Click derecho en la solución en el Explorador de Soluciones
2. Seleccionar "Restaurar paquetes NuGet"

### 3. Crear y Actualizar la Base de Datos

1. Abrir la "Consola del Administrador de Paquetes" 
   - Menú: Herramientas > Administrador de Paquetes NuGet > Consola del Administrador de Paquetes
2. Asegurarse que el "Proyecto predeterminado" sea `Data`
3. Ejecutar el comando:
   ```powershell
   Update-Database
   ```

## Ejecutar el Proyecto

1. En Visual Studio, asegurarse que `PruebaTecniacLAFISE` esté establecido como proyecto de inicio
   - Click derecho en el proyecto `PruebaTecniacLAFISE` > "Establecer como proyecto de inicio"

2. Presionar F5 o el botón "Iniciar depuración" (botón verde de play)

3. Visual Studio abrirá automáticamente el navegador con Swagger en:
   - https://localhost:7223/swagger
   - http://localhost:5143/swagger

## Ejecutar Pruebas

1. Abrir el Explorador de pruebas
   - Menú: Prueba > Explorador de pruebas

2. En el Explorador de pruebas, click en "Ejecutar todas las pruebas" (o presionar Ctrl+R, A)
