Быстрый старт
=============

Создайте файл ``composer.json``:

.. code-block:: js

    {
        "require-dev": {
            "phpspec/phpspec": "^4.0"
        },
        "config": {
            "bin-dir": "bin"
        },
        "autoload": {"psr-0": {"": "src"}}
    }

Следуйте инструкциям на этой странице, чтобы установить Composer: `<https://getcomposer.org/download/>`_.

Установите **phpspec** с помощью Composer:

.. code-block:: bash

    php composer.phar install

Начните написание спецификаций:

.. code-block:: bash

    bin/phpspec desc Acme/Calculator

Узнайте больше из :doc:`документации <manual/introduction>`.

.. toctree::
   :hidden:
   :maxdepth: 1

   manual/introduction
   manual/installation
   manual/getting-started
   manual/prophet-objects
   manual/let-and-letgo
   manual/upgrading-to-phpspec-4
   manual/upgrading-to-phpspec-3

.. toctree::
   :hidden:
   :maxdepth: 1

   cookbook/configuration
   cookbook/console
   cookbook/construction
   cookbook/matchers
   cookbook/templates
   cookbook/extensions
   cookbook/wrapped-objects

.. ready: yes
.. revision: dae50e5501f0bd990748f5710a61ac9089255dff
