.. meta::
   :description: Use hasura scripts for the update-config-v2 script on the Hasura CLI
   :keywords: hasura, docs, CLI, hasura scripts update-config-v2

.. _hasura_scripts_update-config-v2:

Hasura CLI: hasura scripts update-config-v2
-------------------------------------------

Upgrade config from v1 to v2

Synopsis
~~~~~~~~


Upgrade config from v1 to v2

::

  hasura scripts update-config-v2 [flags]

Examples
~~~~~~~~

::

    # Upgrade config from v1 to v2
    hasura scripts update-config-v2
    
    # Upgrade to v2 config with metadata directory set
    hasura scripts update-config-v2 --metadata-dir metadata

Options
~~~~~~~

::

      --admin-secret string   admin secret for Hasura GraphQL engine
      --endpoint string       http(s) endpoint for Hasura GraphQL engine
  -h, --help                  help for update-config-v2
      --metadata-dir string    (default "metadata")

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --log-level string    log level (DEBUG, INFO, WARN, ERROR, FATAL) (default "INFO")
      --no-color            do not colorize output (default: false)
      --project string      directory where commands are executed (default: current dir)
      --skip-update-check   skip automatic update check on command execution

SEE ALSO
~~~~~~~~

* :ref:`hasura scripts <hasura_scripts>` 	 - 

*Auto generated by spf13/cobra*
