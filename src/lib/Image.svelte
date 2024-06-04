<script>
  export let src
  export let caption
  export let alt
</script>

<figure>
  <img {src} {alt} title={caption} />
  <figcaption>Photo taken by {caption}</figcaption>
</figure>
