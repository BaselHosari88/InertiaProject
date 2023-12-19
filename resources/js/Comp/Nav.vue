<template>
    <nav>
        <ul class="flex list disc space-x-5 list-inside bg-gray-300">

                <li>
                <Link  class="text-green-600 hover:underline" :class="{'font-bold underline text-red-400': $page.component=='Home'}" href="home">Home</Link>
            </li>
            <li>
                <Link class="text-green-600 hover:underline" :class="{'font-bold underline text-red-400': $page.component=='Users'}"  href="users">Users</Link>
            </li>
            <li>
                <Link  class="text-green-600 hover:underline" :class="{'font-bold underline text-red-400': $page.component=='Settings'}" href="settings">Settings</Link>
            </li>
        </ul>
    </nav>
</template>

<script>
import { Link } from '@inertiajs/vue3'

export default {
    components: { Link }
}
</script>

<style scoped>

</style>
