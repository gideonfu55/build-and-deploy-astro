---
layout: ../layouts/BasicPage.astro
setup: | 
    import Card from '../Components/Card.astro'
    import Counter from '../Components/Counter.svelte'
title: Basic Page
---

<Card title="Content-1">

Content here.

</Card>

## Title

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo eaque soluta optio impedit dolore hic, exercitationem, illum quasi quas corrupti repellendus, dicta voluptas labore cupiditate placeat quis atque distinctio modi?

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo eaque soluta optio impedit dolore hic, exercitationem, illum quasi quas corrupti repellendus, dicta voluptas labore cupiditate placeat quis atque distinctio modi?

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo eaque soluta optio impedit dolore hic, exercitationem, illum quasi quas corrupti repellendus, dicta voluptas labore cupiditate placeat quis atque distinctio modi?


<Card title="Content-2">

Content here.

</Card>

## Title

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo eaque soluta optio impedit dolore hic, exercitationem, illum quasi quas corrupti repellendus, dicta voluptas labore cupiditate placeat quis atque distinctio modi?

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo eaque soluta optio impedit dolore hic, exercitationem, illum quasi quas corrupti repellendus, dicta voluptas labore cupiditate placeat quis atque distinctio modi?

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo eaque soluta optio impedit dolore hic, exercitationem, illum quasi quas corrupti repellendus, dicta voluptas labore cupiditate placeat quis atque distinctio modi?

<Counter client:load />