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
			title: "Prevention first",
			description: "We believe your healthiest years should be ahead of you, not behind you. By detecting conditions years before symptoms appear, we transform health from reactive to predictive."
		},
		{
			title: "Medical excellence",
			description: "Our Stanford, Harvard, and UCLA medical team brings world-class expertise to make advanced healthcare accessible to health-conscious professionals everywhere."
		},
		{
			title: "Data-driven longevity",
			description: "Through comprehensive biomarker analysis and biological age tracking, we empower members to optimize their health with precision and confidence."
		}
	];
</script>

<SecondaryHero
	title="Predict, prevent, thrive"
	subtitle="We believe your healthiest years shouldn't be behind you—they should be ahead of you"
	imageSrc="/mockups/dark-screen-1756550728937.png"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We watched too many friends and family members discover serious health conditions too late. Despite eating well, exercising, and doing everything right, they were blindsided by diagnoses that could have been prevented with early detection. The traditional healthcare system, brilliant as it is, only springs into action after problems develop—leaving the most health-conscious among us feeling helpless about their future.",
		"That's why we assembled a world-class team of longevity physicians from Stanford, Harvard, and UCLA to transform how we approach health. By combining cutting-edge medical expertise with advanced AI and comprehensive biomarker analysis, we created the world's first truly predictive health platform. What once required $100,000 visits to exclusive concierge clinics is now accessible to anyone who refuses to wait for symptoms to appear.",
		"Today, Superpower empowers thousands of health-conscious professionals to take control of their biological destiny. Our members don't just know their cholesterol levels—they track their biological age, detect early signs of 1,000+ conditions, and receive personalized protocols to optimize their longevity. We're not just changing healthcare; we're giving people the power to add healthy years to their lives, turning the dream of disease prevention into daily reality."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Medical Advisory Team Section -->
<StakeholderGrid
	stakeholderType="team"
	title="World-class medical expertise."
	subtitle="Leading physicians from Stanford, Harvard, and UCLA."
	stakeholders={[
		{
			name: "Dr. Anant Vinjamoori",
			position: "Chief Longevity Officer",
			bio: "Harvard MD & MBA with expertise in preventive and personalized medicine.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Dr. Leigh Erin Connealy",
			position: "Medical Advisor",
			bio: "Clinician & Founder of The Centre for New Medicine, pioneer in integrative oncology.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Dr. Molly Maloof",
			position: "Longevity Physician",
			bio: "Stanford Professor specializing in personalized medicine and health optimization.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Dr. Abe Malkin",
			position: "Medical Director",
			bio: "Founder and Medical Director of Concierge MD with expertise in preventive care.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Dr. Robert Lufkin",
			position: "Medical Advisor",
			bio: "UCLA Medical Professor and NYT Bestselling Author in metabolic health.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Your healthiest years are ahead of you"
	subtitle="Start your health journey today"
	description="Join thousands of health-conscious professionals who've discovered their biological age, detected early health risks, and optimized their longevity with our world-class medical team."
	imageSrc="https://www.unc.mn/image-placeholder.svg"
	callsToAction={[
		{
			href: "/",
			label: "Get your health analysis",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Meet our medical team",
			variant: "secondary"
		}
	]}
/>
