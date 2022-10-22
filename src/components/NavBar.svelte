<script>

</script>

<nav>
 <!-- We're creating a navigation bar with 3 items: About, Experiences, Projects\-->

  <ol>  
     <section class="container__nav" id="/">
  <!-- the href=#something  links to each section so we can create a scroll to section feature\-->
      <li>
          <a href='#About' class="nav__item">
            About
          </a>
        </li>
      <li>
          <a href='#Experiences' class="nav__item">
            Experiences
          </a>
       </li>
      <li>
          <a href='#Projects' class="nav__item">
            Projects
          </a>
        </li>
      </section>
  </ol> 

</nav>

<style>
/* This is CSS style for our navigation bar */
   ol {
    list-style: none;
  }
  li {
    padding: 0;
  }
  .container__nav {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
  }
  .nav__item {
    color: white;
    font-weight: 600;
    font-size: 2rem;
    margin: 0 2rem;
    transition: all 400ms;
  }
  .nav__item:hover {
    color: rgb(0, 157, 255);
  }
  .time {
    color: #1a1a1a;
    font-weight: 700;
    background-color: #2C91C6;;
    padding: 0.35rem;
    margin: 0 2rem;
    border-radius: 12px;
  }
</style>