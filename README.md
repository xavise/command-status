command-status
==============

Utilities
---------

  * exec_and_save_status:

    Executes given command and arguments.

    Stores result in given status directory (must exist), but no output
    is produced.

    Creates this files in status directory:

        cmdline
        stderr
        stdout
        status

  * check_saved_status:

    Prints result stored in given status directory, and exits according
    to stored exit status as well.

