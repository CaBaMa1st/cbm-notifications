### Preview / Notifications (UI)

- Vista previa | Preview : [image/imagen](https://cdn.discordapp.com/attachments/955063452026691584/1059552627706298428/image.png)
- Facil de Editar
- UI Moderna

### Creditos

- Discord: Nightt#8899 & TusMuertos.#4903 // https://discord.gg/8rTndJFRMn
- Script Original | Original Resource : https://github.com/Nightt7/NJ-Notifications
- Vista previa | Preview : https://streamable.com/woxj84

### Fallos
- Si encontrais fallos, o necesitais ayuda // discord: CaBaMa™#5329

### Requirements | Requerimientos
- ESX
- Añadir 3 lineas de codigo al es_extended/client/functions.lua // reemplazando la funcion de ESX.ShowHelpNotification
- Codigo:
    ESX.ShowHelpNotification = function(text)
        return exports["cabama_help"]:showHelp(text)
    end

