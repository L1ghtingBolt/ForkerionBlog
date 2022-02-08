<script>
import Article from "./Article.svelte";
export let articles;
</script>


<div class="flex justify-center">
	{#each articles as article}
		<Article title={article.title} url={article.urlto} date={article.date} content={article.desc}/>
	{/each}
</div>