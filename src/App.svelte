<script>  
	import Something1, {add1} from './absolutepath/Something.svelte';
	import Something2, {add2} from 'relativepath/Something.svelte';
	import Something3, {add3} from 'relativepath/Something.svelte';
</script>

<Something1 />
<Something2 />
<Something3 />