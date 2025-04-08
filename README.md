# push_swap
Proyecto de 42 para ordenar números utilizando stacks y operaciones limitadas.

### 🧠 Descripción

Este proyecto de 42 consiste en ordenar una lista de números utilizando dos stacks (`a` y `b`) y un conjunto limitado de operaciones. El objetivo es reducir el número total de instrucciones.

### 📁 Estructura

- `push_swap.c` - Entrada principal
- `chunk_sort.c` - Lógica del algoritmo principal
- `instructions_*.c` - Operaciones permitidas
- `index_creation.c` - Transformación de valores en índices
- `error_release_functions.c` - Gestión de errores y memoria

### 🔧 Compilación

make

### ▶️ Ejecución

./push_swap 3 2 1

### 🧪 Testing

ARG=$(seq 1 500 | shuf); ./push_swap $ARG | wc -l
