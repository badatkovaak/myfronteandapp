<script>
    let count = 0
    function increment(){
        count += 1
    }
    $: double = count * 2 

</script>
<div>Count Is {count}</div>
<div>Double Count Is {double}</div>
<button on:click={increment}>+</button>

<style></style>

