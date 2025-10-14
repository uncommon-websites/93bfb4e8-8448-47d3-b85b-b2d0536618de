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
	title="Build custom tools instantly, without waiting on engineering"
	subtitle="Operations teams at Series A-C startups use qavo to ship workflows in hours, not months."
	imageSrc="/generated/image-operations-manager-standing-and-smiling-.webp"
	centered={false}
	callsToAction={[
		{
			href: "/contact",
			label: "Get started"
		},
		{
			href: "/about",
			label: "Learn more"
		}
	]}
/>
<LogoScroller
	label="Trusted by operations teams"
	logoUrls={[
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/intercom.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/segment.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="qavo is an AI-powered operations platform that lets teams build custom internal tools instantly, without engineering dependencies. Operations managers at Series A-C startups use qavo to ship workflows that once took months in just hours, eliminating backlogs and scaling processes at the speed of business. We give ops teams the agency to create exactly what they need, when they need it."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Sharma",
			position: "Director of Operations",
			company: "Velocity Labs",
			quote:
				"We went from waiting 3 months for engineering resources to shipping custom compliance workflows in 4 hours. qavo gave our ops team the autonomy we desperately needed.",
			image: "/generated/image-professional-headshot-of-an-indian-woman.webp"
		},
		{
			name: "Marcus Chen",
			position: "Compliance Manager",
			company: "TrustCore",
			quote:
				"The enterprise-grade security controls and audit trails satisfied our CTO's governance requirements immediately. We eliminated the risk of shadow IT while moving 10x faster.",
			image: "/generated/image-professional-headshot-of-an-asian-man-bu.webp"
		},
		{
			name: "Elena Rodriguez",
			position: "Head of Operations",
			company: "Streamline Inc",
			quote:
				"We scaled from 50 to 200 people without adding a single engineer to build internal tools. qavo saved us $400K in engineering costs while accelerating our operations velocity.",
			image: "/generated/image-professional-headshot-of-a-hispanic-woma.webp"
		}
	]}
/>

<Features
	title="Built for operations teams who refuse to wait"
	subtitle="Ship custom tools in hours with AI-powered automation that eliminates engineering dependencies while maintaining enterprise-grade security."
	features={[
		{
			title: "AI-powered tool builder",
			description:
				"Describe what you need in plain language and watch qavo generate custom tools instantly. No code, no tickets, no waiting on engineering sprints."
		},
		{
			title: "Zero engineering dependencies",
			description:
				"Operations teams build, deploy, and iterate on their own workflows without touching the engineering backlog. Your team gets the agency to move fast while engineering focuses on core product."
		},
		{
			title: "Enterprise security that CTOs approve",
			description:
				"Built-in audit trails, role-based permissions, and SOC 2 compliance give your CTO confidence while you maintain the speed to execute."
		},
		{
			title: "Build your way",
			description:
				"Choose AI generation for instant results or use the intuitive visual builder for precise control. Switch between methods whenever your workflow demands it."
		},
		{
			title: "Automate compliance workflows",
			description:
				"Transform manual compliance processes into automated workflows that capture every action, maintain perfect audit trails, and scale effortlessly."
		},
		{
			title: "Connect everything",
			description:
				"Integrate with your entire tech stack through pre-built connectors and APIs. Pull data from anywhere, push updates everywhere, all without engineering help."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop waiting on engineering"
	subtitle="Build custom tools instantly"
	description="Your ops team deserves the agency to ship workflows without engineering dependencies. qavo gives you AI-powered automation with enterprise-grade security that your CTO will approve. No more months-long backlogs—just instant results."
	imageSrc="/generated/image-a-confident-operations-manager-sitting-a.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Get started",
			variant: "primary"
		},
		{
			href: "/about",
			label: "See how it works"
		}
	]}
/>
