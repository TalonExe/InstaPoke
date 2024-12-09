<script>
let i = $state(0)

</script>

<div class="bg-black w-screen h-screen text-white flex justify-center align-center">
    <div>
    <h1>Welcome to SvelteKit</h1>
    <p>{i}</p>
    <button onclick={() => i++}>Increment</button>
    </div>
</div>
