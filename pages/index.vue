<template>
  <div>Bienvenue. C'est vide oui.. nous sommes entrain de travailler !


    <div>
      <nuxt-link to="/cgu/conditions-utilisations">
        <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
          Les conditions d'utilisations
        </button>
      </nuxt-link>
      <nuxt-link to="/cgu/politique-de-confidentialite">
        <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
          La politique de confidentialité
        </button>
      </nuxt-link>
    </div>
  </div>


</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
