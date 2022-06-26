<template>
  <div class="home">
    <section>
      <div>
        <h1 class="text-gray-500 font-bold text-3xl text-center p-2 mt-6">Welcome Coders</h1>
      </div>
      <div class="intro text-gray-500 text-center mt-6">
        <p class="text-lg">Wigan Coders Meet-up is an event that takes place on Saturday mornings at <span
            class="text-blue-800 font-bold">Wigan Library</span>.</p>
        <p class="text-lg">We are a community of profesional developers here to help you start that journey into learning how to code.
        </p>
      </div>
    </section>

    <section>
      <div class="hero-content p-4 flex flex-col lg:flex-row items-center mx-auto mt-0 lg:mt-10">
        <div class="image p-4 mt-0 lg:mt-8 lg:w-6/12">
          <img src="../assets/hero-image.jpg" class="rounded-lg w-full" width="600" height="200" alt="">
        </div>
        <div class="questions mt-10 w-full lg:w-6/12">
          <ol class="text-center mb-10">
            <li class="text-2xl p-2 my-4"><p>Why even learn how to code?</p></li>
            <li class="text-2xl p-2 my-4"><p>What is coding anyway?</p></li>
            <li class="text-2xl p-2 my-4"><p>What can I use coding for?</p></li>
            <li class="text-2xl p-2 my-4"><p>How do I get started?</p></li>
          </ol>
          <div>
            <p class="text-center">If you have ever asked yourself any of these questions, or want to know more about what learning how to code can do for you, then ask no further. We are here to help you understand what coding is and how learning it can change your life for the better.</p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
  }
}
</script>

<style>
</style>
