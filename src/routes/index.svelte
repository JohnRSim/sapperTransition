<script>
	import { send, receive } from "crossfade";
	import { fade } from 'svelte/transition';
</script>

<style>
	h1,
	figure,
	p {
	  text-align: center;
	  margin: 0 auto;
	}

	h1 {
	  font-size: 2.8em;
	  text-transform: uppercase;
	  font-weight: 700;
	  margin: 0 0 0.5em 0;
	}

	h1 span {
	  position: relative;
	  display: inline-block;
	}

	figure {
	  margin: 0 0 1em 0;
	}

	img {
	  width: 100%;
	  max-width: 200px;
	}

	p {
	  margin: 1em auto;
	}

	@media (min-width: 480px) {
	  h1 {
	    font-size: 4em;
	  }
	}
</style>

<main>
<br /><br />
<div transition:fade>
	<h2>Recreate Page Transition Ghosting</h2>
	<ul>
		<li>Scroll all the way down the page.</li>
		<li>Select About link from the nav header.</li>
		<li>Select browser back - this will keep scroll position.
			<ul><li>Ghosting of elements can be seen based off scroll offset.</li></ul>
		</li>
		<li>Select Browser Forward / Back to recreate.</li>
	</ul>
</div>
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<h1>
  <span out:send="{{key: 'title'}}" in:receive="{{key: 'title'}}">INDEX PAGE</span>
</h1>

<figure>
	<img out:send="{{key: 'borat'}}" in:receive="{{key: 'borat'}}" alt='Meow' src='meow.png'>
	<figcaption>MEOW!</figcaption>
</figure>

<p out:send="{{key: 'text'}}" in:receive="{{key: 'text'}}">
  Hi I'm
	<strong>
		 <a href="https://twitter.com/buhrmidayo">buhrmi</a>
	</strong>
	and I made this for you.
	Come say hi.
</p>

</main>