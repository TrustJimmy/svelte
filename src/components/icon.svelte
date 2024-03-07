<script>
    export let name;
    const icons = [
        {
        name:'check-mark',
        path: '<path>✅</path>',
        },
        {
        name:'delete',
        path: '<path>🗑️</path>',
        },
    ];
    let Icon = icons.find((item) => item.name === name);
</script>