Il se peut que dans le cadre d’un déploiement de Microsoft Purview ou Microsoft Fabric, vous ayez besoin de gérer la session des utilisateurs en forçant la déconnection automatique après un certain laps de temps d’inactivité. Dans cet article, je vais expliquer commencer paramétrer la déconnexion automatique pour ces 2 solutions.

# Microsoft Purview

1.	Avec un compte Global Admin, connectez-vous au portail Azure (https://portal.azure.com)
2.	Cliquez sur l’engrenage en haut à droite de l’écran 
3.	Cliquez sur « Signing out + notifications »
4.	Dans la rubrique « Signing out », cochez la case « Enable directory level idle timeout » puis définissez le délai avant la fermeture de session.

![image](Images\001.png)

