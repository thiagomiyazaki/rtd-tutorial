Teste
=====

.. _installation:

Como criar títulos
------------------

Para iniciar o servidor de desenvolvimento:

.. code-block:: console

   (.venv) $ python manage.py runserver

Para abrir o shell do Django:

.. code-block:: console

   (.venv) $ python manage.py shell

Importando Models 
-----------------

Para importarmos o model ``Gene`` e instanciar um objeto:

>>> from brpcw4mb.models.molecular_components_import Gene
>>> q = Gene.objects.all()
