Ansible Plex Role
=========

Ansible role for installing Plex Media Server

Requirements
------------

No specific requirements

Role Variables
--------------

| Variable           | Default | Comments                                                                                  |
|--------------------|---------|-------------------------------------------------------------------------------------------|
| plex_state         | latest  | The state for package. Can be latest, present or absent                                   |
| plex_service_state | started | Default state for the service                                                             |
| plex_nfo_plugins   | true    | Whether to install nfo plugins to allow consistent importing when using Kodi or MediaElch |

Dependencies
------------

No Dependencies

License
-------

BSD