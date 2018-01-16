# DjangoSIGE

Sistema Integrado de Gestión Empresarial basado en Django

Proyecto independiente open-source desarrolado en Python 3

## Dependencias

- [django](http://www.djangoproject.com) == 1.10.1
- [geraldo](https://github.com/thiagopena/geraldo) - Generación de PDF para pedidos de venta/compra
- [apache2](https://www.apache.org/) (Opcional)
- [mod_wsgi](https://modwsgi.readthedocs.io/en/develop/) (Opcional)

## Instalação:

1. Instalar dependencias:

    ```bash
    pip install -r requirements.txt
    ```

2. Edite contenido de archivo **djangosige/configs/configs.py**

3. Generar un `.env` local

    ```bash
    python contrib/env_gen.py
    ```


4. Sincronizar base de datos:

    ```bash
    python manage.py migrate
    ```

5. Crear usuario (Administrador de sistema):

    ```bash
    python manage.py createsuperuser
    ```

6. Probar la instalación cargando el servidor de desarrollo (http://localhost:8000 en navegador):

    ```bash
    python manage.py runserver
    ```

## Implementaciones

- Registro de productos, clientes, empresas, proveedores y transportistas
- Login/Logout
- Creación de perfil para cada usuario.
- Permisos para usuarios.
- Creación y generación de PDF para ordenes de compra/venda
- Módulo financiero
- Módulo para control de inventario
- Módulo fiscal:
- Interface simple en Español

## Creditos

- [AdminBSBMaterialDesign](https://github.com/gurayyarar/AdminBSBMaterialDesign)
- [geraldo](https://github.com/marinho/geraldo)
- [jQuery-Mask-Plugin](https://igorescobar.github.io/jQuery-Mask-Plugin/)
- [DataTables](https://datatables.net/)
- [JQuery multiselect](http://loudev.com/)

## Ayuda

Para reportar bugs o [Issues](https://github.com/thiagopena/djangoSIGE/issues) ou via email thiagopena01@gmail.com

Cualquier feedback será Bienvenido.
