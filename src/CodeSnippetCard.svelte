<script lang="ts">
    import { CodeBlock } from '@skeletonlabs/skeleton';
</script>


<div class="card">
    <header class="card-header">
        Title of Snippet
        <div class="float-right">
            <button type="button" class="btn btn-sm variant-filled-secondary">
                Favourite
            </button>
            <button type="button" class="btn btn-sm variant-filled-error">
                X
            </button>
        </div>
    </header>
    <section class="p-4">
        <CodeBlock language={"HTML"} code="{`<h1>Hello World</h1>`}"> </CodeBlock>
    </section>
</div>