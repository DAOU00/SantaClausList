<template>
    <footer class="footer">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <h5 class="mb-4">Informations de contact</h5>
            <p>Adresse: 123 Rue de la Vue, Ville, Pays</p>
            <p>Téléphone: +123 456 789</p>
            <p>Email: info@monsite.com</p>
          </div>
          <div class="col-md-6">
            <h5 class="mb-4">Liens utiles</h5>
            <ul class="list-unstyled">
              <li><a href="#" class="text-dark">Accueil</a></li>
              <li><a href="#" class="text-dark">À propos</a></li>
              <li><a href="#" class="text-dark">Services</a></li>
              <li><a href="#" class="text-dark">Contact</a></li>
            </ul>
          </div>
        </div>
      </div>
      <div class="text-center py-3" style="background-color: rgba(0, 0, 0, 0.2);">
        <p class="mb-0 text-muted">© {{ new Date().getFullYear() }} MonSite.com. Tous droits réservés.</p>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'Footer',
  };
  </script>
  
  <style scoped>
  /* Votre style existant pour le composant de pied de page */
  </style>
  