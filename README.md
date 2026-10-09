# Portal PEC

## Migrar la Base de Datos
Para aplicar las migraciones a la base de datos, abre la terminal en el directorio del proyecto y ejecuta los siguientes comandos:

```bash
python manage.py makemigrations
python manage.py migrate
```

## Archivos Estáticos
Recopila todos los archivos estáticos de tus aplicaciones ejecutando:

```bash
python manage.py collectstatic
```

## Ejecutar el Servidor
Para iniciar el servidor local, utiliza el siguiente comando:

```bash
python manage.py runserver
```
