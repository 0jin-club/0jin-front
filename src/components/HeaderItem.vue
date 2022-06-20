<template>
    <div id="header">
        <h1>영진</h1>
        <div id="header-list">
            <router-link to="/about">About</router-link>
            <router-link to="/activities">Activities</router-link>
            <router-link to="/Award">Award</router-link>
            <router-link to="/members">Members</router-link>
            <router-link to="/contact">Contact</router-link>
        </div>        
    </div>
</template>

<script>
export default {

}
</script>

<style>
#header {
    padding-top: 10px;
    padding-bottom: 10px;

    display: flex;
}
#header h1{
    flex: 1 1 auto;
}
#header-list {
    display: flex;
    align-items: center;
    gap: 10px;
}
#header-list a{
    text-decoration: none;
    color: rgb(133, 133, 133);
    transition: 0.1s;
}
#header-list a:hover{
    text-decoration: underline;
    color: black;
}
#header-list a:active{
    transform: translate(0, 2px);
}
</style>