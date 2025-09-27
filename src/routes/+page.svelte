<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Stop losing $15K per project to scheduling chaos"
	subtitle="Buffalo's trusted construction management experts deliver 25% cost reduction and faster project completion through streamlined coordination that eliminates costly delays."
	imageSrc="/generated/image-a-professional-construction-project-mana.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/turnerconstruction.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/skanska.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/clarkconstruction.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/gilbaneco.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Our expertise"
	text="CC Construction specializes in streamlined project management for Buffalo-area residential contractors, eliminating the scheduling conflicts and communication breakdowns that cost projects $15K or more. We combine deep local market knowledge with proven coordination processes to deliver faster completions and 25% cost reductions."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Rodriguez",
			position: "Project Manager",
			company: "Buffalo Valley Construction",
			quote:
				"CC Construction saved us $23,000 on our last residential project by eliminating scheduling conflicts between our electrical and plumbing teams. Their coordination system cut our project timeline from 8 weeks to 6 weeks.",
			image: "/generated/image-professional-headshot-of-marcus-rodrigue.webp"
		},
		{
			name: "Amanda Chen",
			position: "Senior Project Coordinator",
			company: "Western NY Builders",
			quote:
				"Before CC Construction, we were losing an average of $18,500 per project to delays and rework. Their streamlined management process has reduced our change orders by 40% and improved our profit margins significantly.",
			image: "/generated/image-professional-headshot-of-amanda-chen-fem.webp"
		},
		{
			name: "David Thompson",
			position: "Operations Manager",
			company: "Niagara Construction Group",
			quote:
				"The communication breakdowns that used to plague our multi-trade projects are gone. CC Construction's coordination reduced our average project completion time by 3 weeks and eliminated costly overtime charges.",
			image: "/generated/image-professional-headshot-of-david-thompson-.webp"
		}
	]}
/>

<Features
	title="Why construction managers choose CC Construction"
	subtitle="Built for Buffalo contractors who demand results"
	features={[
		{
			title: "Guaranteed 25% cost reduction",
			description:
				"Our proven coordination system eliminates the scheduling conflicts and communication breakdowns that drain project budgets."
		},
		{
			title: "Faster project completion",
			description:
				"Streamlined trade coordination and local Buffalo expertise deliver on-time completion when others fall behind schedule."
		},
		{
			title: "Local regulatory expertise",
			description:
				"Deep knowledge of Buffalo building codes and permit processes prevents costly delays that out-of-town firms can't navigate."
		},
		{
			title: "Real-time project visibility",
			description:
				"Advanced tracking tools give project managers complete oversight of every trade, timeline, and milestone across multiple sites."
		},
		{
			title: "Trusted contractor network",
			description:
				"Pre-vetted Buffalo-area trades and suppliers eliminate the risk of unreliable partners that derail construction schedules."
		},
		{
			title: "Communication that works",
			description:
				"Clear, consistent updates between all stakeholders prevent the misunderstandings that turn minor issues into major problems."
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Stop losing margin to miscommunication and delays"
	subtitle="Start building smarter"
	description="Talk to CC Construction today and finish your next project faster—with less stress and 25% lower costs. Buffalo's trusted construction management experts eliminate the scheduling chaos that costs you $15K+ per project."
	imageSrc="/generated/image-a-professional-construction-project-mana.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Get Started",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Schedule Consultation",
			variant: "secondary"
		}
	]}
/>
