<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Local expertise",
			description: "Deep understanding of Buffalo's unique construction landscape, regulations, and market dynamics."
		},
		{
			title: "Efficient processes",
			description: "Streamlined project management that eliminates costly scheduling conflicts and communication breakdowns."
		},
		{
			title: "Proven results",
			description: "Consistently delivering projects faster while reducing costs by 25% through optimized workflows."
		}
	];
</script>

<SecondaryHero
	generating
	title="Solving world hunger"
	subtitle="one step at a time"
	imageSrc="https://www.unc.mn/image-placeholder.svg"
/>

<!-- Story Section -->
<Story
	generating
	paragraphs={[
		"We started in 2018 with a simple goal: make helpful tech that people actually need. While many chase profits, we chose to do things differently.",
		"Beyond making good products, we care about doing the right thing, being kind to our planet, and making sure everyone can use what we build. That's our compass.",
		"From day one, we've asked ourselves: 'Does this actually help people?' This question gets us through tough calls and shapes who we are. We're playing the long game here.",
		"We think about how our work affects real people's lives. We build tech that brings people together, keeps your information safe, and treats everyone fairly. When we stick to these basics, good things happen."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our founders."
	subtitle="Local Buffalo expertise driving construction excellence."
	stakeholders={[
		{
			name: "Viviana Castillo",
			position: "Owner",
			bio: "Bringing years of construction industry experience and deep understanding of Buffalo's unique market dynamics to deliver exceptional project outcomes.",
			image: "/generated/image-professional-headshot-of-a-hispanic-woma.webp"
		},
		{
			name: "Christian Castillo",
			position: "Owner",
			bio: "Focused on streamlining construction management processes and building strong relationships with local contractors across the Buffalo area.",
			image: "/generated/image-professional-headshot-of-a-hispanic-man-.webp"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Start your next project"
	subtitle="with local Buffalo expertise"
	description="Join the contractors already saving $15K+ per project through streamlined management and faster completion times."
	imageSrc="/generated/image-a-cheerful-construction-project-manager-.webp"
/>
