<script>
    import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';
    import Footer from '$lib/Footer.svelte';

    let myInfo = {
   	 title: 'Info',
   	 item1: 'Nur Alya Sofia Amerrudin',
   	 item2: 20,
   	 item3: 'UITM Merbok'
    };

	let hobby = {
   	 title: 'Hobby',
   	 item1: 'Swimming',
   	 item2: 'Cooking',
   	 item3: 'Play badminton'
    };

	let personality = {
   	 title: 'Personality',
   	 item1: 'Happy go lucky',
   	 item2: 'Humble',
   	 item3: 'Kind'
    };
</script>

<Header title="My Biography" />

<Section {...myInfo} />
<Section {...hobby} />
<Section {...personality} />

<Footer gitHub="https://github.com/Alyaamerr/Alya-mini-project5" />
