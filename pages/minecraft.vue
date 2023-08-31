<template>
  <Head>
    <Title>MC - Doksakura</Title>
  </Head>
  <div class="px-10">
    <section>
      <nav class='py-10 mb-12 flex justify-between'>

        <h1 class='text-md'>Minecraft Server</h1>

        <ul class='flex items-center animate-bounce'>
          <li class="font-bold">
            IP: vault.doksakura.com:30812
          </li>
        </ul>
      </nav>

      <div class='relative mx-auto bg-gradient-to-b from-teal-500 rounded-full w-80 h-80 overflow-hidden'>
        <img class='mx-auto' src='/images/minecraft_logo.png' />
      </div>
      <div class='text-center p-10'>
        <h2 class='text-5xl py-2 text-teal-600 font-medium mx-auto'>All In One Minecraft Server</h2>
        <h3 class='text-2xl py-2 text-green-500 animate-pulse'>Status: Online (1.20.1)</h3>
        <p class='text-md py-5 leading-8 text-gray-800'>
          A Minecraft server perform with java plugins and node.js. We provide the automatic start and stop depent on
          players join and left.
        </p>
      </div>
    </section>

    <section class='lg:flex gap-10 justify-center'>
      <div class='text-center shadow-lg p-10 rounded-xl'>
        <img class='mx-auto' src="/images/code.png" width="100" height="100" />
        <h3 class='text-lg font-medium pt-8 pb-2'>Auto Start and Stop</h3>
        <p class='py-5'>
          On stand by mode, you can start a minecraft server with your click
        </p>
        <p>
          On empty, minecraft server will be stoped within 15 minutes
        </p>
      </div>
      <div class='text-center shadow-lg p-10 rounded-xl'>
        <img class='mx-auto' src="/images/design.png" width="100" height="100" />
        <h3 class='text-lg font-medium pt-8 pb-2'>Variety of Minigames</h3>
        <p>
          We provide the well-known minigames from worldwide
        </p>
      </div>
    </section>
    <section class='flex justify-center'>
      <div class='text-center'>
        <h3 class='text-3xl py-1 mt-5'>Contact Me</h3>
        <h4>contact@doksakura.com</h4>
      </div>
    </section>
  </div>
</template>