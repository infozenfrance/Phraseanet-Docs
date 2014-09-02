FAQ Administration
==================

.. topic:: The essential

    This section of the FAQ regroups the questions about *Phraseanet*
	administration.

I can't upload files of more than 2Mb
-------------------------------------

Example to raise the limit to 200Mb :

* In the file php.ini :

.. code-block:: bash

    upload-max-filesize = 200M
    post_max_size       = 200M

Restart your configuration (Apache or PHP-Fpm depending on the case).

With Nginx for web server, large queries must be activated :

* In the file nginx.conf :

.. code-block:: bash

    http {
        ...

        client_max_body_size 200M;

        ...
    }

The result thumbnails are hot-air-balloons
------------------------------------------

Make sure that the sub-definitions task is started in the Admin module. See
`task manager documentation </Admin/TaskManager>`_

There are no thumbnails in the search results
---------------------------------------------

If there are no thumbnails (only the titles), it is that the thumbnail directory
is not well constructed in the web server

Check in the Virtual Host the Alias "/web" and check that it points to the
directory used to stock thumbnails. See `installation documentation
</Admin/Install>`_

When mass editing documents, error messages appear
--------------------------------------------------

The Suhosin module can limit the number of argument per query.
Raise this limit in the configuration file php.ini

.. code-block:: bash

    suhosin.post.max_vars    = 12000
    suhosin.request.max_vars = 12000

When modifying user rights, some rights are not saved
-----------------------------------------------------

The Suhosin module can limit the number of argument per query.
Raise this limit in the configuration file php.ini

.. code-block:: bash

    suhosin.post.max_vars    = 12000
    suhosin.request.max_vars = 12000

The installation aborted, how to resume it ?
--------------------------------------------

To resume an aborted installation, delete the following files :

* config/config.yml
* config/connexions.yml
* config/services.yml
