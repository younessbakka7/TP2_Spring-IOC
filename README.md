# TP2_Spring-IOC

<img width="1272" height="259" alt="1" src="https://github.com/user-attachments/assets/7ea4784a-a012-4ff2-9b42-ffa6b4a30df0" />
Cette capture d’écran montre l’exécution de la classe presentation2. Le résultat affiché est 200.0, ce qui confirme le bon fonctionnement de l’application Spring IoC et l’appel de la méthode calcul().

<img width="1327" height="258" alt="2" src="https://github.com/user-attachments/assets/12ad7f1a-d64c-4464-a554-779ed389a7f9" />
Cette capture d’écran montre l’exécution de la classe presentation2 après la modification de l’injection des dépendances avec Spring. Le résultat obtenu est 300.0, ce qui confirme que l’application utilise DaoImpl2, qui retourne 150.0, puis multiplie cette valeur par 2 dans la méthode calcul().

<img width="974" height="263" alt="3" src="https://github.com/user-attachments/assets/4f304b33-4100-44c1-b8ba-72be94758c58" />
Cette capture d’écran montre l’exécution du test unitaire testCalcul() de la classe MetierImplTest. Le test est réussi (1 test passed), ce qui confirme le bon fonctionnement de la méthode calcul() de la classe MetierImpl.
