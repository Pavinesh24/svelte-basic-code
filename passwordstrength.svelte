<script>
var password=""
var strength=""
function checkStrength()
{
if(password.length >10 && /\d/.test(password))
{
strength="Strong"
}
else if(password.length>=6)
{
strength="Medium"
}
else
{
strength="Weak"
}
}
</script>
<h1>Enter your password</h1>
<input type="password" bind:value={password} on:input={checkStrength} placeholder="Enter password"/>
<h2>{strength}</h2>
