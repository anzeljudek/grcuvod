<script>
	let name = 'Želve';
	let clicks = 0;

	function clicker() {
		clicks = clicks + 1;
	}
</script>

<div class="flex justify-center">
	<div class="  bg-blue-50 grid justify-items-center rounded-2xl m-10 p-10 shadow-2xl">
		<h1 class=" text-4xl">{name} x {clicks}</h1>
		<h2 class="italic">Testudines</h2>
		<p class=" grid justify-items-center px-10">
			Želve (znanstveno ime Testudines) so plazilci, za katere je značilno, da njihovo telo ščiti
			koščen ali hrustančen oklep iz 60 kosov, ki je nastal iz preobraženih reber. Danes poznamo
			okoli 300 živečih vrst želv, mnoge od katerih so zaradi počasnega premikanja in dolgega
			generacijskega časa kritično ogrožene. Skupina je poznana tudi po fosilnih ostankih izumrlih
			predstavnikov, najstarejši izmed katerih so stari okoli 210 milijonov let in dokazujejo, da so
			želve ena najstarejših skupin plazilcev, starejša od kač, kuščarjev in celo krokodilov.
			<img class="rounded-md w-96" src="Haeckel_Chelonia.jpeg" />
			<button
				class=" bg-yellow-600 hover:bg-yellow-500 text-2xl mt-2 rounded-md w-96"
				on:click={clicker}>PREBERI VEČ</button
			>
		</p>
	</div>
</div>
