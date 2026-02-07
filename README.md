# **Vercel**

## ***IDE***

- *Visual Studio Code:*
Es el estándar en Vercel porque permite una integración nativa con su ecosistema de herramientas (Vercel CLI) y una personalización total mediante extensiones que aseguran la calidad del código en proyectos masivos como Next.js.
- *ESLint:* 
Se utiliza para automatizar la revisión de reglas de programación, evitando que errores de lógica lleguen a producción y manteniendo la deuda técnica al mínimo.
- *Prettier:* 
Es fundamental para el trabajo colaborativo; al formatear el código automáticamente, elimina discusiones sobre estilos visuales y facilita la lectura de los Pull Requests. 
- *Tailwind CSS IntelliSense:* 
Optimiza la velocidad de desarrollo al proporcionar autocompletado y vistas previas de clases CSS, reduciendo errores visuales en la implementación de interfaces modernas.
<img width="1365" height="639" alt="image" src="https://github.com/user-attachments/assets/b1f2d617-5745-4e81-9715-216dd375d044" />

## ***Navegadores***
- *Google Chrome (Motor Blink):* 
Es la herramienta base para la optimización de las Core Web Vitals. Vercel lo utiliza para ejecutar auditorías de Lighthouse, asegurando que el rendimiento de sus sitios sea de nivel profesional (cercano al 100%).
- *Arc Browser:* 
Adoptado por su flujo de trabajo eficiente, permitiendo a los desarrolladores organizar múltiples entornos de prueba (desarrollo, staging y producción) de forma aislada y ordenada.
- *Playwright:* 
Justificado por la necesidad de realizar pruebas E2E (End-to-End) automáticas que garantizan que las aplicaciones funcionen perfectamente en todos los motores de renderizado (Blink, WebKit y Gecko) antes de cada despliegue.
<img width="1365" height="637" alt="image" src="https://github.com/user-attachments/assets/a46f2d3e-8544-4e88-a5f0-bbb0b3360213" />

## ***Versiones***
- *Herramienta Base: Git.* 
Implementado para permitir un desarrollo no lineal y seguro; cada nueva función se trabaja en ramas independientes, lo que facilita la reversión de errores sin afectar el código principal.
- *Plataforma de Alojamiento: GitHub.* 
Es el eje central de su cultura de CI/CD. Vercel utiliza GitHub porque su plataforma de despliegue depende de los webhooks de esta red para disparar compilaciones automáticas y generar URLs de previsualización en tiempo real.
<img width="1355" height="630" alt="image" src="https://github.com/user-attachments/assets/2cadf593-3dbf-4a42-b1e6-8aabc61d58aa" />


## ***Diseño***
- *Herramienta: Figma.*
Utilizan Figma porque permite la colaboración en tiempo real entre diseñadores y desarrolladores. Además, Figma permite exportar variables (colores, espacios) directamente a código CSS o Tailwind, lo que acelera el proceso de pasar del prototipo a la web real.
<img width="1343" height="641" alt="image" src="https://github.com/user-attachments/assets/98187f8a-eec2-4f4e-a78a-bbf6beae75c2" />

## ***Lenguajes***
- *TypeScript (TS):*
Utilizado por encima de JavaScript tradicional para añadir tipado estático. Esto permite detectar errores en tiempo de compilación, lo cual es vital cuando cientos de desarrolladores colaboran en el mismo código.
- *Rust:*
Justificado por su extrema velocidad y seguridad de memoria. Vercel ha migrado sus herramientas de compilación (como Turbo) a Rust para reducir los tiempos de espera de los desarrolladores de minutos a segundos.
- *MDX:*
Implementado para unir la potencia de los componentes interactivos de React con la simplicidad del contenido escrito, permitiendo crear documentación técnica dinámica y atractiva.
<img width="368" height="370" alt="image" src="https://github.com/user-attachments/assets/c9ec884c-4b7d-4432-be98-c182bac113aa" />

## ***Finalizando reporte de investigación de Vercel***
