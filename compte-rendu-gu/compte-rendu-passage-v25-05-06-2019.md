# Compte rendu passage V25 \(05/06/2019\)

## Conclusion de la réunion déroulé avec Farid de chez Ineris

XML 2 =&gt; XML 3.0.

A partir du 15 juin 2019, les XML renvoyés par le GU seront en V3.  

Les différents PAD devront donc se mettre à niveau et envoyer des XML 3.0, pour la création de DICT, les DT récupéré seront obligatoirement en V3 donc pour les DT créée avant le changement vers la V25.0 nous ne seront pas impactés.

#### Modification pour toutes les déclarations : 

Une balise FaxObligatoire va maintenant contenir le fax et le mail. Ce champ devra obligatoirement contenir soit un fax soit une adresse mail.

#### Modification pour l'ATU : 

Balise ChantierTermineDuChantierAVenir =&gt; contient deux balises, la balise pasDeReponseAFournirChantierTermine et reponseAttendueChantierAvenir.

La seconde balise devra forcément être renseigné, en boolean. Si elle est à true, ce sera une ATU-DI











