# Ejercicio 3: FiguraColeccionable

## Explicación Lógica
1. **Sobrescritura de Métodos:** Con `@Override`, la subclase reemplaza la implementación general de `calcularPrecioVenta()` por una regla específica de negocio.
2. **Lógica Diferencial:** Si la figura es de edición limitada (`esEdicionLimitada == true`), aplica un recargo del 25% sobre el precio base; de lo contrario, reutiliza la respuesta de la superclase.