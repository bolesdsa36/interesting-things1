<script>
    import Header from "$lib/Header.svelte"
    import Nav from "$lib/Nav.svelte"
    import Footer from "$lib/Footer.svelte"  
  </script>
  <Header />
  
  
  <Nav />


  
  
  
    <main>
        <h2>Revolve around me dress in Emerald</h2>

        <section>
            <div class="columns">
                <div class="column">
                    <figure class="image is-128x128">
                        <a href="https://www.showpo.com/nz/revolve-around-me-dress-in-emerald.html">
                            <img src="ss.png" alt="dresss" />
                        </a>
                        
                    </figure>
                </div>
    
                <div class="column">
                    <h2>fvkajsbfnskf;jng;ajbdl</h2>
    
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                        Integer et libero ultricies, rhoncus velit nec, pharetra
                        diam. In in ligula id nibh placerat faucibus. Suspendisse
                        mattis malesuada purus sit amet interdum. Praesent rhoncus
                        metus quis scelerisque egestas. Aliquam egestas ac mi et
                        aliquet. Nullam in ipsum convallis, dignissim leo quis,
                        laoreet quam. Pellentesque fringilla mattis malesuada.
                        Nullam mattis elit eget elit porttitor eleifend. Phasellus
                        sit amet pretium neque.
                    </p>
                </div>
            
        </section>
  </main>
  <Footer />
  
  <style>
    /* LAYOUT */
    Header { grid-area: h; }
    Nav { grid-area: n; }
    main { grid-area: m; }
    Footer { grid-area: f; }
  
    :global(#svelte) {
      display: grid;
      grid: " n   n   " auto
            " h   h   " auto
            " m   m   " auto
            " f   f   " auto
            / 1fr 3fr ;
    }
  
    /* GLOBAL STYLES */
    :global(main) {
      padding: 2em 10em;
    }
  
    :global(h2) {
      font-size: 1.5em;
      font-weight: bold;
      margin-bottom: 1em;
    }
    
    section {

        margin-bottom: 10em;
    }

  </style>