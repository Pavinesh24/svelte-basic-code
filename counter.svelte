<script>
var count=0
function increase()
{
count=count+1
}
function decrease()
{
count=count-1
}
function reset()
{
count=0
}
</script>

<h1>Counter</h1>

<h1>{count}</h1>
<button on:click={increase}>+</button>
<button on:click={decrease}>-</button>
<button on:click={reset}>Reset</button>


