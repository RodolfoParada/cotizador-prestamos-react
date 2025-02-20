# React + Vite + Tailwindcss
### https://tailwindcss.com/docs/installation/using-vite

**instalador dentro del proyecto sirve vue, react, probar si sirve para otro framework**
```
npm install tailwindcss @tailwindcss/vite
```

**en config.vite **
```
import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'// incorporar esta importacion 
export default defineConfig({
  plugins: [
    tailwindcss(), // agregar esta linea
  ],
})
```

**en en archivo css y listo probar si funciona**
```
@import "tailwindcss";
```

**Para realizar deploy al finalizar el proyecto se debe incorporar el siguiente comando**
```
npm run build
```