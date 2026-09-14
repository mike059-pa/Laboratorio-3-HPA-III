# Laboratorio # 3

**Fecha:** 13/09/2026

## Contenido del Repositorio

Este repositorio contiene los programas desarrollados para la materia **HPA III** utilizando el lenguaje de programación **C#** y el entorno de desarrollo **Visual Studio**.

Durante este laboratorio se desarrollaron tres aplicaciones con el objetivo de poner en práctica diferentes conceptos de programación orientada a objetos, estructuras de control, colecciones, validaciones de datos y el desarrollo de interfaces gráficas utilizando Windows Forms.

Los proyectos desarrollados son:

1. **Caso de Estudio DataGridView**
2. **Caso de Estudio Juego de Craps**
3. **Aplicación MDI en C#**

---

## Tecnologías Utilizadas

* **Lenguaje:** C#
* **Framework:** .NET / Windows Forms
* **IDE:** Visual Studio
* **Control de interfaz:** DataGridView, DateTimePicker, ErrorProvider, ToolStrip
* **Colecciones:** ArrayList
* **Programación orientada a objetos:** Clases, métodos y enumeraciones
* **Control de versiones:** Git / GitHub

---

## Capturas de Pantalla y Problemas

### 1. Caso de Estudio: DataGridView

Este programa utiliza una interfaz desarrollada con Windows Forms para trabajar con información organizada mediante el control `DataGridView`.
Entre los elementos utilizados se encuentran `DataGridView`, `ErrorProvider`, `ToolStrip` y `DateTimePicker`. También se implementaron conceptos como clases, métodos estáticos, `ArrayList` y validaciones de datos.
El `DataGridView` permite mostrar y editar información organizada en filas y columnas, facilitando la interacción del usuario con los datos.

#### Interfaz Principal

<img width="847" height="517" alt="image" src="https://github.com/user-attachments/assets/774898b4-11f8-4a22-88d9-df3d81ae95f8" />

#### Funcionamiento
<img width="847" height="512" alt="image" src="https://github.com/user-attachments/assets/017b4942-6b89-4480-b31d-31cd9768536b" />

<img width="860" height="522" alt="image" src="https://github.com/user-attachments/assets/bbcd9a12-98b0-49df-b113-ebff78c68a6f" />


---

### 2. Caso de Estudio: Juego de Craps

El segundo programa consiste en una implementación del **Juego de Craps**, utilizando C# para representar la lógica del lanzamiento de dados y las diferentes condiciones del juego.

En este caso de estudio se aplicaron diferentes conceptos de programación, entre ellos:

* Tipos de datos `enum`.
* Clase `Random`.
* Estructuras selectivas `switch` e `if/else`.
* Estructura repetitiva `while`.
* Conversión explícita o casting.

El programa utiliza una clase `Craps` y un método para realizar las tiradas de los dados. También se utiliza una enumeración para representar los valores relacionados con los dados.

#### Interfaz / Ejecución del Juego
<img width="1457" height="412" alt="image" src="https://github.com/user-attachments/assets/52e5bb25-073c-4389-b78b-89acc6ab83d3" />

---

### 3. Aplicación MDI en C#

El tercer programa consiste en una aplicación desarrollada utilizando el modelo **MDI (Multiple Document Interface)** de Windows Forms.

La aplicación permite trabajar con una ventana principal que funciona como formulario contenedor y desde ella abrir diferentes formularios secundarios.

La implementación permite organizar las diferentes funcionalidades del programa dentro de una misma ventana principal, utilizando formularios hijos.

#### Ventana Principal MDI

<img width="747" height="476" alt="image" src="https://github.com/user-attachments/assets/1d914e13-8876-4b8d-8577-c552c250418d" />


#### Formularios Secundarios

<img width="572" height="416" alt="image" src="https://github.com/user-attachments/assets/a3eeef70-759c-4424-ac99-8e6ec6b3dcbf" />


#### Funcionamiento del MDI

<img width="750" height="490" alt="image" src="https://github.com/user-attachments/assets/2a12c058-87b5-432d-a30e-d81974dea3ba" />


## Estructura de Carpetas o Directorios

La estructura del repositorio se organiza de la siguiente manera:

```text
HPA-III-Laboratorio/
│
├── DataGridView/
│   ├── Form1.cs
│   ├── Persona.cs
│   ├── Utilidades.cs
│   └── ...
│
├── Craps/
│   ├── Craps.cs
│   ├── Program.cs
│   └── ...
│
├── MDI/
│   ├── Form1.cs
│   ├── Form2.cs
│   └── ...
│

│
└── README.md
```

>

---

## Instrucciones de Ejecución / Uso

### 1. Clonar el repositorio

Clonar el repositorio desde GitHub utilizando:

```bash
git clone [URL_DEL_REPOSITORIO]
```

### 2. Abrir el proyecto

Ingresar a la carpeta del repositorio y abrir el archivo de solución `.sln` utilizando **Visual Studio**.

### 3. Restaurar dependencias

Verificar que el proyecto tenga instalado el framework de .NET correspondiente y permitir que Visual Studio restaure las dependencias necesarias.

### 4. Ejecutar la aplicación

Seleccionar el proyecto que se desea ejecutar y presionar:

```text
F5
```

o utilizar el botón **Iniciar** de Visual Studio.

### 5. Utilizar los programas

Una vez iniciada la aplicación, se puede ejecutar cada uno de los ejercicios desarrollados:

* **DataGridView:** permite gestionar y visualizar los datos mediante una interfaz gráfica.
* **Juego de Craps:** permite ejecutar la lógica del juego mediante las tiradas de dados.
* **MDI:** permite abrir y administrar diferentes formularios dentro de una ventana principal.

---

## Autor y Contexto

**Nombre:** Michael Hunt
**Materia:** HPA III
**Institución:** Universidad Tecnológica de Panamá (UTP)
**Fecha de Realización:** [13/09/2026]

---

## Conclusión

Este laboratorio permitió poner en práctica diferentes conceptos de programación en **C#**, incluyendo el desarrollo de interfaces gráficas con Windows Forms, manejo de colecciones, validación de datos, estructuras de control, enumeraciones, generación de valores aleatorios y utilización de formularios MDI.

Los ejercicios realizados permitieron reforzar los conocimientos necesarios para desarrollar aplicaciones de escritorio de manera organizada, aplicando diferentes componentes y estructuras propias del lenguaje C#.
