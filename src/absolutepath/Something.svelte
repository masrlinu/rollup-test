<script context="module">
  export let variable = 0;
</script>
<script>
  export const add = ()=>{
    variable +=1;
    return variable;
  }
</script>

<div>same variable:{variable}!</div><br>