# TP3 CCNA
# 1.Création et utilisation simples d'une VM CentOS
## I-Création
## II-Installation de l'OS
## III-Premier boot
## IV-Config réseau d'une machine CentOS

   *A faire*  
   a. Pour prouver qu'il y a internet sur la VM j'ai utilisé le raccourci :curl google.com  
   ![Légende](IMG/IMG1.PNG)  
   b. Pour prouver que mon PC et la VM peuvent communiquer j'ai fais la commande: ping 192.168.127.1 et ping 192.168.127.10  
   ![Légende](IMG/IMG2.PNG)  
   ![Légende](IMG/IMG3.PNG)  
   c.  
   ![Légende](IMG/IMG4.PNG)  
   La première ligne est l'adresse IP que l'on devait avoir, la deuxieme ligne est l'adresse IP
   
## V-Faire joujou avec quelques commandes
   *A faire*  
   * cf `Voir IV à faire`  
   * 
   ![Légende](IMG/IMG4_1.PNG)  
   
   ![Légende](IMG/IMG5_1.PNG)  
   *
   ![Légende](IMG/IMG6.PNG)  
  
   *
   ![Légende](IMG/IMG7.PNG)  
   
   ![Légende](IMG/IMG8.PNG)  
   
   # 2.Notion de ports et SSH
   
  ## I-Exploration des ports locaux
  ![Légende](IMG/IMG9.PNG)  
  ## II-SSH
  ![Légende](IMG/IMG11.PNG)  
  ## III-Firewall
  A-SSH
  Modification du port 22 en port 2222
  ![Légende](IMG/IMG12.PNG)  
  Modif via le Firewall et la connexion a pu etre etabli avec putty
  ![Légende](IMG/IMG13.PNG)  
  
  B-NETCAT
  yum install nmap-ncat  
  ![Légende](IMG/IMG14.PNG)  
J'ai pu dialoguer entre mes deux terminals sur le port 5454 mais lorsque je fais mon ss il y a que le port 2222 qui apparait.

   # 3.Routage statique
   
   # II-Configuration du routage
   Voici l'addrese IP de mon PC1 et de la VM1
   ![Légende](IMG/IMG15.PNG)  
   J'ai ping le réseau 2 depuis ma VM1.
   ![Légende](IMG/IMG16.PNG)  
   J'ai ping le réseau 12 depuis ma VM1.
   ![Légende](IMG/IMG17.PNG)  
    
   # III-Configuration des noms de domaine
   J'ai changé mon nom de domaine et j'ai seulement réussi à ping ma propre VM depuis ma VM avec le nom de domaine.
   ![Légende](IMG/IMG18.PNG)  
