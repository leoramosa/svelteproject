<style>
  .Share {
    border: 1px solid rgba(219, 219, 219, 1);
    border-radius: 4px;
    background-color: white;
    margin: 0 0 2em 0;
    width: 300px;

    position: absolute;
    top: 300px;
    left: 30%;
    z-index: 9;
    padding: 1em;
  }
  .Share-head {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .Share-head h2 {
    font-size: 16px;
  }
  .Share-head i {
    cursor: pointer;
  }
  .Share-content a {
    display: flex;
    align-items: center;
    text-decoration: none;
    color: black;
    font-size: 14px;
    margin: 2em 0 0 0;
  }
  .Share-content .icon-facebbok {
    color: #3b5998;
    margin: 0 0.5em 0 0;
    font-size: 20px;
  }
  .Share-content .icon-whatsapp {
    color: #1bd741;
    margin: 0 0.5em 0 0;
    font-size: 20px;
  }
</style>

<div class="Share">
  <div class="Share-head">
    <h2>Compartir</h2>
    <i class="fas fa-times-circle" on:click />
  </div>
  <div class="Share-content">
    <a
      href="https://www.facebook.com/sharer/sharer.php?&u=https://pugstagram.co"
      target="_blank">
      <i class="icon-facebbok fab fa-facebook-square" />
      Compartir en Facebook
    </a>
    <a
      href="https://api.whatsapp.com/send?&text=mira%20este%20hermoso%20pug%20https://pugstagram.co/"
      target="_blank">
      <i class="icon-whatsapp fab fa-whatsapp-square" />
      Compartir en Whatsapp!
    </a>
  </div>
</div>
