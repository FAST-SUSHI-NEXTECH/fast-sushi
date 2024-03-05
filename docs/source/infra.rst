Infra
=====

.. autosummary::
   :toctree: generated

Présentation
------------

L'infra de notre projet en schéma ci-dessous:

.. image:: /assets/infra.png
   :width: 400
   :alt: Alternative text

VPS
----------------
.. note::

   N'ayant pas de server à notre disposition, nous avons décidé de financer notre propre VPS en équipe.

* **Hébergeur**: Redheberge
* **Coût par mois**: 8e
* **Admin** principal du VPS: Talace



DOCKER
----------------

**Equipe "DevOps"**: Talace

N'ayant qu'un seul serveur à notre disposition et étant curieux de Docker. J'ai opté pour une infrastructure entièrement conteneurisée, séparée en 4 parties :

* Web App
* Base de Données
* API
* Websocket
