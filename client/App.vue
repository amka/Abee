<template>
    <div class="column">
        <header>
            <h1>Abee, the Meteorite</h1>
        </header>

        <article>
            <h2>Welcome {{ user }}!</h2>
            <label>
                Your name: <input type="text" v-model="user" autofocus />
            </label>
        </article>
    </div>
</template>

<script>
export default {
    data: () => ({
        user: '%username%'
    })
}
</script>

<style>
header, article {
    text-align: center;
}

input {
    max-width: 250px;
}
</style>
