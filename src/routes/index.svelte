<script>
    import TodoItem from "$lib/todo-item.svelte";
    const title = "Todo";
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<form action="" method="">
    <input
        type="text"
        name="todo"
        id="todo"
        aria-label="Add a todo"
        placeholder="+ type to add a todo"
    />
</form>

<TodoItem />
