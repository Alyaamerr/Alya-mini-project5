<script>
    import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';
    import Footer from '$lib/Footer.svelte';

    let myInfo = {
   	 title: 'Info',
   	 item1: 'Lee Kah Fai',
   	 item2: 14,
   	 item3: 'SMJK (C) Chung Ling'
    };

	let hobby = {
   	 title: 'Hobby',
   	 item1: 'Playing piano',
   	 item2: 'Cooking',
   	 item3: 'Play badminton'
    };

	let personality = {
   	 title: 'Personality',
   	 item1: 'Quiet',
   	 item2: 'Humble',
   	 item3: 'Kind'
    };
</script>

<Header title="My Biography" />

<Section {...myInfo} />
<Section {...hobby} />
<Section {...personality} />

<Footer gitHub="https://github.com/jaydontelebort/mini-project-5" />
