<!-- Ajoutez ceci dans <head> -->
<script>
let panier = 0;

 
function ajouterAuPanier() {
    panier++;
    document.querySelector('#panier').innerHTML = `Panier (${panier})`;
}

+243977556498 l'événement à tous les boutons
document.querySelectorAll('.bouton').forEach(button => {
    button.addEventListener('click', ajouterAuPanier);
});
</script>
