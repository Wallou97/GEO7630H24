# GEO7630H24_P2
Voici le deuxième dépôt 
Université de Québec à Montréal - UQAM 
 
TP2 -
 
Intégration des données vectorielles et matricielles 
 
Responsable
 
: Clément Glogowski 
 
Par Walyde
 
Véronique & Wissam Mehanna 
 
 
 
 
 
Ce read.me
 
présentera le FME Workbench de notre TP2. Ce workbench présente plusieurs jeux
 
de données pour une analyse statistique des transports en commun disponible sur
 
l’ensemble de l’île de Montréal. Pour simplifier la lecture du readme on va
 
présenter un axe de jeux de données, et pour terminer un résultat final sera
 
montré. Les difficultés seront présentées et les échecs de notre
 
FME.   
 
 
 
1.    Intégration des données géographiques 
 
Limite des quartiers 
 
![](https://lh7-us.googleusercontent.com/YXDLrkAphB5uCvFKCHmUt03MMpNZfVckEAcQjxNGzYoEDy_m8biH9_oFsvxIpXi55JWVu3hVIDswlZurlleUkwVpSSR09EqyPraCDuLhaHh3DDhT9TXJudUbYkaH3cmnrBACwKs-HaPjvVQb70l7WAo)
 
2\. Un calcul de superficie est nécessaire avec AreaCalculator pour une analyse statistique
 
![](https://lh7-us.googleusercontent.com/2yM6vbma5d_so5BpUEaVhfL-9BEVZ1AxUh1_Doe0rfuBDbokeYFTJGuFCaxVfJ0Oqt7cwZp_MyFxe_IJeA3ErwvkODW19Ph35ZW3y0z5o2-3dRvU55Zf-15mkg3xx1LeW4FGICZHYO2kZ7t-1v6FOPw)
 
3\. Une conversion de m² en km² pour des données statistiques viable. 
 
![](https://lh7-us.googleusercontent.com/WUdclhm7S-RkC8I4l-ykrNCYZfL39vV_9RKCeHc-9Q0HHFnTRsZOQ3CiHkZEoy5fB3jKiKxGvFgt9vj1Eiq885atNounE7VQCP-jGJMxjj0xQOOK1QNhjNnyNdpO9tyjz5vXwSYm0HjIKtDdjgcm9mE)
 
4.        Intégration des données de comptage des passages de vélo dans les quartiers de Montréal, avec une reprojection et une jointure spatiale avec les limites de quartier.
 
![](https://lh7-us.googleusercontent.com/dprNxpXjq780zVX0jCoBUyprgoKc6G6wd-9oPJAKDssu5ZFA8fY6VmGD8i7WsahawzyY_wD8bb5u4_JyyABuBjei_z6o8BZB7SfgGeVucP2yFMp502uhfkas-whZ2K724IcyeC_w7h37-NvR8msa0H8)
 
****
 
5\. Sélection des attributs avec attribute keeper nécessaire pour l’exercice, création d’un jeu de données de densité avec attribute creator, renommer les colonnes avec Attribute Manager et pour finir calcule statistique avec stastistics calculator.
 
![](https://lh7-us.googleusercontent.com/4ix5BUAfUdUTmelrUKiuDRVded0YG9FFoXiwt5jRk-yX_lFckF6IcwvNoZLx5KG4eHTuQsiX2es4NhF_2O9WAunDa0NwlJck6kXXGKzb6oAz3BiiH7w9kj9GDGgxxCnfRv65rA3mFMFKws8VjUznl70)
 
****
 
6.        Pour finir il faudra de nouveau renommer les nouvelles colonnes créer, retirer les valeurs null avec nul attribute mapper et faire la connexion au projet QGIS.
 
![](https://lh7-us.googleusercontent.com/DVczP8C12ANNEo1qf3vDgv8WHqv8r4CU1CHr-pRABQZbnPbT-cXxvb1XBOevVPHoHSvgpUeOjMc4_lA2PjKfk_5a4HGwXVgnQAUAou72o1OpjoSsh-B9Gl0cZPvwhldcQMYm9MaJJWYZGcRChhxWRmY)
 
****
 
7\.               Une grille H3 est faite pour faciliter la lecture graphique du projet. 
 
![](https://lh7-us.googleusercontent.com/VtNohv7hxsEmdiWavsfV0hkKDj-UvaRItDEmavHVRUt_tMfDSacmkCXjp0gSuEGVUX3oGh7HcfAlIUSpBOtLSc08kZpCQe3t6aljmXSoNqdAkiXvqohc59WvN8mYYTDMbiI3z_9gjXOd3Vhehe049ck)
 
****
 
8\.     Connexion de la grille H3 au donnée comptage de vélo avec point on area overlayer, et faire la connexion au QGIS
 
![](https://lh7-us.googleusercontent.com/rulz_tL4Ed2GteBuhU4glefCX1IemNGSjdOj5ZQkpS6XrQhsn5nakAc0Zl_qFYpiTMbJpV70MF1Iswu-LetJ1win3qwB_1HM3icYNTLkCLlepaO2rT9tIzi-XPnhr6TVSWStVfb1_bXfvei38cbVjN8)
 
9\.     Résumé du FME Workbench 
 
![](https://lh7-us.googleusercontent.com/C5g7HigLE-HHXy2qcEsCtvsqtkRnqxTFU7qHDhU-6uA-rvxM2RBbkEiy3xIzZXvflrZfsPa7fwsKlT-3_dtYaYUkTfP2NjTSD04CTOuWe5N-4hZ0Yyp6OHX_vm2ievCIX8Ogs4TvvvnTfU9rbKuh-Qk)
 
![](https://lh7-us.googleusercontent.com/ggnfzrSxZocIcBtHDGbRm0jKpOJolxZxCeu76-4cqu3RSbMzvZ1vnww4JwaQfrsntKUy7d_tqubWZGFqt8P40oqW_UWsOGgL0MCQJ24O0hTo46UuCoB-tHxTwF2jf_1-y_q9mmKijq1IT3xYWqdMQOE)
 
10..     Lecture des données sur QGIS 
 
![](https://lh7-us.googleusercontent.com/V3GXiMY_JQS8Z_qqFJWOUJUCTmrwdDturzO8ZWPlIUfFt4eGQuB7mQBCn_3pW0pR54dmIhu8mzgFwVfcIB1_DFD0Sf-AMhEE6nM0Sms_xgMIqQ_W6r6JFWqdXWK9_eXmj4HehLvLFOr1aXBPlzidrIs)
 
11\. Distribution du comptage de vélo
 
![](https://lh7-us.googleusercontent.com/_YcmmzNQvHw9r_xgxzk6QPJfS0ZaXpb_jUKGJP8iZZGpuJHnQvkDUHp9Rw1TNtwLuPLptGRAWTn1HnEB4DpvAf2w-7XqXPdPEgkSVH3YuwAxU9oi5RY357KM8V679DP4mTMTouyozIry_2dJfh4z5Mo)
 
12\.     Echec sur des données comme les densités des piste cyclables, la donnée n’est pas présente dans la graduation, elle apparaît en données texte, les photos aérienne ne s'affiche pas non plus 
 
![](https://lh7-us.googleusercontent.com/iG2yiWOgiAtv0VVbSEmgV9Y4p0p2gcFjLueoKZ6qxw4x-j-ib6GHhU9JhvrTXv0agESB-hoSt8vuprVjMZ3q_37vpL_aDjXuorRNdWdPY5ZA6_W1W5ccYnuL61mWUJ-4xf6Tk4PjfQ8LTVRwnTaGKTM)
