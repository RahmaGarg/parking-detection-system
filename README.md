# 🚗 **Parking Spot Detection System** 🅿️

Ce projet utilise la vision par ordinateur (OpenCV) pour détecter et suivre les places de parking disponibles et occupées dans un parking à partir d'une vidéo. L'objectif principal de ce système est de fournir une solution intelligente pour surveiller l'occupation des places de parking en temps réel, en utilisant des informations de coordonnées pré-définies de chaque place dans un fichier YAML.


## 🌟 **Fonctionnalités**

- **Détection de places de parking** 🅿️ : Le système utilise un fichier YAML contenant les coordonnées des places de parking pour les détecter sur une image ou une vidéo. Chaque place est identifiée par un contour polygonal défini par ses points.
  
- **Suivi de l'occupation** 📊 : À l'aide des contours de chaque place, le système surveille les changements dans les zones définies pour déterminer si une place est libre ou occupée. Un algorithme de détection de mouvement est utilisé pour identifier l'occupation.

- **Affichage en temps réel** ⏱️ : Le programme superpose les résultats de la détection sur les vidéos, affichant les places disponibles en **vert** et les places occupées en **rouge**. Il affiche également des informations comme le nombre total de places et le nombre de places occupées.

- **Interface interactive** 🖱️ : L'utilisateur peut ajouter ou supprimer des places de parking en cliquant sur l'image. Les coordonnées des places sont sauvegardées dans un fichier YAML pour une utilisation future.

