<main>
	<div class="result">
		<h3>Your Result</h3>
		<div class="result-score">
			<div class="scored">76</div>
			<div class="max-score">of 100</div>
		</div>
		<h2>Great</h2>
		<p>You scored higher than 65% of the people who have taken these tests</p>
	</div>
	<div class="summary">
		<h3>Summary</h3>
		<div class="classify reaction">
			<div class="classify-cover">
				<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" viewBox="0 0 20 20"><path stroke="#F55" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.25" d="M10.833 8.333V2.5l-6.666 9.167h5V17.5l6.666-9.167h-5Z"/></svg>
				<span class="classify-name">Reaction</span>	
			</div>
			<div>
				<span class="score">80</span>
				<span class="slash">/</span>
				<span class="max">100</span>
			</div>
		</div>
		<div class="classify memory">
			<div class="classify-cover">
				<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" viewBox="0 0 20 20"><path stroke="#FFB21E" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.25" d="M5.833 11.667a2.5 2.5 0 1 0 .834 4.858"/><path stroke="#FFB21E" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.25" d="M3.553 13.004a3.333 3.333 0 0 1-.728-5.53m.025-.067a2.083 2.083 0 0 1 2.983-2.824m.199.054A2.083 2.083 0 1 1 10 3.75v12.917a1.667 1.667 0 0 1-3.333 0M10 5.833a2.5 2.5 0 0 0 2.5 2.5m1.667 3.334a2.5 2.5 0 1 1-.834 4.858"/><path stroke="#FFB21E" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.25" d="M16.447 13.004a3.334 3.334 0 0 0 .728-5.53m-.025-.067a2.083 2.083 0 0 0-2.983-2.824M10 3.75a2.085 2.085 0 0 1 2.538-2.033 2.084 2.084 0 0 1 1.43 2.92m-.635 12.03a1.667 1.667 0 0 1-3.333 0"/></svg>
				<span class="classify-name">Memory</span>	
			</div>
			<div>
				<span class="score">92</span>
				<span class="slash">/</span>
				<span class="max">100</span>
			</div>
		</div>
		<div class="classify verbal">
			<div class="classify-cover">
				<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" viewBox="0 0 20 20"><path stroke="#00BB8F" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.25" d="M7.5 10h5M10 18.333A8.333 8.333 0 1 0 1.667 10c0 1.518.406 2.942 1.115 4.167l-.699 3.75 3.75-.699A8.295 8.295 0 0 0 10 18.333Z"/></svg>
				<span class="classify-name">Verbal</span>	
			</div>
			<div>
				<span class="score">61</span>
				<span class="slash">/</span>
				<span class="max">100</span>
			</div>
		</div>
		<div class="classify visual">
			<div class="classify-cover">
				<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" viewBox="0 0 20 20"><path stroke="#1125D6" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.25" d="M10 11.667a1.667 1.667 0 1 0 0-3.334 1.667 1.667 0 0 0 0 3.334Z"/><path stroke="#1125D6" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.25" d="M17.5 10c-1.574 2.492-4.402 5-7.5 5s-5.926-2.508-7.5-5C4.416 7.632 6.66 5 10 5s5.584 2.632 7.5 5Z"/></svg>
				<span class="classify-name">Visual</span>	
			</div>
			<div>
				<span class="score">72</span>
				<span class="slash">/</span>
				<span class="max">100</span>
			</div>
		</div>
		<button>Continue</button>
	</div>
</main>
<style>
@import url('https://fonts.googleapis.com/css2?family=Hanken+Grotesk:wght@500;700;800&display=swap');
	main {
		display: flex;
		font-family: 'Hanken Grotesk', sans-serif;
		font-size: 18px;
		box-shadow: 1px 1px 5px 1px rgba(0,0,0,0.15);
		border-radius: 1rem;
	}
	.result{
		text-align: center;
		border-radius: 1rem;
		background-image: linear-gradient(hsl(252, 100%, 67%), hsl(241, 81%, 54%));
	}
	.result h3 {
		color: hsl(241, 100%, 89%);
	}
	.result-score{
		width: 7rem;
		height: 7rem;
		border-radius: 50%;
		margin: auto;
		background-image: linear-gradient(hsla(256, 72%, 46%, 1), hsla(241, 72%, 46%, 0));
	}
	.scored{
		color: hsl(0, 0%, 100%);
		font-size: 42px;
		font-weight: bold;
		padding-top: 1rem;
	}
	.max-score{
		color: hsl(241, 100%, 89%);
		font-size: 14px;
		font-weight: 500;
	}
	.result h2 {
		color: hsl(0, 0%, 100%);
		font-weight: bold;
		font-size: 22px;	
	}
	.result p{
		color: hsl(241, 100%, 89%);
        font-size: 14px;
		padding: 0 2.5rem;
	}
	.result, .summary{
		width: 50%;
		padding: 2rem;
	}
	.summary h3{
		padding-left: 0.75rem;		
	}
	.classify{
		display: flex;
        justify-content: space-between;
		align-items: center;
		border-radius: 0.75rem;
		padding: 0.75rem;
		margin: 0.75rem;
	}
	.score, .classify-name{
		font-weight: 700;
	}
	.slash, .max{
		color: hsl(224, 30%, 27%);
	}
	.reaction{
		background:#fff6f5;
	}
	.memory{
		background:#fffbf0;
	}
	.verbal{
		background:#f2fbfa;
	}
	.visual{
		background:#f3f3fd;
	}
	.reaction .classify-name{
		color: hsl(0, 100%, 67%);		
	} 
	.memory .classify-name{
		color: hsl(39, 100%, 56%);		
	}
	.verbal .classify-name{
		color: hsl(166, 100%, 37%);		
	}
	.visual .classify-name{
		color: hsl(234, 85%, 45%);	
	}
	button{
		width: 100%;
		border-radius: 2rem;
		border: none;
		height: 3rem;
		color: hsl(0, 0%, 100%);
		background: #303b59;
		padding: 0 0.75rem;
		cursor: pointer;
	}
	@media screen and (max-width: 768px){
		main{
            flex-direction: column;
        }
		.result, .summary{
			width: 100%;
			padding: 0;
		}
    }
</style>