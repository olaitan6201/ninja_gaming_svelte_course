<script>
    let title = 'Ninja Gaming Guides';

    const updateTitle = () => {
        title = "Some Other Title Content";
    }
</script>

<div class="index">
    <h2>{title}</h2>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quam debitis culpa harum excepturi nesciunt ea iste fugiat corrupti error incidunt fuga temporibus recusandae sapiente nisi, quia adipisci, ducimus est neque? Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus tempore recusandae porro debitis atque, voluptates doloremque deserunt sequi enim odio veritatis nulla minus eos aut rem harum, dolores quod dolorum. Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed vero magnam accusamus quia, suscipit iusto voluptatem quidem illo voluptate asperiores, tempore eligendi mollitia magni non nobis corrupti quis unde nostrum.</p>

    <input type="text" bind:value={title}>
    <button on:click={updateTitle}>Change Title</button>
</div>

<style>
    .index{
        text-align: center;
        display: block;
        margin: 20px auto;
    }
</style>