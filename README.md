# property-broker
Property broker es una herramienta que te permite buscar de manera eficiente sobre el [portal inmobiliario](https://www.portalinmobiliario.com/) para encontrar oportunidades de negocio.

Este repositorio se utiliza para levantar el proyecto completo (utilizando git submodules) pero no debe ser usado para implementar cambios a un repo específico.

### Clonar repositorio

```
git clone --recurse-submodules https://github.com/Grupo8-GPTI-2025-1/property-broker.git
```

### Actualizar repositorios

```
git submodule update --remote --merge
```

### Levantar contenedores

```
docker-compose up --build
```

### Scripts

Para levantar `db` de manera independiente

```
 docker-compose up db
```

(Notar que para crear las tablas es necesario levantar el backend primero)

### Ejecución 

1. Levantar contenedores

2. Setup scrapper (Más información [aquí](https://github.com/Grupo8-GPTI-2025-1/scraping-tool/tree/main))

3. Scrappear páginas (Se debe tener al menos backend y db funcionando)

4. Ver Applicación en `http://localhost:3000`