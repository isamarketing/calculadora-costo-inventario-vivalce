# VIVALCE — Tool Costo Financiero de Inventario

Herramienta interactiva para calcular y simular el costo financiero del inventario por producto.

## URL

[https://isamarketing.github.io/tool-inventario-vivalce/](https://isamarketing.github.io/tool-inventario-vivalce/)

## Funcionalidades

- **Controles globales**: TNA (slider), Tipo de Cambio, Volumen Mensual
- **Controles por producto**: Lead Time y Stock de Seguridad ajustables con sliders, Volumen Anual editable
- **KPIs en tiempo real**: Stock inmovilizado, CF anual, CF promedio/kg, CF mensual ARS
- **Sidebar**: Desglose por origen, Top productos por costo financiero, Fórmulas
- **Export CSV**

## Fórmulas

- Stock Std (días) = Lead Time + Stock Seguridad
- Stock (kg) = (Vol Anual / 365) × Stock Std días
- Stock USD = Stock kg × |DDP|
- CF Diario = (Stock USD × TNA) / (Vol Anual × 365)
- CF/kg Stock Std = CF Diario × Stock Std días
- CF Anual = CF/kg × Vol Anual

## Parte del Sistema P&L

Este tool es parte del Sistema de Gestión P&L por Producto para VIVALCE y RECSA.
El costo financiero se integra al P&L debajo del EBITDA para calcular el resultado neto.
