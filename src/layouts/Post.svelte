<script>
    export let title;
    export let date;
    export let author;
</script>

<div class="postContainer">
    <a href='/' class="block m-10 text-4xl font-bold underline decoration-orange-500 text-center">Forkerion Blog</a>
    <div class="w-full bg-gray-600 opacity-50 h-[2px]"></div>
    <div class="wrapper m-10">
        <h1 class="text-2xl mb-[-10px] text-gray-500">{date}</h1>
        <h1 class="text-5xl font-bold">{title}</h1>
        <h2 class="text-gray-500 text-lg mb-10">{author}</h2>
        <p><slot/></p>
    </div>
</div>
