# 🔍 Tareas por Estado

## 🟢 En Proceso
```dataview
table proyecto, responsable, estado
from "03 - Tareas"
where estado = "En proceso"
```

## 🔴 Pendientes
```dataview
table proyecto, responsable, estado
from "03 - Tareas"
where estado = "Pendiente"
```
