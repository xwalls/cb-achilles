<script type="ts">
  import { Meta, Template, Story } from "@storybook/addon-svelte-csf";
  import TextInput from "./TextInput.svelte";
</script>

<Meta
  title="Components/TextInput"
  component={TextInput}
  argTypes={{
    label: { control: "text" },
    value: { control: "text" },
    onKeyup: { action: "onKeyup" },
    helptext: { control: "text" },
  }}
/>

<Template let:args>
  <TextInput {...args} on:keyup={args.onKeyup} />
</Template>

<Story
  name="Without Helptext"
  args={{
    label: "Test Label",
    value: "1.223",
    helptext: "",
  }}
/>