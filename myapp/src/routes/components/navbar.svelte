<script>

</script>

<nav class="navbar">
    <h1>svelteDaily</h1>

    <div class="menuPerfil">
        <p>Nome</p>
        <div class="avatar">F</div>
    </div>
</nav>

<style>
    *{
        margin: 0;
        padding: 0;
        list-style: none;
        box-sizing: border-box;
    }

    nav{
        color: #fff;
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        padding: 15px;
        background-image: linear-gradient(#077187, #32B194);
    }

    .menuPerfil{
        display: flex;
        align-items: center;
        gap: 10px;
    }

    .avatar{
        color: #000;
        width: 30px;
        height: 30px;
        border-radius: 50%;
        background: #fff;
        display: flex;
        align-items: center;
        justify-content: center;
    }
</style>