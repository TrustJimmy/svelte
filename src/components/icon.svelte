<script>
    export let name;
    const icons = [
        {
        name:'check-mark',
        path: '<path fill="currentColor">✅</path>',
        },
        {
        name:'delete',
        path: '<path fill="currentColor">🗑️</path>',
        },
    ];
    let Icon = icons.find((item) => item.name === name);
</script>