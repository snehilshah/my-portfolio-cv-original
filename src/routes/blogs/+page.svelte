<script>
	import PostList from '../../lib/PostList.svelte';

	export let data;
</script>

<h1 class="py-0 text-4xl sm:text-5xl mb-8">Blog</h1>

<PostList posts={data.posts} />
