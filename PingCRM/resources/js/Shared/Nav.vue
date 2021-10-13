<template>
 <nav>
        <ul>
            <li><Link href="/">Home</link></li>
            <li><Link href="/users">Users</link></li>
            <li><Link href="/settings">Settings</link></li>
            <li><Link href="/logout" method="POST" as="button">Log Out</link></li>
        </ul>
    </nav>
</template>

<script>
    import { Link } from '@inertiajs/inertia-vue3';
    export default {
        components: { Link },
    };
</script>
