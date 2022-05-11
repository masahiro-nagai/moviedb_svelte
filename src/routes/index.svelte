<script context="module">
    export async function load({fetch}){
        const res = await fetch(`
https://api.themoviedb.org/3/movie/popular?api_key=<<api_key>>&language=en-US&page=1`)
    }
</script>