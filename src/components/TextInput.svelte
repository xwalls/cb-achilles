<script type="ts">
  import Textfield from "@smui/textfield/styled";
  import HelperText from "@smui/textfield/helper-text/styled";

  export let label = "Label";
  export let value = "";
  export let helptext = "";
</script>

<Textfield bind:value bind:label on:keyup>
  <HelperText>{helptext}</HelperText>
</Textfield>