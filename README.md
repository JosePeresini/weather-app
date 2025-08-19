# Panel Meteorológico

Esta _aplicación muestra el clima actual_ y el _pronóstico semanal para una ciudad_ buscada por el **usuario**.
Al ingresar el nombre de la ciudad en un campo de texto, la app obtiene datos de temperatura, descripción del cielo, iconos y pronóstico diario desde la API pública de OpenWeatherMap **( hasta 1000 llamadas por día gratuitas )**.
La interfaz es simple: muestra el nombre de la ciudad, la temperatura (en °C), y una breve descripción. Se manejan estados con React Hooks y actualizaciones automáticas
cuando cambia la ciudad.

## Requerimientos técnicos:

**React** _(funciones y Hooks)_ y Vite como bundler. Tailwind CSS para estilos.

Consumo de la _API de OpenWeatherMap_ ( clave de API gratuita en .env ).
Navegador moderno con Fetch/axios.

**Opcional:** manejo de estados con React y useEffect para peticiones en montaje o cambio de ciudad.

## Estructura de Carpetas:

<!--

clima-app/
├── public/
├── src/
│    ├── assets/
│    │     └── css/reset.css
│    │     └── js/weatherService.js (data)
│    │     └── image
│    ├── components
│    │     ├── WeatherCard.jsx
│    │     ├── Forecast.jsx
├── App.jsx
├── main.jsx
├── vite.config.js

-->

## Enlaces útiles:

Documentación de _OpenWeatherMap_ y de _TailwindCSS_, así como listas de _APIs públicas_
gratuitas:
GitHub Public APIs: https://github.com/public-apis/public-apis
RapidAPI: https://rapidapi.com/
