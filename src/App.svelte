<script>
	import FeedbackList from "./components/FeedbackList.svelte";

	let feedback = [
		{
			id: 1,
			rating: 9.5,
			author: "Sir Lewis Hamilton",
			text: "When I was a kid I had all the books, all the videos. Ayrton was the driver I looked up to, way before I even started racing. He inspired me to be a driver.",
		},
		{
			id: 2,
			rating: 6.0,
			author: "Sir Frank Williams",
			text: "Ayrton knew what he wanted and he knew of the various people inside the company who could deliver, and he went after those guys and got them onside.",
		},
		{
			id: 3,
			rating: 6.5,
			author: "Bernie Ecclestone",
			text: "The trouble with asking for good memories of Ayrton is that I do not have any bad ones. Perhaps my very vivid meories are of his strong opinon, and most of the time he was right.",
		},
		{
			id: 4,
			rating: 7.0,
			author: "Adrian Newey",
			text: "There was an aura about him, something that's difficult to describe. He certainly had a presence.",
		},
		{
			id: 5,
			rating: 8.0,
			author: "Bruno Senna",
			text: "Ayrton was definitely very determined on the track. He wouldn't let anything get in way, let's put it like that. He knew he had the ability, the opportunity, and that he wanted it more than the other guys.",
		},
		{
			id: 6,
			rating: 6.0,
			author: "Nigel Mansell",
			text: "Ayrton was our toughest rival. He would leave no stone unturned to get the utmost our of his car and his team",
		},
		{
			id: 7,
			rating: 8.0,
			author: "Damon Hill",
			text: "The Japanese and the Brazilians saw him as a god. His passion was undeniable and I sincerely believe he wanted to make the world a better place.",
		},
		{
			id: 8,
			rating: 7.5,
			author: "Alain Prost",
			text: "When peaople ask me who was the best driver I raced against, I say, Senna, by a long way.",
		},
		{
			id: 9,
			rating: 9.0,
			author: "Michael Schumacher",
			text: "I had one hero, his name is Ayrton Senna.",
		},
		{
			id: 10,
			rating: 10.0,
			author: "Gerhard Berger",
			text: "He had this special charisma what you cannot describe. We had a really good time. And you know, when I was racing for him... I realised then how outstanding he was. But I was not that kind of jealous... I just said, 'Whatever. It's up to me to get better, to improve myself to beat him.' And I think he understood immediately that we would be playing a fair game when we're competing with each other. And so we had room for friendship. And, I mean a great great friendship over the years.",
		},
		{
			id: 11,
			rating: 10.0,
			author: "Mauricio Gugelmin",
			text: "Becão was a generous guy. He was very fun with those close to him. He liked kidding around, but this side of his personality remained hidden, because most people only got to know Senna the driver, the serious, dedicated, super professional man who left everyone in awe of his talent on the track.",
		},
		{
			id: 12,
			rating: 10.0,
			author: "Thierry Boutsen",
			text: "He was exceptional. He was a superlative driver, better than any other. He had that extra skill. I don't see anyone today with that level of skill. If he raced today, no one would be able to beat him.",
		},
	]
</script>

<main>
	<FeedbackList {feedback}/>
</main>
<style></style>