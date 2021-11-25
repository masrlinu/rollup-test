<script context="module">
  let variable = 0;
  export let add = ()=>{
    variable +=1;
    return variable;
  }
</script>

<div>same variable:{variable}!</div>