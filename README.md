# Helm-daemon

The goal of this project is to provide a different way of communicating with helm. Creating and managing helm charts is a really powerful way of managing your
running applications, but since the official version is limited to CLI use only, it is limited to either manual use only, or gimmicky software implementations.

This project opens up the Helm API to http requests via Unix sockets (default), or full fledged REST API on the network.
