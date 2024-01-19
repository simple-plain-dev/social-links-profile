<script>
  import avatar from "$lib/assets/images/avatar-jessica.jpeg"
</script>

<article class="card">
  <header class="profile">
    <img src={avatar} alt="jesica avatar" >
    <h1>Jessica Randall</h1>
    <h4>London, United Kingdom</h4>
    <p>"Front-end developer and avid reader"</p>
  </header>
  <section class="social-list">
    <button>Github</button>
    <button>Frontend Mentor</button>
    <button>LinkedIn</button>
    <button>Twitter</button>
    <button>Instagram</button>
  </section>
</article>

<style>
  /* Layout */
  .card {
    background-color: var(--clr-neutral-3);
    border-radius: 1rem;
    overflow: hidden;
    /* margin-inline: 1rem; */
    padding: 2rem;
    margin: 2rem;
    max-width: 30rem;
    display: grid;
    grid-template-rows: 2fr 3fr;
    text-align: center;
  }

  .profile {
    display: grid;
    gap: 0.8rem;
    justify-items: center;
  }
  
  .social-list {
    margin-top: 1rem;
    display: grid;
    gap: 1rem;
    /* align-items: center; */
    /* padding: 2rem; */
  }

  /* Component */
  img {
    border-radius: 50%;
    width: 40%;
  }

  h4 {
    color: var(--clr-primary-1);
  }

  p {
    font-size: small;
  }

  button {
    border-radius: 0.5rem;
    background-color: var(--clr-neutral-2);
    border: transparent;
    color: var(--clr-neutral-1);
    font-weight: var(--fw-bold);
  }

  button:hover{
    background-color: var(--clr-primary-1);
    color: var(--clr-neutral-2)
  }
  
</style>