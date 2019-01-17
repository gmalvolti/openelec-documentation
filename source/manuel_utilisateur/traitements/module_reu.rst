.. _module_reu:

##########
Module REU
##########


Le module REU est accessible via le menu
(:menuselection:`Traitement --> REU`).

.. image:: a_module_reu_menu.png


.. contents::


Préambule
=========

Ce module permet de gérer les échanges dématérialisés de données électorales
entre les communes et le Répertoire Électoral Unique.

.. note::

   La commune reçoit un identifiant et un mot de passe par sa préfecture pour
   accéder à la plate-forme de l'INSEE https://repertoire-electoral.insee.fr/

openElec se connecte directement à cette plate-forme pour **TOUS** les échanges
nécessaires à la gestion des listes électorales. La commune a simplement besoin
de s'y connecter pour gérer les comptes utilisateurs (dont celui d'openElec).


.. _module_reu_statut:

Statut
======

.. image:: a_module_reu_onglet_main.png

Cet écran permet de configurer la connexion logicielle au REU et de visualiser
son statut.

.. _module_reu_synchronisation_liste_electorale:

Synchronisation Liste Électorale
================================

Cet écran permet de mettre en concordance la liste des électeurs openElec avec
celle du REU. L'objectif de cette étape est d'associer un numéro INE à chaque
électeur openElec.

