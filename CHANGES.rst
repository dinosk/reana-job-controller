Changes
=======

Version 0.4.0 (2018-11-06)
--------------------------

- Improves REST API documentation rendering.
- Changes license to MIT.

Version 0.3.2 (2018-09-26)
--------------------------

- Adapts Kubernetes API adaptor to mount shared volumes on jobs as CEPH
  ``persistentVolumeClaim``'s (managed by ``reana-cluster``) instead of plain
  CEPH volumes.

Version 0.3.1 (2018-09-07)
--------------------------

- Pins REANA-Commons and REANA-DB dependencies.

Version 0.3.0 (2018-08-10)
--------------------------

- Adds uwsgi for production deployments.
- Switches from pykube to official Kubernetes python client.
- Adds compatibility with latest Kubernetes.


Version 0.2.0 (2018-04-19)
--------------------------

- Adds dockerignore file to ease developments.

Version 0.1.0 (2018-01-30)
--------------------------

- Initial public release.

.. admonition:: Please beware

   Please note that REANA is in an early alpha stage of its development. The
   developer preview releases are meant for early adopters and testers. Please
   don't rely on released versions for any production purposes yet.
