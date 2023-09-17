<script lang="ts">
    import CodeSnippetCard from "../CodeSnippetCard.svelte";
</script>

<div class="flex justify-center ">
	<div class="grid grid-cols-1 gap-4 min-w-full md:min-w-[750px]">
		<h3 class="text-center py-6">
			Create a Code Snippet
		</h3>
		<div class="card p-4 w-full text-token space-y-4">
			<label class="label">
				<span class="label-text">Snippet Title</span>
				<input type="text" class="input" placeholder="Enter title here...">
			</label>
			<label class="label">
				<span class="label-text">Programming Language</span>
				<select class="select select-bordered w-full">
					<option value="html">HTML</option>
					<option value="css">CSS</option>
					<option value="js">JavaScript</option>
					<option value="ts">TypeScript</option>
					<option value="php">PHP</option>
					<option value="py">Python</option>
					<option value="java">Java</option>
			</label>
			<label for="" class="label">
				<span class="label-text">Code Snippet</span>
				<textarea class="textarea h-24 textarea-bordered" placeholder="Enter code here..."></textarea>
			</label>
		</div>
		<div class="text-center py-6">
			<h2>My Code Snippets</h2>
		</div>
		<CodeSnippetCard />
	</div>
</div>