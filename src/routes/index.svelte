<script>
	import Header from "$lib/Header.svelte";
	import Nav from "$lib/Nav.svelte";
	import Footer from "$lib/Footer.svelte";
</script>

<Header />

<Nav />

<main>
	<h2>Showpo's Top 3 Ball Dresses</h2>

	<p>Click the pictures below to explore Showpo's Top 3 Ball Dresses.</p>

	<section>
		<div class="columns">
			<div class="column">
				<figure class="image is-128x128">
					<a href="https://www.showpo.com/nz/marlena-dress-in-blue.html">
						<img src="photo.png" alt="dresss" />
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
		</div>
	</section>
	


	<section>
		<div class="columns">
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
		
			<div class="column">
				<figure class="image is-128x128">
					<a href="https://www.showpo.com/nz/revolve-around-me-dress-in-emerald.html">
						<img src="ss.png" alt="of-dress2" />
					</a>
					
				</figure>
			</div>
		</div>
	</section>
	<section>
		<div class="columns">
			<div class="column">
				<figure class="image is-128x128">
					<a href="https://www.showpo.com/nz/waiting-so-long-dress-in-pink-floral.html">
						<img src="sss.png" alt="dresss" />
					</a>
					<figcaption>This is a dress</figcaption>
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
		</div>
	</section>











</main>

<Footer />

<style>
	/* LAYOUT */
	:global(Header) {
		grid-area: h;
	}
	:global(Nav) {
		grid-area: n;
	}
	:global(main) {
		grid-area: m;
	}
	:global(Footer) {
		grid-area: f;
	}

	:global(#svelte) {
		display: grid;
		grid:
			" n   n   " auto
			" h   h   " auto
			" m   m   " auto
			" f   f   " auto
			/ 1fr 3fr;
	}

	/* GLOBAL STYLES */
	:global(main) {
		padding: 1em 3em;
		font-family: "Poiret One", cursive;
	}

	:global(h2) {
		font-size: 1.5em;
		font-weight: bold;
		margin-bottom: 1em;
		font-family: "Old Standard TT", serif;
	}

	section {
		margin-top: 10em;
		margin-bottom:10em;
	}
	img {

		margin-left:10em;
		margin-bottom:10em;
	}
</style>
