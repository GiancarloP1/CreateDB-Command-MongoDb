## Comandos Utilizados:

1\. Conexión a MongoDB:
\`mongo\`

2\. Crear una base de datos:
\`use tienda_online\`

3\. Crear una colección:
\`db.createCollection('productos')\`

4\. Insertar documentos en la colección:
\`\`\`bash
db.productos.insertMany(\[
  { nombre: 'Laptop', precio: 1000, categoria: 'Electrónica' },
  { nombre: 'Celular', precio: 500, categoria: 'Electrónica' },
  { nombre: 'Cafetera', precio: 100, categoria: 'Hogar' }
\])
\`\`\`

5\. Ver los documentos insertados:
\`db.productos.find().pretty()\`
