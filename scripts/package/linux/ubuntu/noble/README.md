n.b. for running `//scripts/package/linux/ubuntu/noble/package`:

By default, the `package` script will attempt to write the packages in the
root directory of the local libbot2 installation. In order for the write to
succeed, this directory needs to have global write permissions enabled. This
can be accomplished by running the following:

  ```
  $ sudo chmod a+w </path/to/libbot2>
  $ source ~/.bashrc
  ```

Note that if you use a different shell or configuration file, you will have to
change the path provided for the second command.
