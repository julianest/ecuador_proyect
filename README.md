# Ecuador Proyect

Este repositorio actúa como un contenedor para gestionar y desplegar los servicios relacionados con la gestión de personas, clientes, cuentas y movimientos bancarios. Incluye los submódulos de los proyectos individuales y permite su integración y administración centralizada.

## 📌 Proyectos Incluidos

Este repositorio contiene dos submódulos que corresponden a los siguientes servicios:

1. **Servicio de Personas y Clientes** ([Repositorio](https://github.com/julianest/ecuadorPerson))
   - Manejo de personas y clientes.
   - CRUD de clientes.
   
2. **Servicio de Cuentas y Movimientos** ([Repositorio](https://github.com/julianest/ecuadorCtaMov))
   - Gestión de cuentas bancarias y sus movimientos.
   - Registro de transacciones.

## 🔧 Configuración Inicial

Para clonar este repositorio junto con los submódulos, usa el siguiente comando:

```sh
git clone --recurse-submodules https://github.com/julianest/ecuador_proyect.git
```

Si ya clonaste el repositorio sin los submódulos, puedes inicializarlos con:

```sh
git submodule init
```

Y luego actualizarlos con:

```sh
git submodule update --recursive
```

## 🚀 Despliegue

Próximamente se incluirán instrucciones para desplegar los servicios de manera centralizada desde este repositorio.

## AUTOR
Julian Huerfano

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo `LICENSE` para más detalles.

