<template>
    <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
    </div>
    <router-view />
</template>
<style lang="scss">
#nav{
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>
