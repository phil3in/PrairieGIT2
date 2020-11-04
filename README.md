# PrairieGIT2
On re-commence le Brief de zéro, en groupe

### Merge
Je ne vois pas de trace de merge sur Github, pourtant j'ai fait plusieurs essais. Notamment, j'ai créé un nouveau fichier texte sur Dev, puis ai fait une merge de la branche vers main. Apparemment avec succès puisque le fichier y est maintenant aussi, mais pas de trace de la merge elle-même.
En tout cas voici le code utilisé :
```phile@LAPTOP-T5E308LF MINGW64 ~/Simplon/dev-data/PrairieGIT2 (Dev)
$ git add fichieramerger.txt

phile@LAPTOP-T5E308LF MINGW64 ~/Simplon/dev-data/PrairieGIT2 (Dev)
$ git commit -m "Ajout fichier a merger"
[Dev 6796e5c] Ajout fichier a merger
 1 file changed, 1 insertion(+)
 create mode 100644 fichieramerger.txt

phile@LAPTOP-T5E308LF MINGW64 ~/Simplon/dev-data/PrairieGIT2 (Dev)
$ git push
Enter passphrase for key '/c/Users/phile/.ssh/id_rsa':
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 348 bytes | 174.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:phil3in/PrairieGIT2.git
   bcf16f8..6796e5c  Dev -> Dev

phile@LAPTOP-T5E308LF MINGW64 ~/Simplon/dev-data/PrairieGIT2 (Dev)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

phile@LAPTOP-T5E308LF MINGW64 ~/Simplon/dev-data/PrairieGIT2 (main)
$ git merge Dev
Updating bcf16f8..6796e5c
Fast-forward
 fichieramerger.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 fichieramerger.txt

phile@LAPTOP-T5E308LF MINGW64 ~/Simplon/dev-data/PrairieGIT2 (main)
$ git commit -m "Fichier a ete merge"
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

phile@LAPTOP-T5E308LF MINGW64 ~/Simplon/dev-data/PrairieGIT2 (main)
$ git push
Enter passphrase for key '/c/Users/phile/.ssh/id_rsa':
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:phil3in/PrairieGIT2.git
   bcf16f8..6796e5c  main -> main
phile@LAPTOP-T5E308LF MINGW64 ~/Simplon/dev-data/PrairieGIT2 (main)```
