---
# try also 'default' to start simple
theme: geist
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: ''
colorSchema: 'auto'
download: /slides-export.pdf
# https://sli.dev/custom/highlighters.html
highlighter: prism
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Building a Portfolio Website with Next.js

  by Sage Abdullah
---

# Building a Portfolio Website with Next.js

Sage Abdullah

<div class="flex m-6 gap-2 abs-br">
  <a target="_blank" rel="noreferrer noopener nofollow" href="https://github.com/laymonage/slides-portfolio-nextjs" alt="GitHub"
    class="text-xl opacity-50 icon-btn !border-none">
    <carbon-logo-github />
  </a>
</div>


<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# About Me

<br />

- 🌏 Open source enthusiast
- 🧑‍💻 Software Engineer at GudangAda
- 🌞 Google Summer of Code 2019 with Django
- 🌱 Developer Student Clubs -- Universitas Indonesia 2019 Lead
- 🧑‍🎓 CSUI 2017

<br />

More at [laymonage.com/about](https://laymonage.com/about)

<div class="flex m-6 gap-2 abs-br">
  <a target="_blank" rel="noreferrer noopener nofollow" href="https://github.com/laymonage" alt="GitHub"
    class="text-xl opacity-50 icon-btn !border-none">
    <carbon-logo-github />
  </a>
  <a target="_blank" rel="noreferrer noopener nofollow" href="https://linkedin.com/in/laymonage" alt="LinkedIn"
    class="text-xl opacity-50 icon-btn !border-none">
    <carbon-logo-linkedin />
  </a>
  <a target="_blank" rel="noreferrer noopener nofollow" href="https://twitter.com/laymonage" alt="Twitter"
    class="text-xl opacity-50 icon-btn !border-none">
    <carbon-logo-twitter />
  </a>
</div>

---

# Background

<br />

<v-clicks>

- The internet is a vast space, full of people.
- How can others find **you**?
- How can others find **your work**?

</v-clicks>

---

# Portfolio

<div grid="~ gap-4 cols-2">
<div>

<br />

<v-clicks>

- Your **home** on the internet.
- Where people can find **you** and **your work**.

</v-clicks>
</div>

<div v-click grid="~ gap-1 cols-2 rows-2" class="max-h-sm">
<a class="h-full" target="_blank" rel="noreferrer noopener nofollow" href="https://leerob.io"><img class="h-full" src="/leerob-io.png" alt="leerob.io"/></a>
<a class="h-full" target="_blank" rel="noreferrer noopener nofollow" href="https://cassidoo.co"><img class="h-full" src="/cassidoo-co.png" alt="cassidoo.co"/></a>
<a class="h-full" target="_blank" rel="noreferrer noopener nofollow" href="https://kentcdodds.com"><img class="h-full" src="/kentcdodds-com.png" alt="kentcdodds.com"/></a>
<a class="h-full" target="_blank" rel="noreferrer noopener nofollow" href="https://katherinempeterson.com"><img class="h-full" src="/katherinempeterson-com.png" alt="katherinempeterson.com"/></a>
</div>

</div>

---

# Why?

<div grid="~ gap-4 cols-2">
<div>

<br/>

<v-clicks>

- Show your background
- Prove that you have the know-how
- Convey your creativity and dedication
- Strengthen your personal branding
- Stand out among others

</v-clicks>
</div>

<div grid="~ gap-1 cols-2 rows-2" class="max-h-sm">
<a class="h-full" target="_blank" rel="noreferrer noopener nofollow" href="https://leerob.io"><img class="h-full" src="/leerob-io.png" alt="leerob.io"/></a>
<a class="h-full" target="_blank" rel="noreferrer noopener nofollow" href="https://cassidoo.co"><img class="h-full" src="/cassidoo-co.png" alt="cassidoo.co"/></a>
<a class="h-full" target="_blank" rel="noreferrer noopener nofollow" href="https://kentcdodds.com"><img class="h-full" src="/kentcdodds-com.png" alt="kentcdodds.com"/></a>
<a class="h-full" target="_blank" rel="noreferrer noopener nofollow" href="https://katherinempeterson.com"><img class="h-full" src="/katherinempeterson-com.png" alt="katherinempeterson.com"/></a>
</div>

</div>

<style>
  ul {
    list-style: disc;
  }
</style>

---

# Where to start?

<div grid="~ gap-16 cols-3 rows-2" class="items-center max-h-sm">
<a class="flex max-h-full p-8" target="_blank" rel="noreferrer noopener nofollow" href="https://jekyllrb.com"><img src="/jekyll.png" class="max-h-full" /></a>
<a class="flex max-h-full p-8" target="_blank" rel="noreferrer noopener nofollow" href="https://gohugo.io"><img src="/hugo.svg" class="max-h-full" /></a>
<a class="flex max-h-full p-8" target="_blank" rel="noreferrer noopener nofollow" href="https://nextjs.org"><img src="/next.svg" class="max-h-full filter invert dark:invert-0" /></a>
<a class="flex max-h-full p-8" target="_blank" rel="noreferrer noopener nofollow" href="https://gatsby.com"><img src="/gatsby.svg" class="max-h-full" /></a>
<a class="flex max-h-full p-8" target="_blank" rel="noreferrer noopener nofollow" href="https://gridsome.org"><img src="/gridsome.svg" class="max-h-full" /></a>
<a class="flex max-h-full p-8" target="_blank" rel="noreferrer noopener nofollow" href="https://nuxtjs.org"><img src="/nuxt.svg" class="max-h-full" /></a>
</div>

---
preload: false
---

# Static vs. Dynamic Website

<div grid="~ gap-4 cols-2">
<div>

<br />

<v-clicks>

## Static

</v-clicks>

<v-clicks>

- ➕ Blazing fast
- ➕ Quick to develop
- ➕ Cheap and easier to host

- ➖ Can't be tailored to individual visitors
- ➖ Functionalities limited by client and premade assets
- ➖ Unable to store external API secrets

</v-clicks>

</div>

<div>

<br />

<v-clicks>

## Dynamic

</v-clicks>

<v-clicks>

- ➕ Can provide tailored experience
- ➕ More powerful and flexible
- ➕ Allows secure authentication for external APIs

- ➖ Slower compared to static websites
- ➖ Require knowledge of backend programming
- ➖ Expensive and harder to host

</v-clicks>

</div>
</div>

---

# Next.js

"The React Framework for Production"

<v-clicks>

Allows pre-rendering in two forms:

</v-clicks>

<ul class="pl-8 list-disc">
  <li v-click><a target="_blank" rel="noreferrer noopener nofollow" href="https://nextjs.org/docs/basic-features/pages#static-generation-recommended">Static Site Generation (SSG)</a></li>
  <li v-click><a target="_blank" rel="noreferrer noopener nofollow" href="https://nextjs.org/docs/basic-features/pages#server-side-rendering">Server Side Rendering (SSR)</a></li>
</ul>

<v-clicks>

Best of both worlds!

In addition...

</v-clicks>

<ul class="pl-8 list-disc">
  <li v-click><a target="_blank" rel="noreferrer noopener nofollow" href="https://nextjs.org/docs/api-routes/introduction">API Routes</a></li>
  <li v-click><a target="_blank" rel="noreferrer noopener nofollow" href="https://nextjs.org/docs/basic-features/data-fetching#incremental-static-regeneration">Incremental Static Regeneration (ISR)</a></li>
</ul>

---

# Pre-rendering

<div grid="~ gap-8 cols-2">

![No pre-rendering](https://nextjs.org/static/images/learn/data-fetching/no-pre-rendering.png)

![pre-rendering](https://nextjs.org/static/images/learn/data-fetching/pre-rendering.png)


</div>

See [nextjs.org/learn/basics/data-fetching/pre-rendering](https://nextjs.org/learn/basics/data-fetching/pre-rendering)

---

# Two Forms of Pre-rendering

<div grid="~ gap-8 cols-2">

![Static Generation](https://nextjs.org/static/images/learn/data-fetching/static-generation.png)

![Server-side Rendering](https://nextjs.org/static/images/learn/data-fetching/server-side-rendering.png)

</div>

See [https://nextjs.org/learn/basics/data-fetching/two-forms](https://https://nextjs.org/learn/basics/data-fetching/two-forms)

---

# Per-page Basis

<div class="w-full">
<img class="max-h-xs mx-auto" src="https://nextjs.org/static/images/learn/data-fetching/per-page-basis.png" />
</div>

See [https://nextjs.org/learn/basics/data-fetching/two-forms](https://https://nextjs.org/learn/basics/data-fetching/two-forms)

---

# Static Generation without Data

<div class="w-full">
<img class="max-h-xs mx-auto" src="https://nextjs.org/static/images/learn/data-fetching/static-generation-without-data.png" alt="Static Generation without Data" />
</div>

See [https://nextjs.org/learn/basics/data-fetching/with-data](https://https://nextjs.org/learn/basics/data-fetching/with-data)

---

# Static Generation with Data

<div class="w-full">
<img class="max-h-xs mx-auto" src="https://nextjs.org/static/images/learn/data-fetching/static-generation-with-data.png" alt="Static Generation with Data" />
</div>

See [https://nextjs.org/learn/basics/data-fetching/with-data](https://https://nextjs.org/learn/basics/data-fetching/with-data)

---

# `getStaticProps`

<br />

```js
export default function Home(props) { ... }

export async function getStaticProps() {
  // Get external data from the file system, API, DB, etc.
  const data = ...

  // The value of the `props` key will be
  //  passed to the `Home` component
  return {
    props: ...
  }
}
```

<style>
  h1 code {
    @apply text-3xl;
  }
</style>

---

# Example: Blog Data

<div class="w-full">
<img class="max-h-xs mx-auto" src="https://nextjs.org/static/images/learn/data-fetching/index-page.png" alt="getStaticProps for blog data" />
</div>

See [https://nextjs.org/learn/basics/data-fetching/blog-data](https://https://nextjs.org/learn/basics/data-fetching/blog-data)

---

# Limitations?

<br/>

<v-clicks>

- Data is only "fetched" and rendered into the pages at **build time**.
- What if the data is constantly updated?

- Stale data! 😦

- Solution: fetch data at **request time**! 😄

</v-clicks>

---

# Server-side Rendering with Data

<div class="w-full">
<img class="max-h-xs mx-auto" src="https://nextjs.org/static/images/learn/data-fetching/server-side-rendering-with-data.png" alt="Server-side Rendering with Data" />
</div>

See [https://nextjs.org/learn/basics/data-fetching/request-time](https://https://nextjs.org/learn/basics/data-fetching/request-time)

---

# `getServerSideProps`

<br />

```js
export default function Home(props) { ... }

export async function getServerSideProps(context) {
  return {
    props: {
      // props for your component
    }
  }
}
```

<style>
  h1 code {
    @apply text-3xl;
  }
</style>

---

# Client-side Rendering?

<br/>

<v-clicks>

- Server-side rendering might be **costly**
- Data might **take a while** to be fetched
- Increase **responsiveness** of the page -> **client side rendering** 🤔

</v-clicks>

---

# Client-side Rendering

<div class="w-full">
<img class="max-h-xs mx-auto" src="https://nextjs.org/static/images/learn/data-fetching/client-side-rendering.png" alt="Client-side Rendering" />
</div>

See [https://nextjs.org/learn/basics/data-fetching/request-time](https://https://nextjs.org/learn/basics/data-fetching/request-time)

---

# More...

<br/>

<ul class="pl-8 list-disc">
  <li v-click><a target="_blank" rel="noreferrer noopener nofollow" href="https://nextjs.org/learn/basics/dynamic-routes">Dynamic Routes</a></li>
  <li v-click><a target="_blank" rel="noreferrer noopener nofollow" href="https://nextjs.org/docs/api-routes/introduction">API Routes</a></li>
  <li v-click><a target="_blank" rel="noreferrer noopener nofollow" href="https://nextjs.org/docs/basic-features/data-fetching#incremental-static-regeneration">Incremental Static Regeneration (ISR)</a></li>
</ul>

---

<div class="w-full text-center">

# Any questions?


<v-clicks>

### Next: **Next.js Hands-on**

</v-clicks>

</div>

---

<div class="w-full text-center">

# Thank you!

</div>

<br/>

- Slides available on [slides.laymonage.com/nextjs-portfolio](https://slides.laymonage.com/nextjs-portfolio)
- Slides source code available on [github.com/laymonage/slides-nextjs-portfolio](https://github.com/laymonage/slides-nextjs-portfolio)
- Made with [sli.dev](https://sli.dev)
- Content based on [nextjs.org/learn](https://nextjs.org/learn)

<div class="flex items-center justify-center h-sm max-h-full">

2021 · laymonage

</div>
