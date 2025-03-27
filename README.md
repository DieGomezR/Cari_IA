# 🕒 Calculadora de Horas por Concepto

Una pequeña aplicación web que permite calcular la distribución de horas trabajadas por concepto (horas ordinarias, extras y nocturnas) según el horario de entrada y salida del empleado.

## ✨ Características

- Interfaz moderna y responsiva con **Tailwind CSS**.
- Gráfico interactivo con **Chart.js**.
- Alertas elegantes con **SweetAlert2**.
- Indicador de carga mientras se consulta la API.
- Comunicación asincrónica con API externa mediante `fetch` y `async/await`.

## 🚀 ¿Cómo usarlo?

1. Abre el archivo `index.html` en un navegador.
2. Ingresa la hora de entrada y salida.
3. Haz clic en **Calcular Horas**.
4. Visualiza el resumen en gráfico de pastel y tabla.

> Nota: Para pruebas locales, asegúrate de tener activado el proxy desde https://cors-anywhere.herokuapp.com/corsdemo

## 🧪 Tecnologías usadas

- HTML5
- JavaScript (ES6)
- [TailwindCSS](https://tailwindcss.com)
- [Chart.js](https://www.chartjs.org/)
- [SweetAlert2](https://sweetalert2.github.io/)
- [CORS Anywhere](https://cors-anywhere.herokuapp.com/) (para evitar problemas de CORS)
