<script>
    let props = $props();
</script>

<div class="flex flex-col justify-center items-center min-h-screen py-10">
    <h1 class="text-3xl font-extrabold">{props.grade}th Model Papers</h1>
    <div class="flex flex-wrap p-10 justify-center items-center gap-5">
        {#each props.paperLinks as paperLink}
            <div class="card w-80 bg-base-100 card-md shadow-sm border-1">
                <div class="card-body">
                    <h2 class="card-title">{paperLink.name}</h2>
                    {#if paperLink.practical && paperLink.practical === true}
                        <p class="text-emerald-500">
                            {paperLink.name} Practical Model Paper
                        </p>
                    {:else}
                        <p>
                            {paperLink.name} Theory Model Paper
                        </p>
                    {/if}
                    <div class="justify-end card-actions">
                        <a
                            href={paperLink.link}
                            class="btn btn-primary md:flex hidden">View</a
                        >
                        <a
                            href={paperLink.link}
                            class="btn btn-primary md:hidden flex">Download</a
                        >
                    </div>
                </div>
            </div>
        {/each}
    </div>
</div>
