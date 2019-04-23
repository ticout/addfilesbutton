# addfilesbutton
Ajouter plus de fichier uniquement si il existe un précedent
créer un input file avec des patterns si nécessaires / create input type="file" with pattern if needed
à la suite un span avec un lien/ after this, a span with a link inside
la référence du lien devra contenir le text "javascript:addFile()" et aura la classe hidden/ the link with reference "javascript:addFile()" and class="hidden"
dans l'input, associez la fonction qui fera afficher le lien ajouter un fichier de plus à l'évènement oninput / inside input add event, she call function for do visible link addfile
la fonction addfile récupère le dernier input, le copie, et le rajoute à la suite, sans oublier d'ajouter la class hidden au span/ Them function get the last input, clone, change name and value, and add after the last input, don't forget add class ="hidden" for span
vous n'oubliez pas non plus de limiter le nombre d'input/ don't forget limit quantity for upload
