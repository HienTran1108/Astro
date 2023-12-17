<script lang="ts">
import {createEventDispatcher} from 'svelte';
export let titleButton: string | undefined;
const dispatch = createEventDispatcher();
</script>
<button 
    class="w-[200px] h-[52px] p-3 mt-4 border-2 border-orange-500 rounded-md font-bold font-roboto text-orange-500 hover:bg-orange-500 hover:text-white transition-colors duration-300 ease-in-out">
    {titleButton}
</button>