# Práctica de Fundamentos de Programación
## Desarrollo de Software y Negocios Digitales

 ![Tests](https://github.com/JorgeTSW/fundamentos-programacion-practica-1/actions/workflows/test.yml/badge.svg)

¡Bienvenido a la práctica de programación! En este repositorio aprenderás a programar en JavaScript mientras aplicas conceptos de álgebra.

## Objetivos

- Aprender a usar Git y GitHub
- Dominar los fundamentos de JavaScript
- Prepararte para programar operaciones matriciales
- Desarrollar habilidades de resolución de problemas

## Requisitos previos

- Tener una cuenta en [GitHub](https://github.com)
- Instalar [Node.js](https://nodejs.org) (versión 14 o superior)
- Instalar [Git](https://git-scm.com)
- Un editor de código como [VS Code](https://code.visualstudio.com)

## ¿Cómo empezar?

### Paso 1: Fork del repositorio
1. Haz clic en el botón **Fork** en la esquina superior derecha
2. Esto creará una copia del repositorio en tu cuenta

### Paso 2: Clonar tu fork
```bash
git clone https://github.com/TU-USUARIO/fundamentos-programacion.git
cd fundamentos-programacion
```

### Paso 3: Instalar dependencias
```bash
npm install
```

### Paso 4: Completar los ejercicios
Abre el archivo `ejercicios.js` y completa cada función siguiendo las instrucciones.

### Paso 5: Probar tu código localmente
```bash
npm test
```

### Paso 6: Subir tus cambios
```bash
git add ejercicios.js
git commit -m "Ejercicio #XX completado"
git push origin main
```

### Paso 7: Ver tu calificación
- Ve a la pestaña **Actions** en tu repositorio de GitHub
- Verás el resultado de los tests automáticos
- ¡Tu calificación aparecerá allí­!

## Estructura del repositorio

```
fundamentos-programacion/
├── .github/
│   └── workflows/
│       └── test.yml           # Configuración de GitHub Actions
├── ejercicios.js              # Aquí­ escribirás tu código
├── ejercicios.test.js         # Tests (NO modificar)
├── package.json               # Configuración del proyecto
└── README.md                  # Este archivo
```

## Reglas importantes

1. **SOLO** debes modificar el archivo `ejercicios.js`
2. **NO** modifiques los archivos de test
3. **NO** modifiques la configuración de GitHub Actions
4. Todos los ejercicios deben pasar los tests para obtener la máxima calificación

## Consejos

- Lee cuidadamente las instrucciones de cada ejercicio
- Prueba tu código localmente antes de hacer push
- Si un test falla, lee el mensaje de error - te dice qué está mal
- Puedes hacer múltiples commits, no hay penalización
- Busca ayuda en la documentación de [JavaScript MDN](https://developer.mozilla.org/es/docs/Web/JavaScript)

## Sistema de calificación

- Cada ejercicio vale puntos especí­ficos
- La calificación final es automática
- Aparecerá en los resultados de GitHub Actions
- Badge de estado: ![Tests](https://github.com/JorgeTSW/fundamentos-programacion-practica-1/actions/workflows/test.yml/badge.svg)

## Próximos pasos

Una vez domines estos fundamentos, trabajaremos en:
- Operaciones con matrices
- Calculadora matricial
- Aplicaciones prácticas (editores de imágenes, encriptación)

---

**¡Éxito en tu práctica!**
---

## 📘 Autor del trabajo
**Nombre:** Noé Euán Herrera  
**Materia:** Fundamentos de Programación  
**Grupo:** Desarrollo de Software y Negocios Digitales  
**Profesor:** Jorge TSW  
**Descripción:**  
He completado todos los ejercicios del archivo `ejercicios.js` siguiendo las instrucciones de la práctica.  
Todos los tests pasan correctamente en Jest, y los resultados pueden verse en la pestaña **Actions** de GitHub.
