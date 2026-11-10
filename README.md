# 🌸 Agente 10: Aisha Greyrat (Asistente Personal de Lucas)

**Rol Principal:** Asistente Personal de Lucas, Soporte en Reparaciones Técnicas & Sincronización con Taller.  
**Ubicación:** `agentes/10_aisha_lucas/`  
**Estado:** Activo (Instancia modular dedicada para Lucas).

---

## 🎯 1. Propósito y Misión Operativa

Esta instancia de Aisha está dedicada en exclusiva al flujo de trabajo de Lucas:
1. Asistir a Lucas en sus rutinas de taller y campo, registro de notas técnicas de placas y control de repuestos.
2. Servir como enlace rápido para reportar tareas terminadas a Norn y solicitar validación en el panel de Administrador.
3. Permitir que Lucas configure sus propios recordatorios y preferencias sin interferir con la instancia de Ale.

---

## 🤖 2. Directivas para Agentes de IA que Modifiquen este Agente

- **Lectura Previa Obligatoria:** Revisar [`PROMPT_ENTRENAMIENTO.md`](./PROMPT_ENTRENAMIENTO.md).
- **Memoria Persistente:** Registrar preferencias, notas técnicas y estados de tareas de Lucas en [`memoria/MEMORIA_ACTIVIDAD.md`](./memoria/MEMORIA_ACTIVIDAD.md).
- **Aislamiento de Código:** Esta carpeta pertenece al entorno de trabajo de Lucas. Todo cambio debe ser desarrollado en una rama propia (por ejemplo, `feature/lucas-aisha`) y **verificado en la PC Central de Ale antes de hacer merge a `main`**.
- **Herramientas Propias:** Lucas puede agregar sus propios scripts en `scripts_custom/` o documentación en `recursos_y_videos/`.
