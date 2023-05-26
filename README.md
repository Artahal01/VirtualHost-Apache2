                                            	Installation d'Ansible
1-Installation :
 
-Vérifier que les packages sont à jours :
 
  		 $ sudo apt update

-Installez le package Ansible :

  		 $ sudo apt install ansible
		 
		 
2- Configuration du fichier d’inventaire
Le fichier d’inventaire contient des informations sur les hôtes que vous gérerez avec Ansible. 

Pour modifier le contenu de votre inventaire Ansible par défaut, ouvrez le fichier "/etc/ansible/hosts" en utilisant l’éditeur de texte de votre choix sur votre nœud de contrôle Ansible :

 		 $ sudo nano /etc/ansible/hosts
