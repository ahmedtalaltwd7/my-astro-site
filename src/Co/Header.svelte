<script>

import { setContext } from "svelte";
import Usr from './Duser.svelte';
const usrname = "Ahmed"
   setContext('twd',usrname)
   

</script>

<h1><Usr/></h1>


