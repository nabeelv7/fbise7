<script>
    let statement = "Hello, which class are you from?";
    let saidStatement = $state("");
    let face = $state("😃");

    let buttons = $state(false);

    let index = 0;
    async function typeText() {
        if (index < statement.length) {
            if (face == "😃") {
                face = "😦";
            } else if (face == "😦") {
                face = "😮";
            } else if (face == "😮") {
                face = "😦";
            }
            saidStatement += statement.charAt(index);
            index++;
            if (index === statement.length) face = "😃";
            await setTimeout(typeText, 70);
        } else {
            buttons = true;
        }
    }

    setTimeout(async () => {
        await typeText();
    }, 400);
</script>

<div class="overflow-hidden">
    <div
        class="flex flex-col justify-center items-center min-h-screen text-4xl md:scale-120"
    >
        <div class="flex md:flex-row flex-col gap-5">
            <div class="flex flex-col">
                <h1 contenteditable="false">{face}</h1>
                <h1 contenteditable="false">/ | \</h1>
                <h1 contenteditable="false">&nbsp;/ \</h1>
            </div>

            <div class="flex flex-col">
                <div
                    class="bg-white p-5 rounded-md md:rounded-bl-none md:rounded-tl-md rounded-tl-none text-black"
                >
                    <p
                        class="text-sm"
                        contenteditable="false"
                    >{saidStatement}</p>
                </div>
                {#if buttons}
                    <div class="flex justify-between py-3 gap-2">
                        <a href="/9" class="btn btn-accent">9th</a>
                        <a href="/10" class="btn btn-accent">10th</a>
                        <a href="/11" class="btn btn-accent">11th</a>
                        <a href="/12" class="btn btn-accent">12th</a>
                    </div>
                {/if}
            </div>
        </div>
        <p class="text-sm fixed md:bottom-30 bottom-20">
            Made by <a
                class="text-blue-500 hover:underline"
                target="_blank"
                href="https://github.com/nabeelv7">Nabeel</a
            >
        </p>
    </div>
</div>
