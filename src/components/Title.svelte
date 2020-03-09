<script>
  // logic goes here
  export let text = 'This is a Title Component';
  let className;

	// creates a `class` property, even
	// though it is a reserved word
	export { className as class };
</script>

<!-- markup (zero or more items) goes here -->
<div class='{className} text-5xl leading-tight tracking-wide' >{text}</div>