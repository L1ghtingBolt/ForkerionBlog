<script>
	export let title;
	export let content;
	export let url;
	export let date;
	export let nsfw;
</script>


<article class="mb-10 border-[1px] p-10 rounded-lg border-gray-400 dark:border-gray-300 min-w-[420px] max-w-max">
    <h2 class="text-gray-500">{date}</h2>
	<a class="hover:underline {nsfw ? 'decoration-red-700' : 'decoration-orange-500'} font-bold text-2xl" href={`${url}`}>{title}</a>
	<p class="text-gray-600">{content} </p>
	<p class="text-red-600 text-right">{nsfw ? 'NSFW' : ''}</p>
</article>
