<template>
  <a
    :class="{ active: activePage == index }"
    aria-current="page"
    :href="page.link.url"
    :title="`This link goes to ${page.link.text} page`"
    @click.prevent="navLinkClick(index)"
    class="nav-link"
    >{{ page.link.text }}</a
  >
</template>

<script></script>
