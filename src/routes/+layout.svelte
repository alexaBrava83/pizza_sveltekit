<script>
    import "../style/app.scss";
</script>

<header>
    <div class="container">
        <div class="logo">
            <img src="img/logo.png" alt="logo" class="icon" />
            <div class="info">
                <h3 class="digit-title">SVELTE PIZZA</h3>
                <p class="description">найсмачніша піца у всесвіті</p>
            </div>
        </div>
        <div class="button">
            <button class="btn orange">button</button>
        </div>
    </div>
</header>

<slot></slot>

<footer>
    <div class="container">Made by Sasha Pysaruk</div>
</footer>
