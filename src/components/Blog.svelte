<script>
import Article from "./Article.svelte";
export let articles;
</script>


<div class="flex items-center flex-col">
	{#each articles as article}
		<Article nsfw={article.nsfw} title={article.title} url={article.urlto} date={article.date} content={article.desc}/>
	{/each}
</div>