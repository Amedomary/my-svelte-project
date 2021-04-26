<script>
  export let head;
</script>

<section>
  <h2 class="logo">{head}</h2>
  <h1>
    Все Тренеры и&nbsp;Корты <br /> по&nbsp; большому теннису <br /> в&nbsp;одном
    приложении
  </h1>
  <button>Скачать в App Store</button>
  <button>Скачать в Google Play</button>
  <button>Перейти на сайт</button>
</section>

<style>
  .logo {
    color: #fff;
    text-transform: uppercase;
    font-size: 2em;
    font-weight: 100;
    margin: 0;
  }

  section {
    text-align: left;
    border-radius: 16px;
    max-width: 980px;
    background-color: #121212;
    margin: auto;
    padding: 32px;
    background-image: url('../images/bg-black.jpg');
    background-size: cover;
    background-position: right;
		margin-bottom: 2rem;
  }

  h1 {
    color: #ffffff;
    font-size: 40px;
    line-height: 1.15;
    font-weight: 700;
    width: 50%;
  }

  button {
    background-color: #000;
    color: #fff;
    border: 1px solid #fff;
    border-radius: 4px;
    padding: 1rem;
    margin: 0 1rem 0 0;
  }
</style>
