<script setup lang="ts">
import ListBlock from '@/components/ListBlock.vue';
</script>

<template>
  <ListBlock title="Add a feature or fix a bug directly">
    <p style="text-indent: 20px;">
      Cosmo is open-source, so you can go in and look at and modify the code for yourself. This means that if you find a bug or want a feature, you can just do it yourself! Of course this doesn't mean I won't, but it's always helpful to have people contributing. Speaking of, if you contribute you will get a Contributor role in my Discord server, as well as your name (with your GitHub linked) and what you contributed to Cosmo on it's README.
    </p>
    <p style="text-indent: 20px;">
      If you want to learn how you can create things for Cosmo, we have a section of documentation <a class="nice-hl" href="https://docs.cosmo-lang.dev">here</a> describing how, though it is minimal. In the future all documentation you might ever need will be at the Docs page of this site. If you have any questions extending the scope of what's documented, please feel free to ask! You can find Cosmo's repository on the <router-link class="nice-hl" to="/">Home</router-link> page.
    </p>
    <p>
      Remember that Cosmo isn't just the language! You can also help by contributing to:
      <ul>
        <li>
          <a class="nice-hl" href="https://github.com/cosmo-lang/stars">Stars</a> + <a class="nice-hl" href="https://github.com/cosmo-lang/stars-api">it's API</a>
        </li>
        <li>
          <a class="nice-hl" href="https://github.com/cosmo-lang/cosmo-installer">The installer</a>
        </li>
        <li>
          <a class="nice-hl" href="https://github.com/cosmo-lang/vscode-cosmo">The VSC extension</a>
        </li>
        <li>
          And <a class="nice-hl" href="https://github.com/cosmo-lang/website">the website</a>.
        </li>
      </ul>
    </p>
  </ListBlock>
  <ListBlock title="Updates, questions, discussions, and more">
    <p style="text-indent: 20px;">
      If you're unsure about anything, need to know where to find something, are interested in what's changing with Cosmo, want to talk about Cosmo, want to share your Cosmo projects, or anything else of that nature, <a class="nice-hl" href="https://discord.gg/WHyHh39dwh">our Discord server</a> is the place to do it. We also have a bot that you can execute Cosmo code with, no installation necessary.
    </p>
  </ListBlock>
</template>