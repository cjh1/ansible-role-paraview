ParaView
=========

An Ansible role to build [ParaView](http://paraview.org).

Requirements
------------

This is intended to be run on a clean Ubuntu 14.04 or CentOS 7 system.


Role Variables
--------------

The following variables may be overridden:

* `paraview_view`: The ParaView version to build ( tag or SHA ).
* `paraview_path`: The path to clone and build ParaView in.

License
-------

Apache
