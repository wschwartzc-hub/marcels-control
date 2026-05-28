# Marcel's · Control de Negocio

Sistema de gestión para Marcel's Seafood, Ceviches & More.

## Qué incluye

- **Punto de venta (POS)** con dos modos (carrito y rápido)
- **Inventario** que se descuenta automáticamente al vender
- **Insumos y costos reales** con rendimiento por producto
- **Recetas** que calculan el costo real de cada platillo
- **Inteligencia**: predicción de compras, patrones de venta por hora/día, efecto del clima
- **Pronóstico de ventas** con modelo estadístico que se ajusta solo
- **Clientes** con historial de compras
- **Dashboard** con vista por mes / año / rango personalizado

## Cómo funciona

Es una aplicación web de un solo archivo (`index.html`) que funciona 100% offline.
Los datos se guardan en el dispositivo (localStorage). Funciona sin internet,
excepto el clima automático que requiere conexión.

## Tecnología

HTML + CSS + JavaScript puro. Sin dependencias externas (la librería de Excel
viene embebida). Diseñado mobile-first.
