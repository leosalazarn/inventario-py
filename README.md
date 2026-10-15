# Control de Inventarios para tienda
Esto es un control de inventarios

inventario-py/
│
├── dominio/                # (Models/Entities) El núcleo del negocio
│   ├── __init__.py
│   ├── producto.py         # Clase Producto, ProductoPerecedero, ArticuloMagico
│   └── inventario.py       # Clase Inventario
│
├── fabricas/               # (Factories) Patrones de creación
│   ├── __init__.py
│   └── fabrica_productos.py# Clase FabricaProductos
│
├── motor/                  # (Core/Controllers) Lógica del juego e interacciones
│   ├── __init__.py
│   └── tienda.py           # Clase Tienda
│
├── utilidades/             # (Utils/Cross-cutting concerns) Servicios globales
│   ├── __init__.py
│   └── historial.py        # Clase HistorialTransacciones
│
├── tests/                  # Pruebas unitarias (TDD)
│   ├── __init__.py
│   └── test_productos.py
│
└── main.py                 # Punto de entrada de la aplicación

