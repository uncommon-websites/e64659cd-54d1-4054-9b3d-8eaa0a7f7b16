<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
	
	// Icons
	import IconEye from "~icons/lucide/eye";
	import IconActivity from "~icons/lucide/activity";
	import IconUserCheck from "~icons/lucide/user-check";
	import IconTrendingDown from "~icons/lucide/trending-down";
	import IconBrain from "~icons/lucide/brain";
	import IconClock from "~icons/lucide/clock";
</script>

<Hero
	title="Transform health from reactive to predictive"
	subtitle="Detect 1,000+ conditions years before symptoms appear through 100+ biomarkers analyzed by Stanford and Harvard medical experts."
	imageSrc="https://images.unsplash.com/photo-1559757148-5c350d0d3c56?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1931&h=1087&q=80"
	centered={false}
/>
<LogoScroller 
	label="Trusted by health-conscious teams at"
	logoUrls={[
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/spotify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/peloton.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Prevention over reaction"
	text="Superpower transforms health management from reactive to predictive by analyzing 100+ biomarkers annually to detect 1,000+ conditions years before symptoms appear. We serve health-conscious professionals aged 28-45 who want to prevent chronic disease and optimize longevity through data-driven insights backed by Stanford and Harvard medical expertise. At 90% cost reduction from traditional concierge medicine, we make premium preventive healthcare accessible to everyone seeking to improve their biological age and life outcomes."
/>

<Testimonials
	testimonials={[
		{
			name: "Dr. Priya Patel",
			position: "Director of Wellness",
			company: "Meta",
			quote:
				"Superpower detected my pre-diabetic markers 3 years before my annual physical would have caught them. The $199 membership saved me thousands in potential medical costs and gave me time to reverse course naturally.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Marcus Williams",
			position: "VP of Engineering",
			company: "Stripe",
			quote:
				"As someone who works 70-hour weeks, I needed health insights that fit my schedule. Superpower's at-home testing and AI-driven recommendations helped me optimize my biomarkers while maintaining my demanding career.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Isabella Rodriguez",
			position: "Founder & CEO",
			company: "Wellness Collective",
			quote:
				"The Stanford medical team caught elevated inflammation markers that traditional doctors missed. Their personalized protocol reduced my biological age by 4 years in just 8 months - completely transformed how I approach longevity.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<Features
	title="Advanced health intelligence"
	subtitle="Transform your health journey with predictive insights that prevent problems before they start"
	features={[
		{
			title: "Predictive health detection",
			description: "Identify 1,000+ conditions years before symptoms appear through comprehensive biomarker analysis that catches what traditional medicine misses.",
			icon: IconEye,
			iconClass: "text-brand-primary"
		},
		{
			title: "100+ biomarkers in one test",
			description: "Get complete health visibility from a single blood draw, eliminating the need for multiple appointments and fragmented testing.",
			icon: IconActivity,
			iconClass: "text-brand-primary"
		},
		{
			title: "Stanford and Harvard expertise",
			description: "Access world-class medical professionals from top institutions with 24/7 availability for personalized health guidance and support.",
			icon: IconUserCheck,
			iconClass: "text-brand-primary"
		},
		{
			title: "90% cost reduction",
			description: "Receive premium concierge-level healthcare services at a fraction of traditional costs while maintaining the highest quality standards.",
			icon: IconTrendingDown,
			iconClass: "text-brand-primary"
		},
		{
			title: "AI-powered insights",
			description: "Transform complex health data into actionable recommendations through advanced AI that learns your unique biological patterns and optimization opportunities.",
			icon: IconBrain,
			iconClass: "text-brand-primary"
		},
		{
			title: "Biological age tracking",
			description: "Monitor your true biological age over time and receive personalized protocols to reverse aging markers and optimize longevity.",
			icon: IconClock,
			iconClass: "text-brand-primary"
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Don't wait for symptoms to appear"
	subtitle="Join 50,000+ professionals taking control of their health"
	description="Your health is your most valuable asset, yet traditional medicine waits for problems to develop. With Superpower, you get 100+ biomarkers analyzed by Stanford and Harvard medical experts for just $199/year—compared to $10,000+ at concierge clinics. Detect conditions years early, optimize your biological age, and invest in the one thing that improves every aspect of your life: your health."
	imageSrc="https://images.unsplash.com/photo-1560472354-b33ff0c44a43?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1426&h=1778&q=80"
	callsToAction={[
		{
			href: "https://getsuperpower.com",
			label: "Start your health transformation",
			variant: "primary"
		},
		{
			href: "https://getsuperpower.com/about",
			label: "Meet our medical team",
			variant: "secondary"
		}
	]}
/>
