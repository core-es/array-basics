Jack: Hey, I'm `jack dawson`.

	const hero = ['jack', 'dawson'];

Rose: Hello jack,

	console.log(`Hello ${hero[0]}`);
	
Rose: This is `rose dewitt bukater`

	const heroine = ['rose', 'dewitt bukater'];

Jack: Hi rose,

	console.log(`Hello ${heroine[0]}`);

Jack: What are you doing?  
Rose: I'm having breakfast.

	const food = ['break Fast'];

Jack: then what next?  
Rose: he he. lunch

	food.push('lunch');

Jack: so you don't drink bed coffee?  
Rose: ofcourse my horse. yes i do that blunder.

	food.unshift('coffee');

Jack: OK then, Lets have drink with me in pantry, before you go to lunch?  
Rose: sure. why not.

	food.splice(2, 0, 'juice');

Jack: How is the Juice taste ?  
Rose: Juice was very good. whats your dinner plan ?  
Jack: hmmm. we can go to Mc. Donalds

	food.push('dinner');

Jack's Instinct of Him :D  

	food.push('beer');

Jack: Can i drop you. beer ?  
Rose: No thanks i can catch a train.

	food.pop();
	
Jack: Anyways, Happy Weekend. enjoy your tomorrows bed coffee.  
Rose: Nope, will not drink bed coffee from tomorrow is a challenge !

	food.shift();

> Last night

	food.push('hot water');
	
## Next day

Jack: Good morning Rose!  
Rose: Good morning.  
Jack: So you didn't had coffee last night ?  
Rose: Yes, I'm not. managed with Hot water  

	
	let lastNightFood = food[food.length - 1];
