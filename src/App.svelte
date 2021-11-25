<script>  
	import Something1, {add as add1} from './absolutepath/Something.svelte';
	import Something2, {add as add2} from 'relativepath/Something.svelte';
	import Something3, {add as add3} from 'relativepath/Something.svelte';

	add1();
	add2();
	add3();
</script>

<Something1 />
<Something2 />
<Something3 />