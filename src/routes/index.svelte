<script>
  import TodoItem from "$lib/todo-component.svelte";

  const title = "TODO";
</script>

<svelte:head>
  <title>{title}</title>
</svelte:head>

<h1>{title}</h1>
<form method="" action="">
  <input
    type="text"
    name="text"
    aria-label="Add Todo"
    placeholder="+ Add TODO here"
  />
</form>

<TodoItem />
<TodoItem />
<TodoItem />
