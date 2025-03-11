<script>
    import MenuIcon from '~icons/heroicons-outline/menu';


    let hasNavigationBeenOpen = false;
    
    const navagationLinks = [
        {href: "home", child: "Home"},
        {href: "books", child: "Books"},
        {href: "contact", child: "Contact"},
        {href: "child", child: "Child"}
    ]
</script>



<header>
    <nav class="flex justify-between">
        <p class="text-orange text-xl font-bold">cartoonify</p>
        <div class="@3xl:hidden">
            <MenuIcon class="text-3xl text-orange" />
            {#if hasNavigationBeenOpen}
                <div>
                    {#each navagationLinks as {href, child}}
                        <a {href}>{child}</a>
                    {/each}
                </div>
            {/if}
        </div>

        <!-- desktop links -->
        <div class="hidden gap-10 text-xl font-bold @3xl:flex">
            {#each navagationLinks as {href, child}}
                <a {href} class="hover:text-orange">{child}</a>
            {/each}
        </div>
    </nav>
</header>