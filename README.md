# Lab-Hidden-Markov-Models
Ce dépôt contient un travail pratique réalisé dans le cadre de mon programme de Mastère Spécialisé à Télécom Paris. Ce TP se déroule en deux parties. La première partie concerne les chaînes de Markov et la deuxième partie traite des HMMs.

Une <i>chaîne de Markov</i> est un modèle statistique composé d'états et de transitions. Une transition matérialise la possibilité de passer d'un état à un autre. Dans le modèle de Markov, les transitions sont unidirectionnelles : une transition de l'état A vers état B ne permet pas d'aller de l'état B vers l'état A. Tous les états ont des transitions vers tous les autres états, y compris vers eux-mêmes. Chaque transition est associée à sa probabilité d'être empruntée et cette probabilité peut éventuellement être nulle.

Un <i>modèle de Markov caché</i> est basé sur un modèle de Markov, sauf qu'on ne peut pas observer directement la séquence d'états : les états sont cachés. Chaque état émet des "observations" qui, elles, sont observables. On ne travaille donc pas sur la séquence d'états, mais sur la séquence d'observations générées par les états.
